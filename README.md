openshift-redland-cart
======================

https://github.com/commonsmachinery/openshift-redland-cart

Openshift cartridge providing the Redland RDF library and Python
bindings.


Deployment
----------

Adding the cartridge:

    rhc cartridge add https://raw.github.com/commonsmachinery/openshift-redland-cart/master/metadata/manifest.yml -a MY-APP

It is supposed to be deployed together with the primary
web_framework.


Using redland
-------------

Set the necessary environment variables:

    . ~/redland/bin/activate-redland

After that it should be possible to use e.g. the Python module:

    import RDF
