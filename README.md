# Skynet
A graphing calculator formula sheet for the AP Calculus AB course

## Warning:
**Use this program at your own risk.  We are not responsible for your calculator if you use this program.  For all you know we are mining Bitcoin on your calculator.  Only use it in situations where you are allowed to use it.**

## Installing Skynet to the Calculator:
Download the correct version of Skynet for your calculator.

Goto:
https://education.ti.com/en/software/details/en/B59F6C83468C4574ABFEE93D2BC3F807/swticonnectsoftware#lightbox=TI-Connect-TI-Connect-CE

Select the correct version for your calculator and install it to your computer.  Plug in your calculator to your computer.  Press `Ctrl-M` and select all of the files.  **If you are using the TI-84 Plus or TI-84 Plus CE send the programs named Skynet Alpha, Skynet Beta, Skynet Charlie and Skynet Delta to Archive and the rest to RAM.  If you are using the TI-83 Plus send them all to RAM**

For the TI-83 Plus it does not have a USB port.  If you have the IO cord you can connect it to another calculator and transfer skynet using the link feature.  This is accessed in `2ND -> LINK`.  One calculator will be in receive mode and the other will send the programs.

### Using Skynet

Press PRGM and navigate to FORMULAS using the arrow keys.  Press ENTER twice.  Use a combination of arrow keys and the ENTER button to find the desired topic.  To close the program press enter again.  **DO NOT PRESS THE ON BUTTON, this will end the program prematurely.**  At best this will mess up your calculator's graph.  If this happens run the program called REBUILD.  This will restore your calculator to the ZDecimal window.  On the TI-84 Plus or TI-84 Plus CE version there will be unterminated assembly settings.  This could mess up your calculator.  Nothing concerning has been observed when this happens in practice, both on physical hardware and on an emulator.  Despite this there is the possibility for damage to occur to your calculator.

### GarbageCollect?

After using Skynet on the TI-84 Plus or TI-84 Plus CE there is the possibility that it will ask you to "GarbageCollect?"  This happens when the calculator needs to reorganize the archive.  Press 'yes'.  It will take a few seconds.  Not pressing yes could result in Skynet temporarily not working anymore.  If you wish you can GarbageCollect early to prevent it from happening when inconvenient, simply press `2ND -> 0 -> TAN` and select GarbageCollect from the menu and press enter.

### Quadratic Formula

The Quadratic Formula can be sent to the calculator in a similar manner to Skynet.  When used it will ask for A, B, and C terms.  It will automatically apply the quadratic formula and output the solutions as a fraction or decimal.

## Using Skynet on Other Calculators:
The programs have been used on physical copies of the TI-83 Plus, TI-84 Plus and TI-84 Plus CE.  If you have a similar model of calculator it is possible one of the versions will work for it.  It is recommended to try using one of the pre existing programs on the calculator to see if one works with yours.  There may be a number of encountered issues.  For the safety of your calculator it is recommended to experiment on an emulator.
### Messy UI
There is a chance that the UI will be messed up if the screen resolution is different on your calculator.  If this is the case the UI Scaler can be used to change how the information is displayed.  It is recommended to start with the TI-84 Plus or TI-83 Plus code as the TI-84 Plus CE code has already been scaled.  Start by having the TextXBias, the LineXBias and the LineYBias set to 1.  Then press `ZOOM -> 4 -> WINDOW` and copy the information to the excel document.  Delete everything in column A.  It will cause most of the document to go blank.  Using the TI Connect software copy and paste the code into column A.  Copy the entirety of the code in column Q into the TI connect software.  Make sure to not select the entire column, as it will paste thousands of extra lines into the document.  There might be some garbage at the end of the document; delete it.  Save it and upload to the calculator.

### Insufficient Archive
Some calculator models may have very little space in the archive and may not be able to fit Skynet Alpha, Skynet Beta, Skynet Charlie and Skynet Delta all into the archive.  If this happens try using TI-83 Plus code as the entirety of it is stored to RAM.

## Stuff for Nerds:

If you wish you can remove the section of the Skynet Hub that calls the assembly program.  If you then send the file Skynet Alpha, Skynet Beta, Skynet Charlie and Skynet Delta to RAM.  This will use more of your calculator's RAM but will speed the usage of Skynet by about half a second.
