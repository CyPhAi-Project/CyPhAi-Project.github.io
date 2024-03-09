# CyPhAI-Project.github.io

Source code repositoy for the CyPhAI project website

## Develop locally

### Install Hugo

I use the command below on Ubuntu 20.04.

```bash
$ sudo apt install hugo
```

### Clone git repository and submodules

Assuming you have set up the SSH key for authentication,

```bash
$ git clone --recurse-submodules git@github.com:CyPhAi-Project/CyPhAi-Project.github.io.git
```

### Build website locally with Hugo

Add `--bind 0.0.0.0` to allow access from the host Windows machine if the website is in Window Subsystem for Linux (WSL).

```bash
$ hugo server  --themesDir themes/  --disableFastRender
```

You should be able to see the website at http://localhost:1313 in the web browser.
For WSL, replace "localhost" with the IP address of the WSL virtual machine.
