# Frigate Home Assistant Blueprints with GenAI

This repo contains Home Assistant blueprints for Frigate camera notifications, extended with support for GenAI captions and optional Pushover notifications.

## 📦 Available Blueprints

### ✅ Full Version
Full-featured Frigate notification with:
- GenAI caption support
- Mobile app push notifications
- Optional Pushover support
- TTS notification

[![Import Full Version](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/nickysqueekz/frigate-ha-blueprints/refs/heads/main/frigate-GenAI-notifications-full)

---

### 💡 Minimal Version
Lightweight Frigate notification with:
- GenAI caption support
- Mobile or Pushover notification
- Clean and simple logic

[![Import Minimal Version](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/nickysqueekz/frigate-ha-blueprints/refs/heads/main/frigate-GenAI-notifications-minimal)

---

## 🛠 Setup

1. Make sure Frigate sends MQTT events to Home Assistant
2. Use the snapshot URL from Frigate:
   ```
   https://your-ha-url/api/frigate/notifications/{{trigger.payload_json.after.id}}/snapshot.jpg
   ```
3. Optional: Set up [Pushover integration in HA](https://www.home-assistant.io/integrations/pushover/)

## 👷 Support

These blueprints are tested with Frigate v0.15+ and Home Assistant 2024.x. If you find issues, open a PR or issue in the repo.
