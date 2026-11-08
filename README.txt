BROCLICKS WEBSITE

Files:
- index.html: website homepage
- BroClicks.exe: downloadable Windows x64 app
- logo.png: BroClicks logo

LOCAL PREVIEW:
Double-click index.html or open it in a browser. The download button downloads BroClicks.exe from the same folder.

PUBLISH WITH GITHUB PAGES:
1. Create a new GitHub repository (for example: broclicks-download).
2. Upload index.html, logo.png and BroClicks.exe to the repository root.
3. Open repository Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select branch main and folder /(root), then Save.
6. Wait for GitHub Pages to publish the site. Use the URL shown in Settings > Pages.

SECURITY:
The EXE may be unsigned, so Windows SmartScreen may show an unrecognized publisher warning.
Do not disable Defender or SmartScreen. The page displays the expected SHA-256 hash:
c12c5c000b47be1d68d21f3d7fac2c341f60421ca5f7c1ac51ba4c3d116ee41e

To check on Windows:
certutil -hashfile BroClicks.exe SHA256

If Microsoft Defender flags the file, do not run it. Investigate the detection and use a properly signed, verified release.
