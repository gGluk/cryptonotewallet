**1. Clone wallet sources**

```
git clone https://github.com/gGluk/cryptonotewallet.git
```

**2. Modify `CryptoNoteWallet.cmake`**
 
```
set(CN_PROJECT_NAME "intime")
set(CN_CURRENCY_DISPLAY_NAME "inTime")
set(CN_CURRENCY_TICKER "ITM")
```

**3. Set symbolic link to coin sources at the same level as `src`. For example:**

```
ln -s ../intime cryptonote
```

Alternative way is to create git submodule:

```
git submodule add https://github.com/gGluk/intime.git cryptonote
```

Replace URL with git remote repository of your coin.

**4. Build**

```
mkdir build && cd build && cmake .. && make
```
