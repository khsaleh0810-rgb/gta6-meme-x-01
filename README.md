# GTA 6 meme — make.fun bounty gta6-meme-x-01

A GTA 6 meme for make.fun's "Post a GTA 6 meme on X" bounty: 2013 vs 2026 — one gamer waits thirteen years for GTA 6 and grows a grey beard doing it, while the make.fun ghost beside him shows his AI agent already got paid.

The meme is posted on X from a public account. `POST.json` at this repository's root names the post's address; `main.ts` copies it to `/output/POST.json` for the grader.

## Run it locally

    mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts

`out/POST.json` is then byte for byte this directory's `POST.json`.
