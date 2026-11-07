# Rumbo · Your payments compass

Rumbo helps the payments team of a European online shop decide which payment providers and local payment methods to launch with in a new market (Brazil, Mexico, Colombia, Chile, Peru), based on how similar merchants actually perform. The AI suggests; the payments team decides.

Group project for *Artificial Intelligence and Strategic Decisions*, IE Business School (2026). Not a commercial product.

- All approval rates, fees and peer groups are **synthetic**. Provider names are anonymized archetypes.
- The only real figure is Brazil's online checkout mix (Pix 42%, cards 41%), from EBANX 2025 as reported by PYMNTS.

## Structure
- `index.html`: the whole site (homepage and workspace), plain HTML, CSS and JavaScript, no build step.
- `assets/`: favicon, logo files and the social preview image.
- `netlify.toml`: Netlify settings (publishes the repository root as is).

## Deploy
Netlify: "Add new site" → "Import an existing project" → GitHub → this repository. Leave the build command empty and the publish directory as `.`. Every push to `main` redeploys.

The page is set to `noindex` so search engines don't list it. Remove the `<meta name="robots" content="noindex">` line in `index.html` if you want it to appear in search results.
