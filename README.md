# stunnel-win32

<b>What is this?</b>

This is a user provided binary release of Michal Trojnara's Stunnel TLS Proxy software compiled for Windows 32-bit.

<b>Why is this needed?</b>

The official stunnel.org site no longer provides 32-bit binaries for Windows. This is provided as a convenience for stunnel users.
 
 <b>How does this differs form the official installer?</b>
 
 The software should be mostly compatible with the official binaries. The binaries for Stunnel and OpenSSL were generated with GCC 8.3.0 or later for i686 architecture. Small tweaks were made to the NSIS install script to accomodate DLL file name changes.

<b>Know Issues:</b>

 You must be aware that some antivirus products flag my stunnel installers as malicious or potentially unwanted applications (PUA). As of December 13th, 2022 we find that 1 out of 71 antivirus engines registered in virustotal.com is flagging the latest installer as dangerous or a potentially unwanted application. Of course, this is a false positive notice because there is no malware on these binaries. In some cases this is because my binaries are not digitally signed (fixing this requieres purchasing a code signing certificate), in others there is a machine learning algorithm involved.
