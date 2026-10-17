Graphite Blue for Firefox

Files:
- chrome/userChrome.css: browser interface (tabs, toolbar, menus, sidebar).
- chrome/userContent.css: built-in Firefox new-tab page and shortcut styling.

Install:
1. In Firefox, open about:support and click the button to open the active profile folder.
2. Create a folder named chrome if it does not exist.
3. Put both CSS files inside that chrome folder.
4. In about:config set toolkit.legacyUserProfileCustomizations.stylesheets to true.
5. Fully quit Firefox and open it again.

If the sidebar colour still does not change, check that the files are in the active profile folder shown by about:support. Firefox UI CSS selectors can change between versions.
