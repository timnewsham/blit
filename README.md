
Blit terminal for Plan9Port.  The code is originally from 9front, http://code.9front.org/hg/plan9front/file/3595611ca650/sys/src/games/blit.
I only made changes to get it to build in plan9port (https://swtch.com/plan9port/).

To build and run (assuming you have V8 listening on port 8888):

```sh
    $ mk
    $ sudo mk install
    $ blit -t "tcp!localhost!8888"
```


For V8, see https://github.com/timnewsham/myv8.

