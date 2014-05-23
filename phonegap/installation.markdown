# win7 with phonegap development environment 

## best instruction

http://docs.phonegap.com/en/3.2.0/guide_platforms_android_index.md.html#Android%20Platform%20Guide

### install list

`. java

http://www.oracle.com/technetwork/java/javase/downloads/index.html

### ant

http://ant.apache.org/bindownload.cgi
http://ant.apache.org/manual/install.html

### set 

Set environmental variables JAVA_HOME to your Java environment, ANT_HOME to the directory you uncompressed Ant to, 
and add ${ANT_HOME}/bin (Unix) or %ANT_HOME%/bin (Windows) to your PATH. See Setup for details.

```
set ANT_HOME=E:\ant
set JAVA_HOME=D:\Program Files\Java\jdk1.6.0_03
set PATH=%PATH%;%ANT_HOME%\bin


```


### install android sdk

http://developer.android.com/sdk/index.html


Append the following to the PATH based on where you installed the SDK, for example:

```
;C:\Development\adt-bundle\sdk\platform-tools;C:\Development\adt-bundle\sdk\tools
```
