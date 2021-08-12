# KDMapper without allocating memory in BigPoolTable

Original creator https://github.com/z175

Improved by https://github.com/TheCruZ

run kdmapper.exe in admin CMD to see it's arguments, in order to not be in BigPoolsTable the argument is --mdl. If you want to free the allocated memory after execution use --free!

If you would like to use a GUI for kdmapper that shows you example entry point refer to https://www.unknowncheats.me/forum/anti-cheat-bypass/465064-kdmapper-gui-modified-version-allocates-pages-mdl.html

Please note I've taken the code from TheCruz and updated it so that it doesn't allocate any memory in the BigPoolTable (if --mdl argument is passed), if there is some code I could've written better please let me know since I'm always willing to improve. Please note that your mdl address is passed to the first argument of your driver entry so you can clean the pfn easily. Also credits to the original creator of kdmapper z175

please note TheCruz had merged my repo and improved the code, I then took this code and added a few more things to it.

Tested from **Windows 10 1607** to current **Windows 11 22000** :heavy_check_mark:


Credits: z175, TheCruz
