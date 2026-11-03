LUGARD AVENUE, OLD IKOYI - FOR SALE EMAIL
=========================================

Folder contents
  index.html        the email (open it directly to preview; images and fonts load from the folders below)
  images/           hero.jpg, living.jpg, bedroom.jpg, kitchen.jpg, pool.jpg, gym.jpg, ros-logo.png
  fonts/            Gloock (display) and Instrument Sans (text), as .woff and .ttf, with their OFL licences

To send it (so it shows in Outlook, Gmail, Apple Mail)
  1. Upload the "images" folder, and the "fonts" folder, to any public https location
     (your website, the email platform's image library, a CDN).
  2. In index.html, find-and-replace   images/   with   https://YOUR-HOST/path/images/
     and                               fonts/    with   https://YOUR-HOST/path/fonts/
     (one replace each, applies to the hero, the VML background for Outlook, the photos and the logo).
  3. Send a test to an Outlook (Windows) address and a phone before the real send.

Notes
  - Outlook for Windows does not load web fonts: it shows Georgia / Arial in their place. Everything else looks the same.
  - Outlook blocks images until "Download pictures" is clicked: normal for all email, not a fault.
  - Replace {{unsubscribe_url}} and {{view_in_browser_url}} in the footer with your email platform's merge tags.
  - Gmail ignores web fonts too; it falls back to Georgia / Helvetica.
