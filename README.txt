Lado Foundation - Website Package
---------------------------------

Files included:
- index.html        -> Home page (About, Founder, Donate button)
- donate.html       -> Donation page (UPI ID + QR code)
- styles.css        -> Shared styles

Notes:
1) Images in the site are hotlinked from Unsplash (real royalty-free photos). If you prefer to host images locally:
   - Replace the <img src="..."> URLs in index.html with local filenames (e.g., 'images/classroom.jpg')
   - Put your image files in an 'images' folder alongside these HTML files.

2) QR Code:
   - The donate page shows a QR generated at runtime using api.qrserver.com with the UPI URI:
     upi://pay?pa=thechallanger@ybl&pn=Lado%20Foundation
   - If you want to include a local QR image file, generate one (via any UPI QR generator) and replace the <img> src in donate.html.

3) To go live:
   - Upload all files to a static host (Netlify, Vercel, GitHub Pages) or your web hosting provider.
   - Ensure both index.html and donate.html are in the same folder.

4) To edit:
   - Open the HTML files in a text editor and change text, images, or the UPI ID as needed.

If you want, I can:
- Generate a local QR image and include it in the ZIP (requires using an external QR generator or confirming you are okay with the runtime QR approach).
- Replace hotlinked images with local image files (you can upload images and I will add them).
