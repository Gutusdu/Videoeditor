# TOUCHLINE STUDIO

A free, browser-based football analysis video editor for vertical short-form videos.

## Run
Open `index.html` in a modern browser. No build step, account, API key, or paid service is required.

## Current features
- 9:16 canvas preview (1080 × 1920)
- Scene templates: hook, stats comparison, tactics board, player spotlight, prediction
- Edit, duplicate, reorder, and delete scenes
- Timeline and scene-duration estimate
- Local project export/import as JSON
- Browser-native WebM video export

## Important limitations
- Statistics and player information are entered manually. The app does not fetch live match data.
- It does not currently provide verified event data, player tracking, heatmaps, pass maps, or automated tactical analysis. Never present manually entered or illustrative values as verified facts.
- Video export is WebM. MP4 conversion and integrated voice-over/subtitle workflows are not implemented yet.
- Projects remain in the browser unless exported as JSON.

## Roadmap
1. Reliable data-source workflow with citations and provenance per statistic.
2. Tactical board with editable player positions, arrows, and movement paths.
3. Voice-over recording, timed subtitles, and audio/video synchronization.
4. MP4 export where browser support permits, with a documented fallback.
5. Responsive editing workflow and robust project persistence.

## Privacy
The current app is client-side. It does not send project content to a server.
