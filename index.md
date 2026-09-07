# Privacy Policy — No Peek

Last updated: September 7, 2026

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
- A password hash (not the password itself) if you choose to set one
- A local log of how many pages were blocked, by date, for the dashboard

## Permissions

- **declarativeNetRequest**: used to block requests to known adult
  domains and to domains/keywords you add yourself.
- **storage**: used to save your settings locally, as described above.
- **tabs**: used to read the URL of your active tab so you can block the
  page you're currently viewing.
- **webNavigation**: used to detect when a page was blocked, purely to
  show a local count on your dashboard.
- **host_permissions (`<all_urls>`)**: required so the blocking rules can
  apply to any website you visit.

None of the above permissions are used to collect, log, or transmit
browsing history to us or to any third party.

## Third Parties

No Peek does not use analytics, advertising, or tracking services of any
kind.

## Changes to this Policy

If this policy changes, the "Last updated" date above will be updated
accordingly.

## Contact

Questions about this policy or the extension can be sent to:
c.jeferson.lc@gmail.com
