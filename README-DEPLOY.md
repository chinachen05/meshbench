# MeshBench — Website #37

Static HTML/CSS/JavaScript. No build step, database, user login, framework or dependency installation required.

## Configuration
- Proposed domain: https://meshbench.vercel.app — **availability and deployment not verified**.
- Contact email: chinachen05@gmail.com
- AdSense publisher: ca-pub-2936167858814999
- Exact AdSense verification script is present once on the homepage and each of the 35 substantive article pages. No script is loaded by calculator-only, notebook, navigation or legal pages.
- `ads.txt`: `google.com, pub-2936167858814999, DIRECT, f08c47fec0942fa0`.
- 35 original focused field notes, with 4 practical tools. Each article contains its own source references, diagnostic checks, steps, concrete example, failure mode, and when-to-stop guidance.

## Deploy on GitHub + Vercel
1. Unzip. Upload **contents** to the root of a new GitHub repository (do not nest the entire site within a parent folder).
2. Import GitHub repository to Vercel. Select **Other** or static framework, no build command; output the root folder.
3. Assign the exact domain `meshbench.vercel.app` if available.
4. Verify `https://meshbench.vercel.app/`, `/guides/index.html`, `/mesh-cut.html`, `/roll-layout.html`, `/spline-length.html`, `/panel-notebook.html`, `/ads.txt`, `/robots.txt` and `/sitemap.xml`.
5. If Vercel assigns another URL, replace **every occurrence of `meshbench.vercel.app`** in .html, `sitemap.xml`, `robots.txt` and this README before requesting indexing. Do not leave two inconsistent domains/canonicals.
6. Add your actual domain to Google Search Console and submit sitemap; verify the 200 status and indexability of editorial articles.
7. In AdSense, ensure the **actual AdSense account** is eligible, not a duplicate account for the same payee, and the site's status permits a review. The script/ads.txt alone do not establish approval.
8. Respect AdSense and local consent obligations (including any required Google-certified CMP for EEA/UK/Switzerland traffic). No fictional consent banner was added.

## Content integrity
- External links: manufacturer Phifer, Andersen; CDC and U.S. Consumer Product Safety Commission.
- No images copied from Pinterest or other copyrighted sources; graphics created as SVG specifically for MeshBench.
- No fabricated author credentials, performance claims, affiliate partnerships or testimonials.
- Mesh cut and roll estimates have explicit user-controlled working assumptions; spline calculator computes *length*, not diameter; no tool certifies safety or frame fit.

## QA checklist
Search categories; test tools at ordinary and invalid inputs; add a panel, refresh, export CSV; test mobile menu; check all sources; review Google Search Console after deployment. Always recheck after any code changes.
