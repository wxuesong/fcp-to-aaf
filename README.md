# fcp-to-aaf
Turn FCPXML into an AAF audio handoff. Organize clips by role, choose embedded audio or external WAV, and keep timeline positions.

Convert Final Cut Pro projects into AAF audio handoffs for dialogue, music and sound mixing. 

Features
• Open .fcpxml files and .fcpxmld project bundles.
• Select audio roles and subroles to organize tracks.
• Export embedded PCM or external WAV at 48 kHz / 24-bit PCM.
• Preserve eligible stereo components or split to mono.
• Keep original media names; export full audio or trimmed media with handles.
• Keep volume keyframe positions and values, or choose dry handoff. Compound gain layers are combined.
• Supported compound clips and multicam clips.
• Check source media, locate moved files and validate exported AAF files.

Before delivery
Deliver the Audio folder with external WAV handoffs. Refine curves between keyframes and final sound in the mix; retiming may sound different from Final Cut Pro.
Complex retiming, reverse playback, synchronized clips and some role trimming, mute and routing within multicam angles require expansion or rendering first. Video, OMF and full recreation of plug-ins or mixes are not supported. Input formats depend on macOS decoding support. Verify media links, channels and sync in your receiving application.

Requires an Apple Silicon Mac, macOS 14 or later, and accessible source media. 
