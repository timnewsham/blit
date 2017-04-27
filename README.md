Blit terminal for Plan9Port.  This is a port of code by aiju, 
originally from 9front, http://code.9front.org/hg/plan9front/file/3595611ca650/sys/src/games/blit.
I only made changes to get it to run properly in plan9port.

To build, install plan9port from https://github.com/9fans/plan9port (https://swtch.com/plan9port/) and execute the following
(assuming you have V8 listening on port 8888):

```sh
    $ mk
    $ sudo mk install
    $ blit -t 'tcp!localhost!8888'
```

When connected, log in and run `/usr/blit/bin/mux`.
To quit, hit the END key.

For V8, grab an image from
http://9legacy.org/download/unix/v8-simh.tar.bz2
or see https://github.com/timnewsham/myv8.

