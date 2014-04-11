Java Opus Wrapper
=====================

This wrapper was created with https://code.google.com/p/jnaerator/ and sligthly adapted.

Binaries found here:

* https://github.com/JohnACarruthers/Aural/tree/master/Aural/Libs/64bit
* https://github.com/JohnACarruthers/Aural/tree/master/Aural/Libs/32bit
* http://packages.ubuntu.com/trusty/amd64/libopus0/download
* http://packages.ubuntu.com/trusty/i386/libopus0/download
* OSX binaries compiled by David Aggeler

How to use the opus wrapper:

Either get the "jar":http://tomp2p.net/dev/mvn/net/tomp2p/opus-wrapper/1.3/

or use maven with

```
<repositories>
  <repository>
    <id>tomp2p.net</id>
    <url>http://tomp2p.net/dev/mvn/</url>
  </repository>
</repositories>

...

<dependency>
  <groupId>net.tomp2p</groupId>
  <artifactId>opus-wrapper</artifactId>
  <version>1.3</version>
</dependency>
```
