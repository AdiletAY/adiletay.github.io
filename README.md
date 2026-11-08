# thejustise site

Static pages served by GitHub Pages: the developer page and each game's privacy policy.

| Page | Path | URL once published |
|---|---|---|
| Developer page | `index.html` | `https://<username>.github.io/` |
| BlastQuake privacy policy | `blastquake/privacy/index.html` | `https://<username>.github.io/blastquake/privacy/` |

## Publishing
1. Create a **public** repository named `<username>.github.io` (your GitHub username). Pages then serves it at the root of that address, which `app-ads.txt` needs.
2. Push this folder to its `main` branch.
3. In the repository: Settings › Pages › Build and deployment › Deploy from a branch › `main`, `/ (root)`.
4. Open the URLs above and check them before entering the privacy policy URL in Play Console.

The URL must not change once it's in the store listing and in the game. Renaming the account or the repository breaks it.

## Still to add
- `app-ads.txt` at the root, once the AdMob account exists. AdMob shows its exact line (it starts `google.com, pub-…`). Put the same address in the store listing as the developer website.

## Updating a policy
Change the page, then the "Last updated" date at its top.
