Forked from http://code.google.com/p/django-saml2-sp/
=====================================================

Authenticate users for your Django web app against a SAML 2.0 Identity Provider.

This is a companion project to the Django SAML 2.0 Identity Provider app @ http://django-saml2-idp.googlecode.com.

NOTE: This is targeted for Django 1.2.1. For other versions, YMMV.

Run the demo sponsored by Anderson Innovative, LLC at https://idpdemo.andersoninnovative.com/. The demo is running code under tag "demo2".

buildout
----------------------
If you are using buildout to install packages install saml2idp from PyPI and install the saml2sp package from this repo here.

Attributes
----------------------
In case SP needs additional data to create/update/authenticate the user based on the SAML response, Attributes must be used ([Documentation](https://www.oasis-open.org/committees/download.php/27819/sstc-saml-tech-overview-2.0-cd-02.pdf)).

To add custom attributes see `saml2idp.demo.AttributeProcessor` for an example.
