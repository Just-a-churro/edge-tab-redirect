Edge New Tab Redirect - No Bloat Edition
----------------------------------------

WHAT THIS IS:
A minimal browser extension that replaces the bloated Microsoft Edge new tab page 
with something actually useful — like Google.com or whatever page you prefer.

WHY I MADE IT:
The Edge new tab page forces Bing, MSN news, ads, and other distractions even 
if you change your search engine in settings. This extension skips all of that 
and redirects to a clean page of your choice. The versions I found online were
either cryptic in name, bloated, or loaded blank new tabs and not a specific page.

WHAT IT DOES:
When you open a new tab, it instantly redirects to the URL defined in `newtab.html`.

Default: https://www.google.com

You can change this by editing `newtab.html`:
<meta http-equiv="refresh" content="0; URL='https://your-site.com'" />

HOW TO INSTALL:
1. Open Edge and go to: edge://extensions
2. Enable "Developer mode" (toggle at bottom left)
3. Click "Load unpacked"
4. Select this folder

That’s it. Every new tab should now go to Google (or whatever you set).

KNOWN QUIRK:
Edge may show a one-time popup saying "Is this the new tab you expected?" after install. 
This is Microsoft's way of guilt-tripping or instilling fear so users revert back to Bing.
You can safely click "keep changes" and move on with your life.

CREDITS:
None. Just a guy who was tired of seeing Bing every time he opened a new tab.

LICENSE:
MIT. Free to use, modify, or fork. No tracking, no updates, no hidden nonsense.
