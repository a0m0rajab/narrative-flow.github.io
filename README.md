# Visual Narrative Flow

_Authors:_ Sean McKenna, Nathalie Henry Riche, Bongshin Lee, Jeremy Boy, and Miriah Meyer

**Visual narrative flow** for data visualization storytelling is defined as "as the congruence between flow-factors, i.e., 1) the way the reader navigates the story, 2) the visual components of the story, and 3) the type of visual feedback the reader receives; along with the nature of the data and facts that the author wants to communicate." For this work, we focus on the congruence of flow-factors.

These supplemental materials can be downloaded and are included in the submission ZIP file. Because several pages load D3 data files directly in the browser, the site should be served from a web server instead of opened from disk. You can also view the published site at:

https://narrative-flow.github.io/

The links on the project page are anonymous, and the form/tracking features used in the studies have been modified to disable all server communication.

## Repository structure

This repository is a static website with `index.html` at the root as the landing page for all supplemental materials.

- `assets/`: shared CSS, JavaScript, fonts, and Sass for the landing page
- `images/`: preview images used by the landing page
- `paper/`: the paper PDF
- `story-corpus/`: the corpus in HTML, PDF, and XLSX formats
- `bar-chart-story/`: the standalone bar chart story demo
- `exploratory-study-1/` and `exploratory-study-2/`: study pages and related assets
- `crowdsourced-study/`: study chapters, questionnaire, model visualizations, and study materials

## Run locally

From the repository root, start a simple static server and open the reported local URL:

```bash
python3 -m http.server 8000
```

## Deploy to GitHub Pages

This project does not need a build step; GitHub Pages can publish the repository as a static site directly from the default branch.

1. Push the repository to GitHub.
2. In GitHub, open **Settings** → **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch that contains the site and choose the `/ (root)` folder.
5. Save the settings and wait for GitHub Pages to publish the site.

After deployment, the site will be served from the repository's Pages URL, with the root `index.html` as the entry point.

## Deploy to Netlify

Netlify can also host the repository as a no-build static site.

1. Create a new site in Netlify and connect this GitHub repository.
2. Keep the **Base directory** empty.
3. Leave the **Build command** empty.
4. Set the **Publish directory** to `.`.
5. Deploy the site.

Netlify will serve the repository root, so `index.html` becomes the homepage and all nested study folders remain available at their existing paths.




## Project Page Template Attribution

Fractal by HTML5 UP
html5up.net | @ajlkn
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)


A simple landing page template for showcasing mobile apps (although it'll definitely work
for other stuff if you get rid of the phone :) Lightweight, fully responsive, and built on
Skel 3, Sass, and flexbox.

Demo images* courtesy of Unsplash, a radtastic collection of CC0 (public domain) images
you can use for pretty much whatever.

(* = not included)

AJ
aj@lkn.io | @ajlkn


Credits:

	Demo Images:
		Unsplash (unsplash.com)

	Icons:
		Font Awesome (fortawesome.github.com/Font-Awesome)

	Other:
		jQuery (jquery.com)
		html5shiv.js (@afarkas @jdalton @jon_neal @rem)
		CSS3 Pie (css3pie.com)
		Respond.js (j.mp/respondjs)
		jquery.scrolly (@ajlkn)
		Skel (skel.io)
