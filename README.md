# 4d-plugin-digidoc
Study of digidoc integration (not functional)

### Milestones

* [Using subclass of ``XmlConfCurrent`` to override the default hard-coded ``digidoc::Conf::TSLCerts()`` and ``digidoc::Conf::TSLUrl()``](http://open-eid.github.io/libdigidocpp/manual.html#CA-settings). 

### Issues

* The Trusted Services Store is always ``0``

```sh
2020-10-26T06:58:44Z I [X509CertStore.cpp:84] - Loaded 0 certificates into TSL certificate store.
ASiC_E.cpp:350 code(General) Failed to sign container.
SignatureXAdES_LT.cpp:228 code(General) Could not find certificate issuer 'emailAddress=keisuke.miyako@4D.com,CN=localhost,OU=support,O=4D,L=Setagaya,ST=Tokyo,C=JP' in certificate store.
```
