Graphite Blue Firefox CSS

Install:
1. In Firefox, open about:support.
2. Click Open Folder next to Profile Folder.
3. Inside the active profile, create a folder named chrome (if it does not exist).
4. Copy BOTH userChrome.css and userContent.css from this package's chrome folder into that profile's chrome folder.
5. In about:config, set toolkit.legacyUserProfileCustomizations.stylesheets to true.
6. Fully exit Firefox and start it again.

userChrome.css changes browser chrome (tabs, toolbar, address bar, menus).
userContent.css changes the built-in Firefox Home / New Tab page and shortcut tiles.

To revert, move these two files out of the profile's chrome folder or set
 toolkit.legacyUserProfileCustomizations.stylesheets to false, then restart Firefox.
CSS selectors for Firefox's built-in New Tab page can change between releases.
