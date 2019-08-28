# sampleNodeCLI

Sample CLI module based on [this blog](https://medium.com/netscape/a-guide-to-create-a-nodejs-command-line-package-c2166ad0452e)

#### gist
+ Include `node` shebang in CLI file
+ Add `bin` entry in package.json mapping file to command
+ NPM will copy the program to system bin for global and `/node_modules/.bin` for local
+ Can use npm `link` for testing
