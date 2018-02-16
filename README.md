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
