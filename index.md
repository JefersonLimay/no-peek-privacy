# Privacy Policy — No Peek

Last updated: September 25, 2026

No Peek is a Chrome extension that blocks access to adult websites. This
policy explains what data the extension handles.

## Data Collection

No Peek does not collect, transmit, or sell any personal data to us or to
any third party. All data the extension uses is stored locally on your
device, using Chrome's built-in storage APIs (chrome.storage.local and
chrome.storage.session), and never leaves your browser.

The data stored locally includes:
- Whether the blocker is enabled or disabled
- Your custom blocklist, whitelist, and keyword lists
- A password hash and salt (not the password itself) if you choose to set
  one
- A local count of how many pages were blocked per day, for the dashboard.
  It does not record which sites were blocked.
- Your language and theme preferences

While your browser is open, No Peek also keeps temporary session data
(whether the settings page is unlocked and which settings tab you last
viewed). This data is cleared when the browser closes.

## Permissions

- **declarativeNetRequest**: used to block requests to known adult
  domains and to domains/keywords you add yourself.
- **storage**: used to save your settings locally, as described above.
- **webNavigation**: used to detect when a page was blocked, purely to
  show a local count on your dashboard.
- **host_permissions (`<all_urls>`)**: required so the blocking rules can
  apply to any website you visit. It is also used to read the address of
  your current tab when you open the popup, so you can add that site to
  your blocklist with one click.

No Peek does not inject scripts into web pages or read their content.
None of the above permissions are used to collect, log, or transmit
browsing history to us or to any third party.

## Third Parties

No Peek does not use analytics, advertising, or tracking services of any
kind, and it does not load remote code or resources: everything it needs,
including fonts, is bundled inside the extension.

The extension contains an optional donation link (Ko-fi) and a contact
email address. These only open when you click them, and no data from the
extension is sent to them.

## Changes to this Policy

If this policy changes, the "Last updated" date above will be updated
accordingly.

## Contact

Questions about this policy or the extension can be sent to:
c.jeferson.lc@gmail.com
