# Customization for Firefox

One line transparent setup for MacOS

<img width="1440" alt="07b27a64f1f5704e596b697affe835abab2d1b893da3edb22460add137b3fccb" src="https://user-images.githubusercontent.com/59616661/215130513-9f9921b6-86c3-4e23-b6a7-a1f7258619a9.png">

## Installation

1. In a new tab, type or paste `about:config` in the address bar and press Enter/Return. Click the button accepting the risk.
2. In the search box above the list, type or paste `userprof` and pause while the list is filtered. If you do not see anything on the list, please ignore the rest of these instructions. You can close this tab now.
3. Double-click the `toolkit.legacyUserProfileCustomizations.stylesheets` preference to switch the value from false to true.
4. In the menubar click `Help > More Troubleshooting Information`. On the opened page find `Profile folder` and click `Show in Finder`.
5. In this folder there is another folder `chrome` — it is a place there you should put files from this repo. You can download this repo as `.zip` and move files in here. Or open terminal in `chrome` folder and execute `git clone https://github.com/mchernigin/firefox-customizations.git .` (dot is important).
6. Now you just need to restart Firefox and everything should work.

