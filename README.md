# Home Assistant Automation Blueprints

Free, production-tested automation blueprints for Home Assistant. Built from a real 700+ entity smart home with ELK M1 security, UPB lighting, Vivotek cameras, and Piper TTS voice announcements.

## Blueprints

### Motion-Activated Night Light
Turn on a light at low brightness when motion is detected during nighttime hours. Auto-off after configurable timeout. Won't re-trigger if light is already on.

[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fbeslain%2Fha-automation-blueprints%2Fblob%2Fmain%2Fblueprints%2Fnight-light-blueprint.yaml)

**Want more?** The full [Night Lights & Motion Pack](https://beslain.gumroad.com/l/ha-night-lights-pack) includes 8 pre-built room configs, camera-triggered exterior lighting, color temperature curves, and multi-zone coordination.

---

### Alarm Voice Announcement
Announce alarm state changes through any media player using TTS. Supports armed away, armed night, armed home, and disarmed with contextual messages.

[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fbeslain%2Fha-automation-blueprints%2Fblob%2Fmain%2Fblueprints%2Falarm-voice-blueprint.yaml)

**Want more?** The full [Jarvis Voice Announcement Pack](https://beslain.gumroad.com/l/ha-jarvis-voice-pack) includes 12 automations, centralized announce script with room routing, speaker groups, custom phrase templates, and a Piper TTS setup guide.

---

### Door Alert with Delay
Get notified when a door is left open longer than a configurable threshold. Works with any binary sensor (door/window contact, garage).

[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fbeslain%2Fha-automation-blueprints%2Fblob%2Fmain%2Fblueprints%2Fdoor-alert-blueprint.yaml)

**Want more?** The full [ELK M1 + HA Security Blueprint](https://beslain.gumroad.com/l/elk-m1-ha-security-blueprint) includes 10+ production automations for alarm response, security modes, zone logging, camera AI integration, and a complete wiring reference.

---

## About

These blueprints are extracted from a live system running:
- **ELK M1** alarm panel (80 zones, M1XEP ethernet interface)
- **54 UPB** hardwired light switches
- **4 Vivotek** 5MP cameras with AI object detection
- **Piper TTS** with custom Jarvis voice on 7 distributed speakers
- **700+ entities** across 11 automation packages

Everything is local. No cloud. No subscriptions.

## Full Automation Packages

| Package | What's Included | Price |
|---------|----------------|-------|
| [ELK M1 Security Blueprint](https://beslain.gumroad.com/l/elk-m1-ha-security-blueprint) | 10+ automations, alarm response, zone logging, camera integration, wiring guide | $49 |
| [Night Lights & Motion Pack](https://beslain.gumroad.com/l/ha-night-lights-pack) | 8 room configs, camera-triggered exterior, color temp curves | $19 |
| [Jarvis Voice Pack](https://beslain.gumroad.com/l/ha-jarvis-voice-pack) | 12 automations, announce script, speaker groups, Piper setup | $29 |
| [Complete Bundle](https://beslain.gumroad.com) | All 3 packages | $79 |

Use code **LAUNCH50** for 50% off any product.

## Newsletter

Get weekly Home Assistant automation tips, YAML recipes, and security integration guides:

[Subscribe to The Automated Home](https://theautomatedhome.beehiiv.com)

## License

These blueprints are free to use and modify. Attribution appreciated but not required.
