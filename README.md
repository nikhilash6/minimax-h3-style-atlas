# MiniMax H3 Style Atlas

A browsable index of all **941 distinct visual styles** across the 1,000 video clips in the
[ostris/minimax_h3_1k](https://huggingface.co/datasets/ostris/minimax_h3_1k) dataset.

Each style entry shows the opening style descriptor from the clip's caption, a still frame from
the video, and a link that streams the clip directly from Hugging Face. Styles are grouped into
eight media categories (live-action cinematic, film stock & era looks, documentary & broadcast,
amateur/found footage, 2D animation, stop-motion & puppetry, 3D/CG & game renders, and specialty
imaging), with a live text filter for browsing.

- **[Browse the atlas](https://hoodtronik.github.io/minimax-h3-style-atlas/)** (GitHub Pages)
- [`STYLES.md`](STYLES.md) — plain-text version of the full style list with clip numbers

## Credits

All videos and captions are from the [minimax_h3_1k](https://huggingface.co/datasets/ostris/minimax_h3_1k)
dataset by **[ostris](https://huggingface.co/ostris)** — 1,000 clips generated with MiniMax Hailuo,
each with a detailed multimodal caption. The thumbnails embedded in the atlas are single frames
extracted from those clips; the play links stream the original files from the Hugging Face repo.
This repository only adds the index/browsing layer — go download the dataset itself from ostris's
Hugging Face page.
