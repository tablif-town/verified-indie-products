# WristBridge

Put Tasker, JSON API and custom data on your Wear OS watch

- **Site:** [play.google.com/store/apps/details?id=com.quazmoz.wristbridge](https://play.google.com/store/apps/details?id=com.quazmoz.wristbridge)
- **Topic:** [Desktop and utilities](../topics/desktop-and-utilities.md)
- **Ownership verified:** 2026-11-23

WristBridge turns custom values, Tasker data, phone battery state and JSON API values into native Wear OS complications and a configurable Tile. Set up sources on your phone; the watch keeps the last synced value, and shows whether data is current, stale or unavailable instead of faking real time. REST credentials stay on the phone. No account or WristBridge cloud. Free covers the core with a few sources; Pro adds REST/JSON, unlimited sources and more, as a one-time unlock.

## Quick answers

Each answer comes with the sentence it is based on, quoted from the product's own pages.

### Is Tasker required to use WristBridge?

No, Tasker is an optional separate app. You only need Tasker if you plan to display Tasker-driven data sources.

> Tasker is a separate app and is only required for Tasker-driven sources.

### Will it work with any watch face?

Only with faces that have a compatible complication slot. How the value looks, and which presentation types you get, depends on the face you pick.

> Watch-face support varies. A compatible complication slot is required for complication display.

### Does my watch need its own internet connection to show API values?

No. The phone fetches the data and syncs it, and the complication and Tile draw from what is already stored on the watch.

> Complication and Tile rendering use synchronized watch-local data rather than making remote API requests directly from the watch.

### Is REST/JSON data included in the free version?

No. REST/JSON sources are a Pro feature. The free version covers the core phone-to-watch workflow with a limited number of sources.

> WristBridge Pro unlocks REST/JSON sources, unlimited sources, and advanced presentation features.

## Longer reads

- [How to show phone battery on Wear OS watch face](https://answers.delivery/wristbridge/how-to-show-phone-battery-on-wear-os-watch-face)

## Raced against well-known names

- [AutoWear vs Home Assistant vs Complications Suite for putting your own data on your Wear OS watch face, and the dark horse](https://darkhorsepick.com/autowear-vs-home-assistant-vs-complications-suite-for-wear-os-data)

---

Part of [Verified indie products](../README.md) · [office in Tablif Town](https://tablif.com/town/a3a42903-206e-4df0-98a8-74376a37ed3e)
