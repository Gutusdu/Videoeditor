# TOUCHLINE STUDIO 2.0

A browser-based, local-first multitrack editor for vertical sports videos.

## Open

https://gutusdu.github.io/Videoeditor/

## Studio 2.0

- Multi-track timeline for image, video, text and audio clips
- Upload multiple files and automatically pair visual media with audio by matching file names
- Matched audio duration determines the visual clip duration when media metadata is available
- Drag clips to reposition them, move clips between compatible tracks, and trim either edge
- Clip inspector for start time, duration, in-point, position, scale, opacity, rotation, fit mode and playback speed
- Optional start-to-end keyframe interpolation for position, scale and opacity
- Separate channel profiles for TOUCHLINE (football), TOUCHLINE FOOTBALL (American football) and TOUCHLINE MOTORSPORT
- Per-channel outro storage and one-click outro insertion; quick montage appends the saved outro
- Integrated Wikimedia Commons image search with license filtering and attribution details
- IndexedDB autosave for the current project and media on the current browser/device
- Project JSON export/import with media embedded; legacy scene-based TOUCHLINE JSON import
- 1080 × 1920 project canvas for TikTok, Reels and Shorts

## Export

The editor uses the browser's native MediaRecorder. It exports MP4 when the current browser exposes a compatible MP4/H.264 recorder; otherwise it exports WebM and uses the correct file extension. Export capability and performance depend on the browser and device. Test a short clip before relying on a long production export.

## Existing pages and compatibility

- `legacy.html` preserves the previous Build 30 scene-based editor.
- `audience.html` remains available for private, manually entered TikTok analytics.
- Existing scene-based JSON projects can be imported into Studio 2.0 and converted to timeline clips.

## Storage and privacy

Media and projects are processed in the browser. Autosave uses IndexedDB on the current device/browser. Use **Projekt exportieren** to create a portable backup. Clearing browser site data can remove local autosaves and channel outros.

## Known limitations

- There is no cloud sync between devices.
- No live match-data provider or automated tactical/statistical feed is connected.
- Browser-native export formats, codec support and performance vary by device.
- Very large source files can exceed browser memory or local storage limits.
- Wikimedia Commons licensing information is a starting point; verify the original file page and usage restrictions before publishing.
