# wrangler

Compilation Using Google Closure Compiler
(https://developers.google.com/closure/compiler/)
------------

Download the Closure Compiler file (https://dl.google.com/closure-compiler/compiler-latest.zip) to the working directory and save it as `closure-complier`

To run the compiler successfully, make sure you have the latest version of Java installed. You can check by typing in the command line: 

    $> java -version
    
Now that assume you have Closure Compiler saved to the working directory, you can run

    $> java -jar closure-compiler.jar --js file_to_be_compiled.js --js_output_file out.js
    
to compile file_to_be_compiled.js into out.js

out.js is the compiled version of the original source, it could be unreadable at the moment.

If you need more formatted text version, add `--formatting PRETTY_PRINT` flag to the original command before compiling
