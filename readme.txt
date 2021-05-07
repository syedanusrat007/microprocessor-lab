--- Installation of Wampserver ---
BEFORE proceeding with the installation of Wampserver, you must ensure that certain elements are installed on your system, otherwise Wampserver will absolutely not run, and in addition, the installation will be faulty and you need to remove Wampserver BEFORE installing the elements that were missing.
Make sure you are "up to date" in the redistributable packages VC9, VC10, VC11, VC13 and VC14

See --- Visual C++ Packages below.

--- Do not install Wampserver OVER an existing version, follow the advice:
- Install a new version of Wampserver: http://forum.wampserver.com/read.php?2,123606

If you install Wampserver over an existing version, not only it will not work, but you risk losing your existing databases.

--- Install Wampserver in a folder at the root of a disk, for example C:\wamp or D:\wamp. Take an installation path that does not include spaces or diacritics; Therefore, no installation in c: \ Program Files\ or C: \ Program Files (x86\

We must BEFORE installing, disable or close some applications:
  - Close Skype or force not to use port 80
  Item No. 04 of the Wampserver TROUBLESHOOTING TIPS:http://forum.wampserver.com/read.php?2,134915
  - Disable IIS
  Item No. 08 of the Wampserver TROUBLESHOOTING TIPS:http://forum.wampserver.com/read.php?2,134915

If these prerequisites are not in place, Press the Cancel button to cancel the installation, then apply the prerequisites and restart the installation.

--- Visual C++ Packages ---

The MSVC runtime libraries VC9, VC10, VC11 are required for Wampserver 2.4, 2.5 and 3.0, even if you use only Apache and PHP versions with VC11. Runtimes VC13, VC14 is required for PHP 7 and Apache 2.4.17

-- VC9 Packages (Visual C++ 2008 SP1)
http://www.microsoft.com/en-us/download/details.aspx?id=5582
http://www.microsoft.com/en-us/download/details.aspx?id=2092

-- VC10 Packages (Visual C++ 2010 SP1)
http://www.microsoft.com/en-us/download/details.aspx?id=8328
http://www.microsoft.com/en-us/download/details.aspx?id=13523

-- VC11 Packages (Visual C++ 2012 Update 4)
The two files VSU4\vcredist_x86.exe and VSU4\vcredist_x64.exe to be download are on the same page: http://www.microsoft.com/en-us/download/details.aspx?id=30679

-- VC13 Packages] (Visual C++ 2013[)
The two files VSU4\vcredist_x86.exe and VSU4\vcredist_x64.exe to be download are on the same page: https://www.microsoft.com/en-us/download/details.aspx?id=40784

-- VC14 Packages (Visual C++ 2015)
The two files vcredist_x86.exe and vcredist_x64.exe to be download are on the same page:
http://www.microsoft.com/fr-fr/download/details.aspx?id=48145
If you have a 64-bit Windows, you must install both 32 and 64bit versions, even if you do not use Wampserver 64 bit.
This is item number 20 of TROUBLESHOOTING TIPS of Wampserver: http://forum.wampserver.com/read.php?2,134915

