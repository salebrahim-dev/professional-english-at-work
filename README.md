# Professional English at Work

A lightweight mobile-first Progressive Web App for practising confident workplace English. It uses only browser technologies and stores progress locally on the device.

## Run locally

Open `index.html` in a browser for a quick look. For the PWA offline cache and installation prompt, serve the folder over a local web server instead. For example, in VS Code use the **Live Server** extension, or run `npx serve .` if Node.js is installed.

Then open the local address shown by the server in your browser.

## Test on an Android phone

1. Put the computer and phone on the same Wi-Fi network.
2. Start a simple local server that allows LAN access, for example `npx serve . -l 3000`.
3. Find the computer's local IPv4 address with `ipconfig` and open `http://YOUR-IP:3000` on the phone.
4. Use Chrome's menu and choose **Install app** or **Add to Home screen**.

For a fully secure install experience, publish it first (GitHub Pages provides HTTPS automatically).

## Publish free with GitHub Pages

1. Create a new GitHub repository and upload every file in this folder to its `main` branch.
2. In the GitHub repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and the `/ (root)` folder, then save.
4. Wait for GitHub to show the public Pages URL. Open that address on Android Chrome and select **Install app**.

## Add or edit cards

Edit [cards.js](cards.js). Each entry is a three-part record: weak phrase, professional alternative, and category. The app adds progress statistics itself in LocalStorage, so the source card file stays clean and easy to extend.
