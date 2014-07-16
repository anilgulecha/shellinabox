This is my fork of the ubuntu repo shellinabox, with some fixes.

  * Firefox/Chrome crash fixed.
  * Auto login enabled -- enable auto-login.
     - To set user and optional password and pause between entering the two
       set the 'u', 'p' and 'd' URL params. Default dealy is 2000 ms (2 second).
     - Ex: http://localhost/?u=test&p=pASword
           http://localhost/?u=test&p=pASword&d=5000


To build the debian binary run (after cding into the repository):
```
sudo apt-get install build-essential debhelper autotools-dev binutils libssl-dev libpam0g-dev zlib1g-dev
./configure
dpkg-buildpackage
```
Original Readme
---
Build the package according to the information in INSTALL, then refer to
to the shellinaboxd.1 manual page, or the shellinaboxd.ps PostScript file
for detailed documentation.
