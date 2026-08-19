# Mass Pack Creator 🚀
**For Snapshot & Lewd Shores**

A fully client-side, lightning-fast, and beautifully designed Web Application that automates the creation of custom content packs for *Snapshot* and *Lewd Shores*.

Unlike the standard pack creator, this tool allows you to upload **massive amounts of images (up to 1000+) at once**, automatically splitting them into manageable, game-compliant parts, and bundling everything into a single `.ZIP` file.

## ✨ Features
- **Mass Uploads (Drag & Drop):** Drop hundreds of generated images directly into the browser.
- **Auto-Chunking:** Automatically divides images into 100-image chunks (e.g., `Part 1`, `Part 2`) as required by the games.
- **Smart ID Range Allocation:** Just paste the starting ID range you got from Discord (e.g. `250000-250499`), and the script will automatically assign the correct, sequential sub-ranges to each generated chunk.
- **One-Click .ZIP Export:** No more manually creating folders. The tool instantly compresses everything into a `.ZIP` file using JSZip, ready to be shared or extracted directly into the game.
- **100% Client-Side & Secure:** No images are uploaded to any server. All processing and `.ZIP` generation happens locally in your browser.
- **Beautiful UI:** A sleek, minimalist dark mode interface with glassmorphism and smooth animations.

## 🛠️ How to use
You can use this tool by either downloading the `mass_pack_creator.html` file and opening it in your browser, or by hosting it on GitHub Pages for free!

1. Open the tool.
2. Drag and drop all your `.jpg`, `.png`, or `.webp` images into the upload zone.
3. Fill in the **Pack Title**, **Pack ID** (lowercase only), and your **Target Game**.
4. *(Optional)* Paste your unique **ID Range** from Discord.
5. Choose your **Theme Color**.
6. Click **Generate Pack (.ZIP)**!

The tool will process the images and download a `[PackName]_MassPack.zip` file directly to your computer.

## 🌐 Hosting on GitHub Pages
Want to share this tool with others? 
1. Create a new GitHub repository.
2. Upload `mass_pack_creator.html` and rename it to `index.html`.
3. Go to **Settings > Pages**.
4. Select the `main` branch and hit Save.
5. In a few minutes, your Mass Pack Creator will be live on the web!

## 📜 Credits
Based on the original pack creator logic for *Snapshot / Lewd Shores*, completely reimagined for mass AI generation workflows.
