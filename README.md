## PinguinoBase Eagle Library

Now in Eagle 7 format!

### Don't click on the files!

[Click here](https://github.com/PinguinoBase/Eagle-Libraries/zipball/master) to download this as a zip file.

### Installation

1. Open Eagle and select the **Control Panel** window.
2. Choose **Options** and from the drop down that appears, **Directories**.
3. Change the Libraries line from: **$EAGLEDIR/lbr** to something like:
  * `$EAGLEDIR/lbr:$HOME/Eagle/external_lbrs` (for OS X and Linux).
  * `$EAGLEDIR\lbr;$HOME\Eagle\external_lbrs` (for Windows).
4. Click **OK** to save your changes.
5. Eagle will prompt to create the directory if it does not already exist. Note the location and choose **Yes** to create the directory.
  * On OS X, `$HOME/Eagle/external_lbrs` changes to: `/Users/username/Eagle/external_lbrs/`
  * On Linux, `$HOME/Eagle/external_lbrs` changes to: `/home/User/username/Eagle/external_lbrs/`
  * On Windows, `$HOME\Eagle\external_lbrs` changes to: `C:\Users\username\Eagle\external_lbrs`
6. Find and open the **external_lbrs** folder. Unzip and drag **pinguinobase.lbr** into the new **external_lbrs** folder.
7. Restart Eagle. The library should be now be usable.
Al3x1s1408
