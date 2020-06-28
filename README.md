# My kubernetes playground (managed k8s in DigitalOcean)

This repo contains examples/tests/POCs for a managed kubernetes cluster in Digital Ocean

# To explore the repo, you must have the ff clis

1. doctl  
   digitalocean's cli
1. kubectl  
   the kubernetes command line tool

# To understand this repo, you have to at least know the ff

1. containerization  
   I use `docker`, alternative includes CoreOS' `rkt` (rocket)
1. container registry  
   I am using (dockerhub)[https://hub.docker.com]
1. BASH/SH/ZSH (your shell of choice)
1. `git`, for obvious reasons
1. you must have a containerable application  
   most of my examples use, `nodejs`, sometimes, `deno`
