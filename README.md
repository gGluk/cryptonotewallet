For Ubuntu 16.04 LTS

**1. Open terminal**

```
// open terminal on home directory
```

**2. Clone wallet sources**

```
git clone https://github.com/gGluk/intime_wallet.git
```

**3. Change directory `intime_wallet`**
 
```
cd intime_wallet
```

**4. Set symbolic link to coin sources at the same level as `src`**

```
ln -s ../intime cryptonote
```

**5. Build**

```
mkdir build && cd build && cmake .. && make
```


For Windows 10

**1. Open terminal**

```
// open terminal cmd.exe
```

**2. Create a folder in a convenient place for you, for example, the folder * git *.**

```
mkdir /mnt/d/git
```

**3. Go to the newly created folder**

```
cd /mnt/d/git/
```

**4. Clone wallet sources**

```
git clone https://github.com/gGluk/intime_wallet.git
```

**5. Change directory `intime_wallet`**
 
```
cd intime_wallet
```

**6. Set symbolic link to coin sources at the same level as `src`**

```
ln -s ../intime cryptonote
```

**7. Build**

```
mkdir build && cd build && cmake .. && make
```
