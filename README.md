# XOM_Valuation
Availalbe is a Valuation project for ExxonMobil that I completed for one of my graduate courses.

# A note on Excel files and Macros
Excel files with the extenstion **xlsm** are macro enabled workbooks. Macros can include malicous code [(and more than ever this fact is exploited)](https://www.fortinet.com/blog/threat-research/microsoft-excel-files-increasingly-used-to-spread-malware.html). Please note that the main file of this project uses Macros. If you do not wish to enable macros, I have provided an **xlsx** version of the same file which does not conatin any Macros. Please be aware the **xlsx** version can produce highly inaccurate results because it does not contain the macro to rebalance.

## Getting the Macro Version to work:
Before downloading the file **XOM Project Macro Version** you will need to set up a trusted file location on your computer.

1. Open a blank excel file.
2. Select **File**, then at the bottom (you may have to scroll) select **Options**. A window will open up.
3) On the left hand side of this window select **Trust Center**, then select **Trust Center Settings...** a new window will open.
4) On the left hand side of this new window select **Trusted Locations**
5) At the bottom select **Add new location...** Another smaller window will pop up.
6) Select **Browse...** and select the file location you'd like to use (like your desktop).
7) Select **Ok**.

Now download the file and move it to this trusted location.

When you are done and want to remove the trusted file location, repeat steps 1 to 4, then click on the path under user locations and then select **remove**.
