# akiss

`akiss` is a daily-driver usable KISS Linux repository, containing a lot of packages.
Most of this is for personal use, but you can use it yourself too!

# How to use

1. Clone this repository:

```
git clone https://github.com/notcomplexsoftware/akiss /var/repo/akiss
```

2. Add this repository to your KISS_PATH:

```
export KISS_PATH="/var/repo/akiss/core:/var/repo/akiss/extra:/var/repo/akiss/x11:/var/repo/akiss/gui:$KISS_PATH"
```

You could also add this to your `/etc/profile`.

3. Update:

```
kiss update
```

4. (optional) Rebuild all packages:

```
cd /var/db/kiss/installed && kiss build *
```

5. You are ready to install packages!

# What's included

- A `core` repository for all core packages
- An `extra` repository for all extra packages
- An `x11` repository for X.org and some packages for it
- A `gui` repository for miscellaneous GUI apps
