#IndexError

An attempt to make Python's IndexError exception strings more useful  
This project is still a work in progress  

###Files and folders  

 `python-2.7.10` Contains Python's modified source code (Plus i386 x86 binaries for linux)  
 `slides` contains a ipython notebook with the presentation of the project  
 `indexerror.patch` applies all the changes to the python 2.7.10 source from python.org

###Compiling  

* go to `python-2.7.10` and run the `configure` script
* run `make` to compile the source code

If you just want to try it out, you can launch the compiled binary with `./python` to get the interpreter  
This is not the same as launching `python` from your console. Make sure you are launching the binary in the `python-2.7.10` folder  

If you try to install this in your system, do so at your own risk
