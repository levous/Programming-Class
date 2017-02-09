Setting Up on Windows 10
========================

Microsoft has provided the *“Windows Subsystem for Linux”* environment with Windows 10.  Using this will make developing on Windows, Linux or Mac almost identical.  There are *Windows ways* to accomplish the same thing if you are a Windows loyalist and prefer to use those tools and techniques.  For our purposes, we're going to favor the Linux approach since it's available and will remove the concern for which operating system you have from our list of complications (in theory).

* Make sure you have the *Windows 10 Anniversary Update*.  Note: 64bit Windows 10 is required
* Open the *Settings* app
  * Follow *Update & Security > For Developers*
  * Activate the “Developer Mode” switch
  ![Windows Update &amp; Security][winUpd]
* Open the *Control Panel*
  * Click *Programs*
  * Click *Turn Windows Features On or Off* under *Programs and Features*
  * Enable the *Windows Subsystem for Linux (Beta)* option in the list and click *OK*
  * You’ll be prompted to reboot your computer. Click *Restart Now* to reboot your computer and Windows 10 will install the new feature
  ![Windows Subsystem for Linux][winSubSys]
* Click the *Start* button
  * type `bash`
  * press *Enter*




[winUpd]: windowsUpdateAndSecurity.png
[winSubSys]: windowsSubSysLinux.png
