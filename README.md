# Hands & Ears: plugin reports and feedback (beta)

Hands & Ears connects your DAW to the AI you choose. **Ears** measures the audio in your session; **Hands** hosts a
plugin and lets your AI change its parameters, with every change read back and reversible.

This repository collects **plugin compatibility reports** and beta feedback. The code isn't here.

## Report a plugin
When Hands can't load a plugin, or can only use part of it, Hands offers **Report this plugin**. It opens a new issue
here, already filled in. You see everything before it's sent, and you click **Submit** yourself.

**What a report contains:** the plugin's name, maker, version and format (VST3 / AU), what happened (works with limits /
doesn't work) and at which step, your DAW and its version, your OS, and the Hands version.

**What it never contains:** file paths, project or track names, audio, or anything that identifies you beyond your
GitHub account.

You can also [file a report by hand](../../issues/new?template=plugin-compat.yml).

## What happens next
Many plugin problems can be fixed without a new release: Hands keeps a list of per-plugin adjustments (timing, names
of controls, known limits) that we update from these reports. Real bugs go into the next Hands update.

## Beta
The beta supports Ableton Live 12 on macOS. Compatibility depends on the plugin, its version and your setup. Hands
checks your own plugins on your computer and tells you which work fully, which work with limits, and which don't.
