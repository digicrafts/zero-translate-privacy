# Zero Translate Privacy Policy

Last updated: 27 October 2026

Zero Translate reads selected text only when you invoke its toolbar action, keyboard shortcut, selection context menu, or double-click on website text. It sends up to 5,000 characters to https://translate.google.com in the URL to display the translation. Google processes that text according to its own privacy policy: https://policies.google.com/privacy. Google Translate may use cookies, and translation URLs may be retained by the browser or Google's systems according to their settings and policies.

The extension stores your chosen target language locally on your device. It stores the latest selected text and target language per browser window in temporary browser-session storage so the side panel can display and restore the current translation. This text is replaced on the next translation action and removed when its browser window closes or the browser session ends. It also keeps temporary identifiers to reuse the optional floating window. By default, it also saves the latest 100 translation selections, their target languages, and timestamps locally on your device. Use History in the side panel to select an entry and translate it again. Settings lets you disable recording or clear saved history; disabling recording retains existing entries. Text typed directly into the Google Translate website is not recorded by the extension. It does not collect browsing history or account details. It has no analytics, advertising, tracking, developer-operated server, or sale of user data.

A content script runs on HTTP/HTTPS websites to detect double-clicks. It reads and sends only the selected text when you use the configured double-click shortcut (Command + double-click by default); password fields and empty selections are ignored. Website text is not collected in the background. No account or payment is required by this extension. Removing the extension removes its extension-managed storage. Clearing browser history or Google account data is managed separately through those services.

This extension is independent and is not affiliated with or endorsed by Google. For privacy questions, use the developer contact provided on the extension's store listing.

For side-panel embedding, the extension removes the X-Frame-Options header only on Google Translate frames requested by this extension. It also removes the Sec-Fetch-Dest request header for those same frame requests to allow the website to load. It does not change headers for Google Translate frames requested by ordinary websites.
