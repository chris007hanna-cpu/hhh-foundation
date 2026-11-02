# HHH Foundation standalone website

Built 2026-11-02 on Irish's revised direction: HHH gets its own separate website, kept separate from the main Irish + Nova site. Live since 2026-11-02 at https://chris007hanna-cpu.github.io/hhh-foundation/ in its own repo (chris007hanna-cpu/hhh-foundation), awaiting its own domain when Irish picks and approves one.

Alignment pass 2026-11-02: pages restyled to the original Drive site's design (navy #0f172a header and hero gradient, gold #d97706, blue accent #2563eb, light #f8fafc background, white cards with left blue border), with the finished Drive logo in the header and hero and the verse banner "John 3:16 | Love God. Love People." The logo PNG and Irish's four real payment QR PNGs sit in assets/ as source files; because the GitHub connector snapshot route carries UTF-8 text only, the live pages embed the logo and QRs as inline data URIs (the same method the main site's shop page uses).

## Pages
- index.html: home. Logo hero with verse banner, three cards (Strategic Acquisitions, Community & Dignity, Absolute Governance), the money model, the COSL land route, work lanes, sister chapters vision, how we run, formation status.
- about.html: how HHH is run. Chairman and Chief of Staff, the AI Boardroom and departments, bylaws Article III Section 3.3, structure and formation status.
- get-involved.html: follow formation, offer land or property, join a work lane, and giving through the Donate page.
- donate.html: Ways to Give, mirroring the original Drive donate page. Payment cards for Cash App ($Irish0007), Zelle, Chime ($Irish007), and PayPal with Irish's real QR codes and the handles printed on his main site, a text only card noting card giving and web checkout are not open yet, and volunteer, skilled services, and material donation cards. There is no Venmo account, so there is no Venmo card; the page states plainly that HHH does not take Venmo. The page carries the formation disclosure: HHH is in formation, giving runs through Irish's own payment handles until foundation accounts exist, and gifts are not tax deductible.

## Rules baked into the copy
- In formation wording only. No registered nonprofit claim, no tax deductible claim, no donate button, no payment handles.
- No em dashes and no en dashes in public copy.
- Public names are Irish or Chris only in personal references. Hanna Enterprises LLC appears only as the legal entity name that will hold land titles, exactly as the brief required.
- Every page carries a unique keyword title, a 150 to 160 character meta description, og:title and og:description, and exactly one H1.

## Deployment status and the domain step
1. Done 2026-11-02: separate HHH repo created (chris007hanna-cpu/hhh-foundation), this folder's pages pushed as the repo root, GitHub Pages enabled and verified live.
2. When Irish picks and approves a domain: add the approved custom domain in the repo's Pages settings and point DNS at GitHub Pages per GitHub's custom domain instructions.
3. After the domain resolves, add the full domain to each page's og tags and add canonical links in one edit pass.
Hosting on GitHub Pages is free. Domain options and prices live in ../domain-options-2026-11-02.md. No domain has been purchased; purchase needs Irish's explicit approval with the price stated.
