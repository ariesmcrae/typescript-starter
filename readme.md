# Typescript starter

## How to re-create this project
`npm init`

`tsc --init`

`git init`

`npm install -g typescript`

`npm install -D rimraf`


## How to compile your ts files on the fly
From the command line, type `tsc -w`. 

This will watch and compile your your .ts files while you modify them.
It knows what files to monitor because you specified `rootDir` in `tsconfig.json`


## How to package your project
`npm run build`


## Notes
* `npm init` creates package.json

* `tsc --init` creates tsconfig.json

* Installing `typescript` globally will give you the `tsc` compiler.

* `rimraf` allows you to perform `rm -rf` command

* ts files live in `/src`. This is specified in `tsconfig.json rootDir`

* Compiled js files live in `/dist`. This is specified in `tsconfig.json outDir`