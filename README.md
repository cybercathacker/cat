# [CAT] Cilent

A browser userscript add-on for Territorial.io, made for [CAT]. It provides live match statistics and manual quality-of-life controls. It does not automatically attack or play the match for you.

## Install

1. Install Tampermonkey in your browser. In Chrome, enable **Allow User Scripts** for the extension if prompted.
2. Open the [live installer page](https://cybercathacker.github.io/cat/) and click **Install with Tampermonkey**. Confirm the installation in Tampermonkey.
3. Visit [Territorial.io](https://territorial.io/) and start a match.

If the `.user.js` link downloads a file instead, use Tampermonkey **Dashboard → Utilities → URL** to import `https://cybercathacker.github.io/cat/CAT-Cilent.user.js`. Do not double-click the file in Windows Explorer. That opens Windows Script Host, which reports a JScript syntax error because this is a browser userscript.

## GitHub Pages

The [live page](https://cybercathacker.github.io/cat/) serves the installer and instructions from the `main` branch of [`cybercathacker/cat`](https://github.com/cybercathacker/cat). The add-on runs on the official game page; GitHub Pages does not host matches.

## Licence and third-party material

This repository uses the MIT licence already selected for it. It applies to original [CAT] Cilent code and documentation created for this project. It does not grant rights to Territorial.io or third-party code, trademarks, artwork, or other assets. See [`THIRD-PARTY-NOTICES.md`](THIRD-PARTY-NOTICES.md).
