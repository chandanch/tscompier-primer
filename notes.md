Use `tsc -- init` to initalize the folder with default typescript configuration

By default, TS will assume the folder that contains the _tsconfig_ file as the root folder

Using `tsc` in command line will make TS to search for all files within the root folder and transpile to JS files

Use `tsc --watch` option to watch for TS file changes. with the --watch option TS will look for changes in TS file in the root folder and transpiles to JS files

In order ignore or exclude files from compilation by TS we can use the **exclude** property, which takes an array of files

We can specify the directory which contains the TS source files using the `rootdir` option

`outdir` instructs TS to output the transpiled files to a specific folder. TS preserves the folder structure after transpilation

`target` Used to specify and to set the JS Version for the emitted JS files
