**For Ubuntu 16.04 LTS**

**1. Open terminal on home directory**

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

**6. Open**

//close the terminal and go to directory: home directory/intime_wallet/build and open cryptonote_wallet

//create the new wallet, set the password and copy your wallet adress

**7. Mining**

//paste your wallet adress in intime terminal

start_mining [your wallet adress] [threads=2]

Good luck!

**For Windows 10**

**1. Open terminal cmd.exe**

**2. Go to the directory**

```
cd /mnt/d/git/
```

**3. Clone wallet sources**

```
git clone https://github.com/gGluk/intime_wallet.git
```

**4. Change directory `intime_wallet`**
 
```
cd intime_wallet
```

**5. Set symbolic link to coin sources at the same level as `src`**

```
ln -s ../intime cryptonote
```

**6. Build**

```
mkdir build && cd build && cmake .. && make
```

**7. Open**

//close the terminal and go to directory: *d:/git/intime_wallet/build* and open cryptonote_wallet

//create the new wallet, set the password and copy your wallet adress

**8. Mining**

//paste your wallet adress in intime terminal

start_mining [your wallet adress] [threads=2]

Good luck!
