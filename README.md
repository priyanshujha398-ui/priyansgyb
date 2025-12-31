# Memory Keeper

A simple, client-side web app for saving and privately sharing personal memories (texts, images, and videos) with loved ones. Built with HTML, CSS, and JavaScript—no server required. Memories are stored locally on your device and can be shared securely via encrypted links.

## Features
- **Save Memories**: Add text, images (up to 5MB), or videos (up to 50MB) as personal entries.
- **Local Storage**: Memories persist in your browser's localStorage for offline access.
- **Private Sharing**: Share memories across devices (e.g., phones) with password-protected, encrypted links. Only those with the password can view them.
- **Mobile-Friendly**: Responsive design that works on phones and desktops.
- **Export/Import**: Backup your memories as a JSON file or restore from one.
- **Delete Memories**: Easily remove entries from your personal collection.
- **No Data Collection**: Everything stays on your device—privacy-focused.

## Demo
Live demo available at: [https://yourusername.github.io/memory-keeper](https://yourusername.github.io/memory-keeper) (replace `yourusername` with your actual GitHub username after enabling GitHub Pages).

## How to Use
1. **Open the App**: Download `index.html` and open it in a modern web browser (e.g., Chrome, Firefox). Or, if hosted on GitHub Pages, visit the live URL.
2. **Add Memories**:
   - Enter text in the form.
   - Upload an image or video (check file size limits).
   - Click "Save Memory" to store it locally.
3. **View Memories**: Your saved entries appear below the form, with options to delete them.
4. **Share Privately**:
   - Click "Share Memories Privately."
   - Enter a strong password when prompted.
   - The encrypted share link is copied to your clipboard. Share the link and password securely (e.g., via text—don't send them together).
   - Recipients open the link on their device, enter the password, and view the memories.
5. **Backup**: Use "Export Memories" to download a JSON file. Use "Import Memories" to restore.

## Requirements
- Modern web browser with support for Web Crypto API (e.g., Chrome 60+, Firefox 60+, Safari 12+).
- No internet required for basic use (works offline), but sharing links need a connection.

## Installation (Local)
1. Clone or download this repository.
2. Open `index.html` in your browser.
3. Start saving memories!

## Contributing
Feel free to fork this repo and submit pull requests for improvements (e.g., better UI or additional features). This is an open-source project under the MIT License.

## Privacy Note
Memories are encrypted during sharing, but the app's code is visible if the repo is public. No personal data is sent to servers—everything is client-side.

## License
MIT License. See LICENSE file for details (add one if needed).
