# LearningTorch
The Journey begins!

## Issues and Solutions

### Failed Installing Dependency [Installing iTorch]
```
Error: Failed installing dependency: https://raw.githubusercontent.com/rocks-moonscript-org/moonrocks-mirror/master/luacrypto-0.3.2-2.src.rock - Could not find header file for OPENSSL
```

#### Solution

```
sudo apt-get install -y libssl-dev
luarocks make
```
