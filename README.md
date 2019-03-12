# ipfs-privnet

Try the `docker-compose.yml` file to build a single peer in the public network first.

On Ubuntu 18.04, i got some message like:

 `Error: /data/ipfs is not writeable by the current user`

And, the same error while using the formal docker image `ipfs/go-ipfs`. 

! Even with a `sudo` permission and the param `--privileged` in docker.

So, use the command `sudo ./start.sh X` to create a private network of ipfs with X peers instead. But, the web UI on port 5001 is not usable yet.

`Damn the Linux?`