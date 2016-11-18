# .laptop.local

Custom setup file intended to be used in conjunction with [Laptop by ThoughtBot](https://github.com/thoughtbot/laptop).

Save Custom .laptop.local
-------

Add this file to laptop root before starting Laptop:

```sh
cd ~; curl -O https://raw.githubusercontent.com/davidwickman/laptoplocal/master/.laptop.local
```

Install [Laptop by ThoughtBot](https://github.com/thoughtbot/laptop)
-------

Download, review, then execute the script:

```sh
curl --remote-name https://raw.githubusercontent.com/thoughtbot/laptop/master/mac
less mac
sh mac 2>&1 | tee ~/laptop.log
```
