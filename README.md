# CodeSpaces-Sabatage

This repo is for code related to sabataging the local dev demo portion of my belfastJS talk. By binding processes to ports, ruining local envs, and messing with dependencies I will demonstrate that local dev environments are very fragile. 

## Setup

### 1. Bind port 
```bash
cd bind-port
sls offline
```

### 2. Break npm -g
1. Go to `./global-npm-break/README.md`
2. Remove permissions
3. Fix permissions - but have a good story to tell 

### 3. Set old node version
