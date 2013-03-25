Bitcommerce - Enterprise eCommerce for Postgresql, FireBird, and MySQL
===========

*If you are looking for production quality version of Zencart or Magento that will run on Postgresql, Bitcommerce is your answer.*

It is an extensive fork of http://www.zen-cart.com. Many, many improvements have been made to create a modern commerce system that can support thousands of products, production options, and users. It supports **both MySQL, PostgreSQL and Firebird** databases. Much of Bitcommerce was written by die-hard postgres fans, so its postgresql support is actually tested first.

Key features of Bitcommerce is that it is a true e-commerce system built on top of a CMS and web Framework. This allows easy integration of digital content with purchases, as well as full support for physical item sales.

At it's core, Bitcommerce is built for customization - which means adding and removing code as necessary.

Full documentation can be found at http://www.bitcommerce.org

## But does it, ya know, work?

http://www.viovio.com/shop/

## Say Hello!

There is much to do, and we need your help. Drop by our **IRC channel** at irc://freenode.net/#bitweaver and say hello.

Bitcommerce master project that will keep all of the submodules. After cloning, you will need to pull in all of the submodules with the following command:

## Installation

``` bash
cd bitcommerce
# Yes, we have a few submodules that have their own submodules
git submodule foreach --recursive git update --init
# We also recommend checking out the most recent versions of all sources with:
git submodule foreach --recursive git checkout master
```

After cloning, install pointing your web browser to http://example.com/install/install.php (for a site installed at the DocumentRoot. Subdirectories will work fine)

## Nifty Features you should know about
* High compatibility with all Zen-cart modules. A few tweaks, and most plugins can be easily integrated
* Vastly improved shop admin that enables efficient order processing
* Thorough reporting broken down by day/week/month/quarter/year with statistics broken down by product, customer referrals
