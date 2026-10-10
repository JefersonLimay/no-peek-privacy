# Privacy Policy — No Peek

Last updated: October 9, 2026

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
- Your language and theme preferences, and whether safe search and
  restricted YouTube are turned on
- Whether commitment mode is on, and when it started and ends
- The time of the last blocked attempt, your longest streak without one and
  the streak that the last attempt ended, to show your streak. They do not
  record which site was blocked.
- The personal reason you choose to write, if any, to show it on the blocked
  page
- The date the extension was installed, and whether you already answered
  the review reminder, so it is only shown when it makes sense

While your browser is open, No Peek also keeps temporary session data
(whether the settings page is unlocked and which settings tab you last
viewed). This data is cleared when the browser closes.

## Permissions

- **declarativeNetRequest**: used to block requests to known adult
  domains and to domains/keywords you add yourself. If you turn on the
  optional safe search setting, it also adds the safe search parameter to
  Google, Bing and DuckDuckGo search addresses. If you turn on restricted
  YouTube, it adds the standard "YouTube-Restrict" header to requests to
  YouTube. Both changes are made by the browser itself; No Peek does not
  read your searches or the pages you visit.
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

The extension contains an optional donation link (Ko-fi), a contact email
address, and a reminder that links to its page on the Chrome Web Store or
Microsoft Edge Add-ons so you can leave a review. These only open when you
click them, and no data from the extension is sent to them.

## Uninstall Survey

When you uninstall No Peek, your browser opens a short, optional survey page
(hosted on this site) asking why you uninstalled it. The page address
includes only the extension's version number and language, so the survey
appears in your language and answers can be matched to a release. It does
not include your lists, settings, or browsing history.

Answering is entirely optional. If you send an answer, only the reason you
chose, any comment you write, the version number, and the language are
stored, using Google Forms, under Google's privacy policy. No email address
or other personal information is collected.

## Changes to this Policy

If this policy changes, the "Last updated" date above will be updated
accordingly.

## Contact

Questions about this policy or the extension can be sent to:
c.jeferson.lc@gmail.com
