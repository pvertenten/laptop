Laptop
======

Laptop is a script to set up an OS X laptop for development.

It can be run multiple times on the same machine safely (idempotent).

It installs, upgrades, or skips packages based on what is already installed on the machine.

Install
-------

Download, review, then execute the script:

```sh
curl --remote-name https://raw.githubusercontent.com/pvertenten/laptop/master/mac
less mac
sh mac 2>&1 | tee ~/laptop.log
```

Debugging
---------

Your last Laptop run will be saved to `~/laptop.log`. Read through it to see if
you can debug the issue yourself.
