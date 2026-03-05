# Valour Planet Joiner

A simple browser-based tool for joining planets on the [Valour](https://valour.gg) platform using a bot token.

---

## Features

- Automatically checks whether a planet is publicly discoverable as you type the Planet ID
- If the planet is discoverable, the invite code field is disabled — no invite needed
- If the planet requires an invite, prompts you to enter one before joining
- All requests are made directly from your browser to Valour's API — nothing is stored or logged

---

## Usage

1. Enter your **Bot Token**
2. Enter the **Planet ID** you want to join
3. Wait a moment — the tool will automatically check if the planet is discoverable
4. If an invite code is required, enter it in the invite field
5. Click **Join Planet**

---

## How It Works

The tool makes the following API calls to `api.valour.gg`:

| Action | Method | Endpoint |
|---|---|---|
| Check discoverable planets | `GET` | `/api/planets/discoverable` |
| Join a planet | `POST` | `/api/planets/{planetId}/join` |
| Join with invite | `POST` | `/api/planets/{planetId}/join?inviteCode={code}` |

Your bot token is sent as an `Authorization: <token>` header with each request.

---

## Privacy

This tool runs entirely in your browser. No data is collected, stored, or sent anywhere other than directly to Valour's API. See [PRIVACY.md](PRIVACY.md) for full details.

---

## Disclaimer

This project is not affiliated with, endorsed by, or officially connected to Valour in any way. Use at your own risk and ensure your bot token usage complies with Valour's terms of service.

---

## License

Copyright (c) 2026 SkyJoshua. All rights reserved. See [LICENSE](LICENSE) for details.

&copy; 2026 Valour Planet Joiner
