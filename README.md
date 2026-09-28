# 🦖 Printzilla PetLink
 
🐾 Scan. Connect. Reunite.

Printzilla PetLink is a NFC pet profile system that helps lost pets find their way home. Each pet receives a personalized webpage containing a photo, owner information, and one-tap WhatsApp contact.

PetLink works with NFC tags and QR codes, allowing anyone who finds a pet to quickly contact the owner.

## Features

✅ NFC Tag Compatible
 
✅ QR Code Compatible
 
✅ Pet Photo Display
 
✅ One-Tap WhatsApp Contact
 
✅ Mobile-Friendly Design

## Example Profile
 
### OJ 🐱
 
- Pet Photo
- Owner: Leo Martinez
- WhatsApp Contact Button
- Found Pet Notification Button

- Example URL:
 
```text
https://printzilla77.github.io/printzilla-petlink/oj/
```
 
---
 
## Folder Structure
 
```text
printzilla-petlink/
│
├── README.md
├── index.html
│
├── oj/
│ ├── index.html
│ └── oj.jpg
│
├── max/
│ ├── index.html
│ └── max.jpg
│
└── assets/
├── logo.png
└── styles.css
```
 
---
 
## GitHub Pages Setup
 
### Create Repository
 
Repository Name:
 
```text
printzilla-petlink
```
 
### Enable GitHub Pages
 
1. Open Repository Settings
2. Select Pages
3. Under Source select:
 
```text
Deploy from a branch
```
 
4. Choose:
 
```text
Branch: main
Folder: / (root)
```
 
5. Save
 
---
 
## Upload Pet Photos
 
Place pet photos inside each pet folder:
 
```text
oj/oj.jpg
max/max.jpg
```
 
Example image reference:
 
```html
<img src="oj.jpg" alt="OJ" class="mming
 
Program the NFC tag with the pet's profile URL.
 
Example:
 
```text
https://printzilla77.github.io/printzilla-petlink/oj/
```
 
When scanned, the page opens automatically.
 
---
 
## Contact Button
 
```html
<a href="https://wa.me/16463434123"
class="button whatsapp"
target="_blank">
et Button
 
```html
<a href="https://wa.me/16463434123?text=Hi%20Leo%2C%20I%20found%20OJ."
class="button found"
target="_blank">
- Lost / Found Status
- Multiple Emergency Contacts
- GPS Location Sharing
- QR Code Generator
- Custom Pet Tag Designs
- Admin Dashboard
 
---
 
## License
 
MIT License
 
---
 
🦖 Printzilla PetLink
 
Helping lost pets find their way home.
