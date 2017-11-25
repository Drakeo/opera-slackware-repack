# opera-slackware-repack
this scipt is used to down load 
a prebuilt unmodified build of opera
it must be ran as root to set permissiond for 
opera-sandbox.

# ffmpeg restricted build opition
~~~
FFMPEG=YES ./opera.SlackBuild
or
FFMPEG=YES ./opera-developer.SlackBuild
~~~
opera-FFMPEG and  opera-developer-FFMPG 

this builds and uses the ffmpeg from google chromium source

this allows h264 video formats
~~~
builds on slackware 14.2 and "current Fri Jul 28"
build in 14.1 you must upgrade binutils from Slackware64-14.2
lftp -c 'open http://mirrors.kernel.org/slackware/slackware64-14.2/source/d/; mirror -c -e binutils'
~~~
to build in slackware 14.2 to ln -s /usr/lib64/libncurses.so.5.9 /usr/lib64/libtinfo.so.5
and current need install libtinfo http://www.slackware.com/~alien/slackbuilds/libtinfo/
then fix his package cd /lib or cd /lib64   ln -sf libncurses.so.5.9 libtinfo.so.5


this will build in qt4 or qt5
you will need to install ninja
~~~
any questions email me at flats_fixed@flatsfixedbicycles.com subjet opera ffmpeg.
