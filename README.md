# IceDragon-Browser
TesseraQt - Highly Secure Web Browser for the GNU OS Project

It is a fork of the FireDragon Web Browser. It is updated with Firedragon. Developed from FireDragon Floorp Browser. Floorp Browser is the best firefox based Web Browser in terms of performance and speed. FireDragon is a security-oriented web browser. It includes security configurations from projects like LibreWolf. In this project we will fork FireDragon and import some settings and configurations from the GNU Icecat Browser Project. We will add them to the settings interface. We will also do the following according to the needs of the TesseraQt-GNU OS Project:

1. The default search engine will be google, yandex, yaani, bing, baidu, bing, baidu, etc. Search engines of 3rd party application developers who develop closed source software will be absolutely inaccessible. These search engines cannot be added from the settings. The default search engine will be duckduckgo, searx, starpage, brave, wikipedia will be added as selectable.
2. Fingerprint blocker, Canvas Blocker, WebGL fingerprint blocker, tracker blocker extensions will be embedded and cannot be deactivated or deleted.
3. Container creation and opening in container extension will be embedded. The Temperaray Container plugin, which is the plugin for opening with a container in the new tab, will also be embedded. It cannot be deleted or deactivated.
4. User-Agent Switcher extension will be embedded. It cannot be deleted or deactivated.
5. No Script extension will be embedded. Cannot be deleted. Cannot be deactivated. 
6. Proton VPN extension will come installed.
7. Javascript blockers will be embedded. GNU LibreJS and JShelter extension will be embedded, cannot be deleted or deactivated.
8. Other LibreJS extensions (LibreJS compatible Pay.gov, LibreJS compatible SumOfUs.org, LibreJS Google Docs, LibreJS/USPS compatibility, LibrifyJS: libgen.me, Make Google Docs work under LibreJS, Rock and Roll McDonald's, Sign RSF.org petitions with free Javascript, Workarounds for nonfree JS= will be embedded, cannot be deleted or deactivated.
9. Reveal hidden HTML extension will be embedded, cannot be deleted, can be deactivated, but there will be no deactivate button in the settings interface.
10. By default the extensions store will be the GNU Mozzarella Store. You will not be able to install extensions from the Mozilla Extensions Store. For extensions that are not in the Mozzarella store, you will be redirected to the git page, and installation from the git page will be allowed. Not every extension will be allowed. Only add-ons that we label as trusted will be allowed to be installed via git.
11. Useful features will be transferred from Floorp Browser. For example, vertical tab features, Workspaces features. 
12. Useful features will be added from Zen Browser. We will add panel application shortcuts, the ability to split the browser window into 2,3,4 tabs, workspaces management interface, hide tap bar and hide top bar feature, embedded container feature. We will make the sidebar feature vertical like floorp sidebar.
13. We will release optimized version for those who support Intel Processor AVX2. We will also release a generic version. By default the optimized version will be installed from Guix package manager.
14. DRM-protected content will be blocked and not installed. DRM-support lacks. DRM license will not be purchased.
15. If there are missing security settings and configurations, they will be imported from the librewolf browser project.
16. open in tor window to open onion sites in brave browser. This feature is not used for anonymity in terms of security, it will be added to access blocked sites, to access news sites, to access your protonmail account.


This project will be developed for installation from the Guix OS Package Manager. An optional AppImage version will be released. We might release a flatpak version, but we are not thinking about it. We will definitely not be included in distributions' package managers (rpm, deb etc.) and snap store.

We will also release a version for Nix OS NixPkgs.

Since this scanner will be designed to run inside containers, no versions will be allowed outside isolated areas and containers. Necessary legal actions will be taken under the terms of the license.
