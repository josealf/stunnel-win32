# stunnel-win32

<b>What is this?</b>

This is a user provided binary release of Michal Trojnara's Stunnel TLS Proxy software compiled for Windows 32-bit.

<b>Why is this needed?</b>

The official stunnel.org site no longer provides 32-bit binaries for Windows. This is provided as a convenience for stunnel users.
 
 <b>How does this differs form the official installer?</b>
 
 The software should be mostly compatible with the official binaries. The binaries for Stunnel and OpenSSL were generated with GCC 8.3.0 or later for i686 architecture. Small tweaks were made to the NSIS install script to accommodate DLL file name changes. Also, I stick to a supported LTS release of OpenSSL. Starting with Stunnel 5.80 I am using 3.5.x branch as 3.0.x branch enters end of free support in September 7th 2026. Other historical versions used older LTS branches (1.1.1 and 1.0.2).

 Once in a while, new experimental builds will be published. The first is one is 5.78.3. I named the installer file stunnel-win32-5.78.<b>3</b>.testing-openssl-3.0.20-installer.exe. This special build includes UI and other minor enhancements that are not in the official Stunnel software. See [the experimental notes here](https://github.com/josealf/stunnel-win32/blob/master/README-EXPERIMENTAL.md)

<b>Which Operating System does it work on?</b>

Version 5.72 with OpenSSL 3.0.14 or later should work on Windows XP/2003 and later. This can be useful to help secure services in legacy systems that cannot be easily upgraded. If you have trouble running under on a legacy OS, open an issue and I will do my best to help. I am also available for freelance work.

<b>Know Issues:</b>

 You must be aware that some antivirus products flag my stunnel installers as malicious or potentially unwanted applications (PUA). As of August 28th, 2026 we find that 2 out of 70 antivirus engines registered in virustotal.com are flagging the latest installer (version 5.80) as dangerous or a potentially unwanted application. Of course, this is a false positive notice because there is no malware on these binaries. In some cases this is because my binaries are not digitally signed (fixing this requires purchasing a code signing certificate), in others there is a machine learning algorithm involved.
