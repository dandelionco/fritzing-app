DANDELION BUILD NOTE:

This program uses libgit2 and zlib to run. The builder/project/code SHOULD be set up correctly to compile with these. However, execution WILL fail unless you copy the zlibwinapi.dll and the libgit build output 
dll into the debug32/release32 folders that this QT compiler outputs to!