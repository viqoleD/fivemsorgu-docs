# Privacy Policy — fivemsorgu Bot

**Last Updated:** May 13, 2026

## 1. Introduction

This Privacy Policy describes how **fivemsorgu** ("the Bot", "we", "our") collects, uses, and stores information when you interact with the Bot on Discord. We are committed to being transparent about our data practices.

**Support Server:** [discord.gg/erenlol](https://discord.gg/erenlol)

## 2. Data We Collect

### 2.1 Data Collected Automatically

When you use any slash command, the following information is automatically logged:

| Data | Purpose | Retention |
|---|---|---|
| Discord User ID | Command usage tracking & statistics | Indefinite |
| Discord Username & Tag | Interaction logging (webhook) | Webhook log only (not stored in DB) |
| Command name used | Bot usage statistics | Indefinite |
| Guild (server) ID & name | Logging command context | Webhook log only |
| Channel ID & name | Logging command context | Webhook log only |
| Command arguments provided | Detailed interaction logging | Webhook log only |
| Whether command was used in DM | Usage statistics | Indefinite |
| Timestamp of command execution | Usage statistics | Indefinite |

### 2.2 FiveM Player Data (Third-Party Public Data)

The Bot retrieves and stores player data from **FiveM's public API**. This data is publicly available to anyone. We store:

| Data | Source | Purpose |
|---|---|---|
| In-game player name | FiveM Public API | Player lookup & search |
| FiveM License identifier | FiveM Public API | Player identification |
| All player identifiers (license, discord, steam, xbl, live, fivem) | FiveM Public API | Player identification & linking |
| First seen timestamp | Bot-generated | Historical tracking |
| Last seen timestamp | Bot-generated | Session tracking |
| Server ID (which FiveM server) | Bot-generated | Data organization |
| Ban records (reason, date) | Scraped from server ban lists | Ban history display |
| Player snapshots (ID, first seen per session) | Bot-generated | Playtime estimation |

> **Important:** The player identifiers and names stored are sourced from FiveM's **publicly accessible** server browser API. This data is available to any member of the public without authentication.

### 2.3 Data We Do NOT Collect

The Bot does **not** collect or store:
- Message content (the Bot cannot read your messages)
- Private/direct messages
- Email addresses
- Payment information
- Any data beyond what is listed above

## 3. How We Use Collected Data

The data collected is used exclusively for the following purposes:

- **Providing Bot functionality:** Responding to slash commands with player information
- **Usage statistics:** Tracking how frequently commands are used (owner-only, via `/istatistik`)
- **Historical lookups:** Enabling `/id-data` and `/data-ara` commands to retrieve past player information
- **Ban history display:** Showing ban records attached to specific FiveM player identifiers
- **Service monitoring:** Logging interactions to a private webhook for debugging and moderation

## 4. Data Storage

- All data is stored in a **private MongoDB database** controlled by the Bot's owner.
- The database is **not shared with third parties**.
- Data is stored on a self-hosted or cloud server accessible only to the Bot's operator.
- No data is sold, rented, or traded to any external party.

## 5. Data Sharing

We do **not** sell or share your personal data with third parties, except:
- **Discord:** The Bot operates on Discord's platform. Discord's own [Privacy Policy](https://discord.com/privacy) applies to all interactions.
- **FiveM / Cfx.re:** Player data is fetched from FiveM's public API. Their [Privacy Policy](https://fivem.net/privacy) governs their data practices.
- **Legal requirements:** We may disclose data if required to do so by applicable law or valid legal process.

## 6. Data Retention

| Data Type | Retention Period |
|---|---|
| Command usage statistics | Indefinite (no automated deletion) |
| Player records from FiveM API | Indefinite (continuously updated) |
| Ban records | Indefinite |
| Player snapshots | Indefinite |
| Webhook interaction logs | Governed by Discord's webhook log retention |

We do not currently have an automated data deletion policy. If you have concerns about specific data, please contact us via the support server.

## 7. Your Rights

Depending on your jurisdiction, you may have the right to:
- **Access** the data we hold about you
- **Request deletion** of your data
- **Object** to the processing of your data

To exercise any of these rights, please contact us via our support server: [discord.gg/erenlol](https://discord.gg/erenlol). Please note that some data (such as FiveM identifiers tied to public API data) may not be deletable if it is sourced from publicly available information.

> **Note for EU/EEA users (GDPR):** If you are located in the European Union or European Economic Area, you may have additional rights under the General Data Protection Regulation (GDPR). Please contact us for GDPR-specific requests.

## 8. Children's Privacy

The Bot is not directed toward children under the age of 13 (or the applicable minimum age in your country). We do not knowingly collect personal information from children. If you believe we have inadvertently collected data from a child, please contact us immediately.

## 9. Security

We take reasonable technical measures to protect stored data. However, no method of electronic storage or transmission over the internet is 100% secure. We cannot guarantee absolute security.

## 10. Third-Party Links & Services

The Bot interacts with the following third-party service:
- **FiveM Public API** (`https://servers-frontend.fivem.net/api/servers/single/`) — We are not responsible for the data practices of FiveM/Cfx.re.

## 11. Changes to This Policy

We may update this Privacy Policy at any time. When we do, we will update the "Last Updated" date at the top of this document. We encourage you to review this policy periodically. Continued use of the Bot after changes constitutes acceptance of the updated policy.

Significant changes will be announced in our support server: [discord.gg/erenlol](https://discord.gg/erenlol)

## 12. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or your data, please contact us:

👉 **Discord Support Server:** [discord.gg/erenlol](https://discord.gg/erenlol)

---

*This Privacy Policy applies solely to the fivemsorgu Discord bot and does not apply to any other services, websites, or applications.*
