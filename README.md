# stunnel-win32

<b>What is this?</b>

This is a user provided binary release of Michal Trojnara's Stunnel TLS Proxy software compiled for Windows 32-bit.

<b>Why is this needed?</b>

The official stunnel.org site no longer provides 32-bit binaries for Windows. This is provided as a convenience for stunnel users.
 
 <b>How does this differs form the official installer?</b>
 
 The software should be mostly compatible with the official binaries. The binaries for Stunnel and OpenSSL were generated with GCC 7.3 or later for i686 architecture. Small tweaks were made to the NSIS install script to accomodate DLL file name changes.

<b>Know Issues:</b>

 You must be aware that some antivirus products flag my stunnel installers as malicious or potentially unwanted applications (PUA). As December 12, 3 out of 70 antivrus engines registered in virustotal.com erroneously flag the latest installer. Of course, I did not plant any malware on them. 
