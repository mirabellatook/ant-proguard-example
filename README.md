Steps to produce the class files: 

ant build
ant obfuscate

jar file will be within the output directory.  To unpack the jar file, just use the following command: 

jar xvf library_out.jar  

then run strings on the two class files that are produced to see the enumerated files.  

This was run with the latest proguard (v5.3.3) at the time
