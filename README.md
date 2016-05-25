This is not an official Google product.

steamkeysactivator
==================

Activates Steam Keys in bulks (Mac only)

It's a small and dumb script that reads the currently open Safari/Chrome page,
searches for Steam keys and uses local Steam client to activate them one by one.

It's particularly useful for Humble Bundles.

How to run:

1. Check that you are using Mac OS and not Windows or Linux
1. Download everything to your Mac
1. Make sure your keyboard layout is set to Qwerty
  * The "V" key must be the same physical keyboard key as Qwerty, due to Steam having a weird copy & paste implementation
1. Run this application
1. The first run may fail because it needs permission to automate your desktop:
  1. Go to System Preferences → Security & Privacy → Privacy → Accessibility
  1. Make sure the checkbox next to "SteamKeysBulkActivation" is checked
1. In case the app does not run, try to run the script in a Script Editor

Known to work with:

1. Humble Bundle 14
1. Steam in English April 2015th version
1. Mac OS Yosemite

Other bundles (e.g. IndieGala) may not work on their own.  If you have trouble:

1. Make a blank HTML file with `<html><body>...</body></html>`
1. Paste a list of Steam keys into the `...` part.
1. Open the list in Safari/Chrome

Good luck!
Feel free to send patches and bugs!
