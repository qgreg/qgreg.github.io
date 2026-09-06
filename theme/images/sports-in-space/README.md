# Sports in Space — concept art slots

Drop generated images here named exactly for their `asset_tag` in
`/sports-in-space.json`, with a `.jpg` extension:

    header_banner.jpg
    basketball_planetary_dome.jpg
    soccer_dense_atmosphere.jpg
    football_canyon_dome.jpg
    hockey_rotating_habitat.jpg
    baseball_zero_g_chamber.jpg
    basketball_rotating_ring.jpg
    soccer_zero_g_sphere.jpg
    football_habitat_corridor.jpg
    hockey_ice_moon_rink.jpg
    baseball_high_g_dome.jpg

The page probes each path and swaps the image in automatically when it loads;
a missing file falls back to a labelled placeholder, so partial delivery is fine
and no code change is ever needed.

Suggested export: 1600px wide or larger, JPEG, under ~400 KB each. The banner is
laid out at a 21:7 aspect ratio; row cards are 16:10.

Generation prompts for each tag live in `/sports-in-space-assets.md` and are also
copy-to-clipboard on the page itself.
