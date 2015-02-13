# Docker tutorial

Docker works a bit like the movie 'inception': you start wide awake, at the terminal of you computer. Typing `boot2docker` will start a daemon on your machine. This is like dropping you into the first level of dreaming. When you are in an environ boot2docker, you have access to a repository of docker **images**. These are different dreams you could possibly have.

    docker images

shows you what images you already pulled. Something like

    docker pull ubuntu:14.04

will bring down the ubuntu image from dockerhub to your boot2docker environment. In this case the 14.04 **tag** will be pulled. Next, you can instantiate a **container** from this image:

   docker run ubuntu:14.04

This doesn't really do much, because you didn't even pass a command for this container to do. It's essentially a blank dream.

If you want to experience the dream directly, you can do something like:

    docker run -ti ubuntu:14.04 bash

The `-ti` flags stand for 'TTY' () and 'interactive'. In this case it just means that your terminal will now be inside of this container. For example typing ls 




## 



## 

