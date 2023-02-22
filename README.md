# Simple-Firefox-Menus
Make Firefoxes right-click menus simpler, beginner-friendlier and more practical for daily usage.

A UserChrome.css preset using [SimpleMenuWizard](https://github.com/stonecrusher/simpleMenuWizard) I use and recommend for everyone.

install:

Flatpak Firefox:
```
git clone https://github.com/trytomakeyouprivate/Simple-Firefox-Menus 
cd Simple-Firefox-Menus
mkdir ~/.var/app/org.mozilla.firefox/.mozilla/firefox/*.default-release/chrome
mv * ~/.var/app/org.mozilla.firefox/.mozilla/firefox/*.default-release/chrome/
rm -rf ~/Simple-Firefox-Menus
sed -i 's/stylesheets", false/stylesheets", true/g' ~/.var/app/org.mozilla.firefox/.mozilla/firefox/*.default-release/prefs.js
```

Native Firefox:
```
git clone https://github.com/trytomakeyouprivate/Simple-Firefox-Menus 
cd Simple-Firefox-Menus
mkdir ~/.mozilla/firefox/*.default-release/chrome
mv * ~/.mozilla/firefox/*.default-release/chrome/
rm -rf ~/Simple-Firefox-Menus
sed -i 's/stylesheets", false/stylesheets", true/g' ~/.mozilla/firefox/*.default-release/prefs.js
```

[Flatpak ARKENFOX:](https://github.com/trytomakeyouprivate/Arkenfox-softening)
```
git clone https://github.com/trytomakeyouprivate/Simple-Firefox-Menus 
cd Simple-Firefox-Menus
mkdir ~/.var/app/org.mozilla.firefox/.mozilla/firefox/ARKENFOX/chrome
mv * ~/.var/app/org.mozilla.firefox/.mozilla/firefox/ARKENFOX/chrome/
rm -rf ~/Simple-Firefox-Menus
sed -i 's/stylesheets", false/stylesheets", true/g' ~/.var/app/org.mozilla.firefox/.mozilla/firefox/ARKENFOX/prefs.js
```

[Native Arkenfox:](https://github.com/trytomakeyouprivate/Arkenfox-softening)
```
git clone https://github.com/trytomakeyouprivate/Simple-Firefox-Menus 
cd Simple-Firefox-Menus
mkdir ~/.mozilla/firefox/ARKENFOX/chrome
mv * ~/.mozilla/firefox/ARKENFOX/chrome/
rm -rf ~/Simple-Firefox-Menus
sed -i 's/stylesheets", false/stylesheets", true/g' ~/.mozilla/firefox/ARKENFOX/prefs.js
```

If you use a manually named profile folder, you have to create the `chrome` directory yourself, and move the files there.
