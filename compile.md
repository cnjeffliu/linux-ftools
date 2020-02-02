执行aclocal，产生aclocal.m4文件
执行autoconf，生成configure文件
执行automake命令，产生Makefile.in： automake --add-missing
执行configure命令，生成Makefile文件
重新执行make 和 make install,一切顺利. 


通常用法：执行 linux-fincore --pages=false --summarize --only-cached * 即可，其中*代表查看任意文件的cache。也可以指定某个目录/*，表示该目录中的所有文件。或指定某个具体的文件。
