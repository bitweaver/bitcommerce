bitcommerce
===========

Bitcommerce master project that will keep all of the submodules. After cloning, you will need to pull in all of the submodules with the following command:

``` bash
cd bitcommerce
# Yes, we have a few submodules that have their own submodules
git submodule foreach --recursive git update --init
# We also recommend checking out the most recent versions of all sources with:
git submodule foreach --recursive git checkout master
```

After cloning, install pointing your web browser to http://example.com/install/install.php (for a site installed at the DocumentRoot. Subdirectories will work fine)
