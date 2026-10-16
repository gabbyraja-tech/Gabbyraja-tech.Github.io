# Macro Pop: using it outside Claude

Macro Pop is a single web page (index.html) that works offline once opened. Your entries are stored on the device, in the browser, and nothing is sent anywhere.

## Easiest: host it free, install on your phone
1. Put the files from this folder on any static host with https. Free options: Netlify Drop (app.netlify.com/drop, drag the folder in), Cloudflare Pages, GitHub Pages, Vercel.
2. Open the address on your phone.
   - iPhone: Safari > Share > Add to Home Screen.
   - Android: Chrome menu > Install app.
3. Open it from the Home Screen icon. The first launch loads the 120 starter foods.
4. To bring over your existing data: tap the download icon at the top, choose the backup file (macro-pop-my-data-backup.json), then Restore now.

Keep the hosted address private-ish: the page holds no data, but anyone with the link could use their own copy.

## Without hosting
index.html opens by double-clicking, but the install and offline features need https (or localhost), and file:// storage can be cleared by some browsers. Hosting is recommended.

## Things to know
- Data lives per device and per browser. Phone and laptop do not sync. Use Download backup, then Restore on the other device.
- Download a backup regularly. Clearing browser data or deleting the Home Screen app on iPhone can erase what is stored.
- To update the app later, replace the files on your host; your data stays.
