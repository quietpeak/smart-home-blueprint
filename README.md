# Smart Home Blueprint (Home Assistant + Apple Home)

Reference architecture for a privacy-first smart home setup running Home Assistant on a Raspberry Pi bridged to Apple Home.

## Core Stack
- **Hub / Bridge:** Raspberry Pi running Home Assistant
- **Ecosystem:** Apple TV & HomePod Mini (Matter / HomeKit hubs)
- **Security & Sensors:** Presence sensor (mmWave), Doorbell, Smart Lock, IP Camera
- **Lighting & Power:** Smart Wi-Fi/Matter bulbs, smart plugs
- **Audio & Cleaning:** Sonos speakers, Robot vacuum

## Best Practices
- Assign static DHCP reservations by MAC address on your router.
- Keep your real IP/MAC inventory in a **private** repository.
- Use `inventory.example.md` as a starting template.
