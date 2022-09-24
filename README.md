<!-- This content will not appear in the rendered Markdown -->

**Table of Contents**
- [Git tut](https://github.com/mghasemi19/git_tut/blob/main/README.md#git_tut)
- [Introduction](https://github.com/mghasemi19/git_tut/blob/main/README.md#introduction)
- [Docker Image](https://github.com/mghasemi19/git_tut/blob/main/README.md#docker-image)
- [Docker Container](https://github.com/mghasemi19/git_tut/blob/main/README.md#docker-container)
- [Footnote](https://github.com/mghasemi19/git_tut/blob/main/README.md#footnote)


# git_tut
This repo includes some useful Git tutorial commands which could be helful for beginners. I will try to add some docker commands/descriptions as well. 

## Introduction
**Docker** [^1] is a set of platform as a service products that use OS-level virtualization to deliver software in packages called containers. The service has both free and premium tiers. The software that hosts the containers is called Docker Engine. [Docker Doc](https://docs.docker.com/language/python/configure-ci-cd/) includes a great tutorial. [Docker image](https://github.com/mghasemi19/git_tut/edit/main/README.md#docker-image) and [Docker container](https://github.com/mghasemi19/git_tut/edit/main/README.md#docker-container) are the most important parts. [Cheatsheet](./cheat-sheet-v2.pdf) file in this repo.

## Docker Image
A Docker image is a file used to execute code in a Docker container. Docker images act as a set of instructions to build a Docker container, like a template. Docker images also act as the starting point when using Docker. An image is comparable to a snapshot in virtual machine (VM) environments. To build and run a `Docker image` one can use:
```
docker build --tag myimage
docker run -dp host_port:VM_port myimage
```

## Docker Container
Docker is a set of platform as a service products that use OS-level virtualization to deliver software in packages called containers. The service has both free and premium tiers. The software that hosts the containers is called Docker Engine. It was first started in 2013 and is developed by Docker,

1. First list item
   - First nested list item
     - Second nested list item

- [ ] Mercury
- [x] Venus
- [x] Earth (Orbit/Moon)
- [ ] https://github.com/octo-org/octo-repo/issues/740

## Footnote
Here is a simple footnote.

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.


