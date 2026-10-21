# Tested compatibility (closed beta)

"Tested" means we ran it and measured it. Anything not listed here may work, but hasn't been tested. Results depend
on the plugin version, your DAW version and your setup. Hands also checks **your own** plugins on your computer and
shows which work fully, which work with limits, and which don't.

## Supported setup for the beta
| | Tested | Notes |
|---|---|---|
| **DAW** | Ableton Live 12 (macOS, Apple silicon) | Ears + Hands + DAW control |
| | Logic Pro, FL Studio (macOS) | Ears only |
| | Ableton Live 12 (Windows) | Ears streaming only, without audio. Not a beta platform yet |
| **AI client** | Claude Code (local MCP) | Primary |
| | Claude Desktop, OpenAI Codex CLI (local MCP) | Included once they pass the same install and workflow checks |
| | ChatGPT on the web, claude.ai on the web | Not supported in this beta |
| **Plugin formats in Hands** | VST3, AU | Plugins that expose their parameters to the host |

## Plugins tested in Hands
Full cycle: load, parameter search, set with read-back, undo, save and restore. macOS 27 (Apple silicon), 48 kHz.

| Plugin | Format | Parameters | Also checked in Live 12 |
|---|---|---|---|
| FabFilter Pro-Q 4 (4.1.3) | VST3 | 737 | measured +6.0 dB bell, save/quit/reopen |
| FabFilter Pro-Q 3 | VST3 | 519 | |
| FabFilter Pro-C 2 | VST3 | 183 | |
| FabFilter Pro-L 2 (2.2.6) | VST3 | 169 | latency 3115 samples reported to Live, save/reopen |
| FabFilter Pro-MB | VST3 | 288 | |
| FabFilter Pro-R 2 | VST3 | 273 | |
| FabFilter Saturn 2 | VST3 | 1088 | measured, save/reopen |
| FabFilter Timeless 3 | VST3 | 1144 | |
| FabFilter Volcano 3 | VST3 | 1033 | |
| FabFilter Pro-DS | VST3 | 157 | |
| FabFilter Pro-G | VST3 | 172 | |
| oeksound soothe2 | VST3 | 57 | |
| Xfer Records OTT | VST3 | 21 | |
| Nicky Romero Kickstart 2 | VST3 | 2093 | |
| ValhallaVintageVerb | VST3 | 18 | |
| XLN Audio RC-20 Retro Color | VST3 | 59 | |
| Cableguys ShaperBox 3 | VST3 | 5037 | saves its state late: wait a moment after a change before saving |
| Cytomic The Drop | VST3 | 2213 | |
| Schwabe Digital Gold Clip | VST3 | 23 | |
| Rare Signals Transatlantic Plate Reverb | VST3 | 10 | |
| Polyverse Music Wider | VST3 | 5 | |
| Cradle The God Particle | VST3 | 11 | |
| Apple AUNBandEQ | AU | 41 | |
| Apple AUDynamicsProcessor | AU | 7 | |
| Apple AUDelay | AU | 4 | |

A plugin that isn't here? Run the plugin check in Hands, and use **Report this plugin** if it doesn't work fully.
