# cauliflower-ui

## Dependencies


### Node + NPM + Bower

> We require these to be globally installed for running scripts + installing dependencies

we recommend following their [official instructions](https://nodejs.org/en/download/package-manager/).

or follow these quick instructions for Debian/Ubuntu
```
curl -sL https://deb.nodesource.com/setup_4.x | sudo -E bash -
sudo apt-get install -y nodejs
```

Finally, install Bower globally
```
npm install -g bower
```


### Foundation-cli

> We use Foundation-cli for the development server, and to build the sources for production

We recommend following their [official instructions](http://foundation.zurb.com/sites/docs/installation.html#command-line-tool)

Or follow these quick instructions
```
npm install --global foundation-cli
```


### Site Dependencies

> These are dependencies are required for the running/building of the site.

Run these commands in the project directory
```
npm install
bower install
```


## Running

for development, we can use the foundation-cli watch, which will build the sources, launch a server, then monitor for
any changes you make + rebuild accordingly.
```
foundation watch
```

You can of course use ```gulp server``` (```gulp```), which will build the sources then serve them without monitoring
for changes.

Where applicable, you can run ```gulp build```, then serve the dist folder using whatever means you want.


## Building

For building, just run ```gulp build```, which will output everything in to the dist folder.

For building for production, do ```gulp build --production```, or ```foundation build```, which will minify
the CSS, JS and images.


## Updating Dependencies

TODO


## Coding Style

TODO


## Deployment

TODO


## Reporting Issues

TODO


## Submitting Patches

TODO


## About

The base of these sources based on the Foundation [zurb template](https://github.com/zurb/foundation-zurb-template)

TODO
