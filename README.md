# MageStack Varnish

Simple Varnish module for Magento to provide admin controlled, URI-based exceptions (with regex support). This module should be used alongside the respective guides,

 - [Magento 1](https://www.sonassi.com/help/performance/implementing-varnish)
 - [Magento 2](https://www.sonassi.com/help/performance/implementing-varnish-magento-2)

## Installation

 1. Download and extract the module

    ~~~~
    wget -O master.zip -no-check-certificate https://github.com/sonassi/magestack-varnish/archive/master.zip
    unzip master.zip
    rsync -vPa magestack-varnish*/app/ app/
    rsync -vPa magestack-varnish*/lib/ lib/
    rm -rf magestack-varnish* master.zip
    ~~~~

1. Follow the installation steps for your respective Magento installation

    - [Magento 1](https://www.sonassi.com/help/performance/implementing-varnish)
    - [Magento 2](https://www.sonassi.com/help/performance/implementing-varnish-magento-2)
