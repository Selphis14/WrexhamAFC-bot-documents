# Privacy Policy — Wrexham AFC Devvit Bot

**Last updated:** 2026-11-05

## 1. What data the apps process

These apps process content that Reddit's Devvit platform makes available to them, namely:

- **Post submissions** (URL, title, author username) in subreddits where the app is installed
- **Existing thread metadata** (post IDs, comment IDs, sticky state) in subreddits where the app is installed
- **Wiki page content** (for templates and configuration) in subreddits where the app is installed
- **User profile data** (username, user ID) to display and submit comments through the app.

These apps also fetch data from public third-party APIs (api-sports.io, rapidapi.com) operated by those organizations. See the app README "Fetch Domains" section for the list and purpose.

## 2. What data the apps store

These apps store minimal operational state in Reddit's Devvit-provided Redis storage. Stored data includes:

- Reddit post IDs and thread IDs (for deduplication and lifecycle tracking)
- Install settings configured by subreddit moderators
- Cached responses from data APIs (short-lived, time-bounded)

Stored data is per-subreddit-install. When the app is uninstalled from a subreddit, Devvit's platform retains storage for that install according to Reddit's own data retention policies, which the author does not control.

## 3. What data the apps do NOT store

These apps do NOT collect, store, transmit, or share:

- Personal identifying information of subreddit users (other than usernames already public on Reddit)
- IP addresses or device information
- User comment content
- Any data from subreddits where the app is not installed

## 4. Third-party sharing

These apps do NOT share collected data with any third party. Data processed by the apps remains within Reddit's Devvit platform infrastructure.

The apps DO fetch data FROM third-party public APIs. These outbound requests carry only standard HTTP headers; they do not include subreddit-specific identifying information beyond what is publicly available (such as "today's date" or "this team's ID").

## 5. Children's privacy

This app is intended for use by Reddit users (who must be 13+ per Reddit's terms) and does not knowingly process data from children under 13.

## 6. Changes to this policy

This policy may be updated from time to time. The "Last updated" date at the top of this document reflects the most recent change.

## 7. Contact

Privacy questions or concerns: contact `/u/Selphis` on Reddit.
