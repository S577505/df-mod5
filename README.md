# Digital Forensics — Module 5

**Student:** Mary Jones  
**Time spent:** 3–4 hours

## Exercise 1 — Chapter 8 Investigation
Investigated the Superior Bicycles case using Autopsy and the `C08InChp.dd` disk image. Located photographic evidence and repaired an altered JPEG header using ImHex. Verified the repaired `Fixed1.jpg` opens as an image.

## Exercise 2 — Defeat Simple Steganography
Explored the [sample website](https://denisecase.github.io/386-site/) and its [source repository](https://github.com/denisecase/386-site). Found hidden HTML text containing `stupendous`, `stegasaurus`, and the question “what does the cat say?” Examined `web.jpg` in a hex editor and found the appended text **“This is a secret message.”** after the JPEG end marker.

## Exercise 3 — Examine Email Headers
Exported three school-related emails from Outlook as `.eml` files and examined their headers in Notepad:

1. Bearcat Alert
2. President's Tree Lighting invitation
3. Northwest Digest

Recorded each Message-ID, available originating-IP information, transport encryption details, and hashing-related headers. Where the original public IP or standalone email-content hash was absent, documented that limitation rather than assuming a value. SHA-384 in a TLS cipher suite does not by itself establish a separate message-content hash.

## Verification screenshots
All nine verification screenshots from the local computer are included in the uploaded PDF. They document the recovered photographic evidence, JPEG header repair, hidden website and image messages, and email-header investigations.

**[View Module 5 Verification Screenshots (PDF)](Module5_Verification_Screenshots.pdf)**
