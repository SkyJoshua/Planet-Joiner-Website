# Privacy Policy

**Last updated: March 2026**

## Overview

Valour Planet Joiner is a lightweight, client-side web tool for joining planets on the [Valour](https://valour.gg) platform. This policy explains what information is handled when you use the tool and how it is used.

---

## What Information You Enter

To use this tool, you provide:

- **Bot Token** — your Valour bot's authorisation token (THIS IS NOT STORED!!)
- **Planet ID** — the ID of the planet you wish to join
- **Invite Code** *(optional)* — an invite code if the planet is not publicly discoverable

---

## How Your Information Is Used

All data you enter is used solely to make API requests to Valour's official API (`api.valour.gg`) on your behalf. Specifically:

- Your **Bot Token** is sent as an `Authorization` header with each request
- Your **Planet ID** and optional **Invite Code** are used to construct the API request URL

These requests are made **directly from your browser** to Valour's servers. No data is routed through any intermediate server operated by this project.

---

## What We Do NOT Do

- We do **not** collect, store, log, or transmit your bot token or any other input to any server we control
- We do **not** use cookies, local storage, or any form of persistent storage
- We do **not** track usage, analytics, or behaviour
- We do **not** share any of your data with third parties

---

## Third-Party Services

All API calls are made to **Valour's API** (`api.valour.gg`). Any data sent to that API is subject to [Valour's own privacy policy](https://valour.gg). This project is not affiliated with or endorsed by Valour.

---

## Data Retention

Because this tool runs entirely in your browser and stores nothing, **no data persists** after you close or refresh the page. Your bot token and other inputs exist only in memory for the duration of your session.

---

## Changes to This Policy

This policy may be updated occasionally. The date at the top of this file reflects when it was last revised.

---

## Contact

If you have questions about this privacy policy, please open an issue on the [GitHub repository](https://github.com).
