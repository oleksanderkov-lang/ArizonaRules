# Privacy Policy for Arizona Helper (Политика конфиденциальности)

**Last updated:** November 2026

## 1. Data Collection and Usage (Сбор и использование данных)
**Arizona Helper** does not collect, sell, or share any personal or sensitive user data (such as passwords, emails, browsing history, or cookies).
* **Local Storage:** All extension settings (theme colors, hotkeys, custom reply templates, and cached forum rules) are stored locally in your browser using `chrome.storage.local` and `localStorage`.
* **GIF Avatars Synchronization:** If a user voluntarily sets a custom GIF avatar in the extension settings, the extension sends only the public numeric forum User ID (`forumUserId`) and the direct image link (`gifAvatarUrl` from Imgur, Tenor, Giphy, or PostImg) to Firebase Realtime Database solely to display the GIF avatar to other extension users on `forum.arizona-rp.com`.
* **Discord Webhook (Optional):** If configured by the user, moderation form logs are sent directly from the user's browser to the Discord Webhook URL specified by the user.

## 2. Third-Party Sharing (Передача третьим лицам)
We do not sell, trade, or transfer any data to third parties for advertising, analytics, or marketing purposes.

## 3. Contact (Контакты)
If you have any questions or requests regarding data removal, you can clear your GIF avatar link directly inside the extension popup settings (which deletes the record from the database) or contact the developer via the Chrome Web Store support page.
