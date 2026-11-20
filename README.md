# GTA 6 Meme — "Lucia broke out of prison. The ghost broke the bank. Legally."

make.fun bounty `gta6-meme-x-01` ($500, top 50): post a GTA 6 meme on X.

The picture: a neon-lit bank vault in Vice City at night. Lucia (orange
jumpsuit) and Jason (duffel bag) wait in the doorway — and the make.fun
ghost walks out of the vault with the money, holding its magenta star coin.

Top caption: "LUCIA BROKE OUT OF PRISON."
Bottom caption: "THE GHOST BROKE THE BANK. LEGALLY."

`main.ts` (Node 22, stdlib only) writes `meme.png` to `$MAKEFUN_OUTPUT_DIR`
and copies `POST.json` there when it exists (added after the meme is posted
on X). Run locally with:

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```
