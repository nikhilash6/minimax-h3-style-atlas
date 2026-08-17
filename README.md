# MiniMax H3 Style Atlas

A browsable index of all **941 distinct visual styles** across the 1,000 video clips in the
[ostris/minimax_h3_1k](https://huggingface.co/datasets/ostris/minimax_h3_1k) dataset.

Each style entry shows the opening style descriptor from the clip's caption plus a still frame
from the video. Styles are grouped into eight media categories (live-action cinematic, film stock
& era looks, documentary & broadcast, amateur/found footage, 2D animation, stop-motion &
puppetry, 3D/CG & game renders, and specialty imaging), with a live text filter for browsing.

## Two ways to use it

**Offline bundle (recommended):** download
[`minimax-h3-style-atlas-offline.zip`](https://github.com/hoodtronik/minimax-h3-style-atlas/releases/latest/download/minimax-h3-style-atlas-offline.zip)
(~1.4 GB) from the [Releases page](https://github.com/hoodtronik/minimax-h3-style-atlas/releases),
extract it, and open `index.html`. Clicking any still plays the clip instantly from the bundled
`videos/` folder — fully offline, nothing streams. The bundle also includes all 1,000 caption
files and `STYLES.md`.

**Online:** browse the [atlas on GitHub Pages](https://hoodtronik.github.io/minimax-h3-style-atlas/)
(stills only). To play clips there, either grab the offline bundle above, or download the dataset
from [ostris's Hugging Face page](https://huggingface.co/datasets/ostris/minimax_h3_1k) and use the
page's **Connect local folder** button (Chrome/Edge) to play your local copies in-page. The online
atlas never streams video from Hugging Face, so browsing it costs the dataset author nothing.

## Credits

All videos and captions are from the [minimax_h3_1k](https://huggingface.co/datasets/ostris/minimax_h3_1k)
dataset by **[ostris](https://huggingface.co/ostris)** — 1,000 clips generated with MiniMax Hailuo,
each with a detailed multimodal caption. This repository only adds the index/browsing layer;
the thumbnails are single frames extracted from his clips.

The offline bundle redistributes the dataset's videos and captions for convenience, with full
attribution. The original dataset does not declare a license; if ostris would prefer the bundle
not be redistributed here, it will be removed on request.
