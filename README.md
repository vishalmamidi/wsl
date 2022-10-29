# wsl

## path
```
export PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```

## check wsl version 
```
wsl --list --all -v
```

## set default wsl 
```
wsl --setdefault Ubuntu-22.04
```




## create sudo user 

```
sudo adduser vishal
```
```
usermod -aG sudo vishal
```
```
groups vishal
```

```
ubuntu config --default-user vishal
```
