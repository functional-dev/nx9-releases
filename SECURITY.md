# Security

NX9 drives Claude Code sessions that can edit files and run commands on your Mac, so we treat any way past its sign-in as serious.

## Reporting a problem

Please do not open a public issue for a security problem.  Use GitHub's private reporting instead:  open the [Security tab](https://github.com/functional-dev/nx9-releases/security) of this repository and choose **Report a vulnerability**.  You can also reach us through [functional-development.com](https://functional-development.com).

Include the NX9 version (click the logo in NX9), your macOS version, and the steps that show the problem.  We will reply within five working days and keep you informed until it is fixed.

## Supported versions

Security fixes go into the latest release.  Please update before reporting.

## How NX9 protects your Mac

- It listens only on your Mac and on your Tailscale network, never on all network interfaces.
- Once you choose a password, every device that reaches NX9 over the network signs in with it.  The password is stored as a salted PBKDF2-SHA256 digest.  After five wrong guesses, that address waits longer before each new try.
- A signed-in device that goes 30 days without opening NX9 is signed out, and changing the password signs every device out.
- It answers only requests addressed to its own names, and only accepts changes from its own page, so other websites open in your browser can't drive it.
- Its settings, keys, sign-in records, uploads and logs are files only your user account can read.
- It sends nothing about your work anywhere.  Its only automatic connection is to check for new-version notices, which you can turn off.
