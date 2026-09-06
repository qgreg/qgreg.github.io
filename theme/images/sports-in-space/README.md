# Sports in Space — concept art slots

One image per sport. Name each file for its `asset_tag` in
`/sports-in-space.json`, with a `.jpg` extension:

    basketball_planetary_dome.jpg
    hockey_rotating_habitat.jpg
    football_lunar_dome.jpg
    soccer_dense_atmosphere.jpg
    baseball_lunar_dome.jpg

The page probes each path and swaps the image in when it loads; a missing file
falls back to a labelled placeholder, so partial delivery is fine and no code
change is ever needed.

Suggested export: 1600px wide or larger, JPEG, under ~400 KB. Slots are 16:9.

Generation prompts live in `/sports-in-space-assets.md`.
