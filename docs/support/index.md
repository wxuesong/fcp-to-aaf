---
layout: default
title: FCP to AAF Support
permalink: /support/
---

# FCP to AAF Support

FCP to AAF converts Final Cut Pro XML projects into AAF audio handoffs on your Mac.

## Getting started

1. Export an FCPXML file or project bundle from Final Cut Pro.
2. Open it in FCP to AAF and grant access to the source media folders when prompted.
3. Select audio roles, export settings, and a handoff location.
4. Check the project and export the AAF.
5. Import it in your receiving application and verify media links, channels, and sync.

## Common questions

### Why does the app request media folder access?

Selecting an XML does not grant access to every file referenced inside it. Select the source media folder when prompted. Full Disk Access is not required. If files have moved, add their new location under Media Locations.

### Embedded PCM or External WAV?

Embedded PCM stores audio inside the AAF. External WAV creates an Audio folder that must be delivered with the AAF. After moving the handoff, relink to that folder if needed.

### Are compound and multicam clips supported?

Yes. Compound clips and explicitly selected multicam audio angles in the XML are expanded. Some role trimming, mute, or routing within multicam angles requires expansion or rendering in Final Cut Pro first.

### Are keyframes and effects preserved?

Keep Keyframes transfers volume keyframe positions and values, plus necessary clip and fade boundaries. Compound gain layers are combined; refine curves and final sound in the mix. Supported constant-speed changes are rendered and may sound different from Final Cut Pro.

Complex speed curves, reverse playback, synchronized clips, and some effects require preparation or rendering first. Video and OMF export are not supported.

## Contact and bug reports

Please [open an issue on GitHub](https://github.com/wxuesong/fcp-to-aaf/issues) for help or feature requests, or [submit a new report](https://github.com/wxuesong/fcp-to-aaf/issues/new).

Include your macOS version, app version, receiving application, export settings, and steps to reproduce. A GitHub account is required to post. Issues are public: do not include confidential media, credentials, or private project details. Redact file paths before sharing logs.

Read the [Privacy Policy]({{ '/privacy/' | relative_url }}) to learn how FCP to AAF handles data.
