# COEP CyberCell Induction 2026: Mini CTF Write-up

How I solved the six challenges. I'm new to CTFs  so this is just what I tried and what I learned.

**1. Nothing to See Here**
Viewed the page source (Ctrl+U) and found the flag in an HTML comment.
`COEP{view_source_is_your_friend}`

**2. Mystery String**
It looked like Base64, so I decoded it in CyberChef.
`COEP{base64_is_not_encryption}`

**3. Picture Perfect**
The flag was in the photo's metadata not the picture, Read it with a metadata viewer.
`COEP{metadata_never_lies}`

**4. Polite Robots**
robots.txt listed a hidden folder so I opened that path and found the flag.
`COEP{robots_know_secrets}`

**5. Where Was This Taken?**
Google Lens failed so I searched the clues in text and found it was the COEP main building.
`COEP{main_building}`

**6. Not What It Seems**
The "jpg" started with `50 4B 03 04` which is a ZIP so i renamed it and extracted it and read flag.txt.
`COEP{not_every_jpg_is_a_jpg}`

**Tools:** browser, CyberChef, metadata viewer, Google

**AI use:** I used Claude for hints and for help organizing this write-up.
