# Ministry Stage

**Sends your stage display to any tablet.**

Local screen mirroring for the preacher's stage display, plus a congregation
words page for the morning the projector dies.

## Download

**[Download Ministry Stage for macOS](../../releases/latest)**

Open the disk image and drag Ministry Stage into your Applications folder.

## What you need

- An **Apple Silicon** Mac (an M-series chip, or the A18 in a MacBook Neo).
  Intel Macs cannot run it.
- **macOS 12** or later.
- **ProPresenter** on that same Mac.
- The tablets and phones on the **same wifi** as the Mac. Nothing works over
  mobile data, by design.

## What to expect on first open

The app is signed with an Apple Developer ID and notarised by Apple, so macOS
will not block it. You will still see a few prompts, which is normal:

1. macOS asks whether you are sure, because you downloaded it from the
   internet. Open it.
2. The app offers to move itself into Applications. Let it.
3. It asks for **Screen Recording**, which is how it sees the stage display.
   Allow it, then **quit Ministry Stage and open it again**: macOS only applies
   that permission on a fresh start.
4. It may ask for **Local Network** access, which is how your tablet reaches it.

## Where your data goes

Ministry Stage serves the stage picture and the words page **on your own
network only**. Nothing about your church, your slides or your people is sent
anywhere, and there is no account to make.

The one exception, so you hear it from us rather than a firewall log: if
somebody chooses **Check for updates** from the Help menu, the app fetches a
small file from GitHub to see whether a newer version exists. That is a
deliberate click, there is no background checking, and nothing about you is
sent with it.

Note that the pages your tablets and phones open are served over plain `http`
on your local network, not `https`. Anyone already on your wifi could in
principle see the words page. The stage picture itself is encrypted in transit.

## Setting it up

The full guide is inside the app: **Help → Ministry Stage guide**. It covers
pointing ProPresenter at the stage screen, setting up a tablet, reserving the
Mac's address on your router, and a Sunday morning checklist.

## Staying up to date

Click **Watch** at the top of this page and choose **Releases only** to hear
about new versions. Or use **Help → Check for updates** in the app.

## A word of warning

This is a young app, written for one church and shared in the hope it helps
yours. Please try the words page with ProPresenter open **before** you rely on
it in a service.

## Problems

Please [open an issue](../../issues). It is the only way to reach me about this,
and the only way I find out something is broken.

## Licence

Not open source, and this repository holds the released app rather than its
code. Free to install and free to pass on to another church, but not to sell,
rebrand, modify and redistribute, or pass off as your own. See [LICENSE](LICENSE).

Copyright (c) 2026 Harry Goodwin. All rights reserved.
