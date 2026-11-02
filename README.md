# Vigil

Whoever you are. Whatever you call God. We'll keep watch with you.

Vigil is a free, non-denominational global prayer web app, kept by its stewards Brad McCorkle and McKayl. It is also a Louder Labs case study in launching for $0.

Live at https://worldvigil.org

## How it is built

- **Front end:** one static page (`index.html`), a web app manifest (`manifest.json`) and a small service worker (`vigil-sw.js`). No build step.
- **Hosting:** GitHub Pages, deployed from the repo root by `.github/workflows/pages.yml` on every push to `main`.
- **Domain:** `worldvigil.org`, DNS at Porkbun, pointed at GitHub Pages.
- **Data:** Wix Headless collections, read and written from the browser with a public visitor OAuth client. Visitors can read approved prayers and vigils and submit to the inbox. They cannot read the inbox or write prayers directly.

## Deploying

Push to `main`. The Pages workflow publishes the repo root, usually within two minutes.

## Privacy and safety

Do not weaken the crisis flow, the privacy rules or the Wix collection permissions. Any change touching those needs a steward's review.

## License

MIT. See [LICENSE](LICENSE).
