# TorRecentVersion
Just install recent tor version on Ubuntu Yakkety /16.10/

Setup key with:  
`gpg --keyserver keys.gnupg.net --recv 886DDD89`
`gpg --export A3C4F0F979CAA22CDBA8F512EE8CBC9E886DDD89 | sudo apt-key add -`

Setup repository with:  
`sudo sh -c 'echo "deb http://deb.torproject.org/torproject.org/ yakkety main" >> /etc/apt/sources.list.d/tor.list'`

Run:  
`apt update`
`apt upgrade`

You are done :)
