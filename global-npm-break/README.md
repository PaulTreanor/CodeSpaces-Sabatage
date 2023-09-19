# How to break installing globally installed npm packages

I can't quite figure out how to incorporate this into the talk. 

### 1. Make npm dirs non-writable
``` bash
sudo chmod -w /usr/local/lib/node_modules
sudo chmod -w /usr/local/bin
```

### 2. Try to install something 
``` bash
npm i -g serverless
```

### 3. Revert permissions
```bash
sudo chmod +w /usr/local/lib/node_modules
sudo chmod +w /usr/local/bin
```