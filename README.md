# A Letter For You — deployment

1. Put your two photos in the `photos/` folder, named exactly `photo1.jpg` and `photo2.jpg`
   (any other name/format: edit the two `<img src="photos/...">` lines near the bottom of the HTML body in index.html).
   Resize each to ~1600px on the long side (under ~500 KB) so it loads fast.
2. Netlify (easiest, no account CLI): open https://app.netlify.com/drop, sign in, drag this whole folder onto the page.
   You get an https://something.netlify.app link in seconds. Site settings > Change site name for a nicer URL.
3. Vercel: push the folder to a GitHub repo, then at vercel.com choose Add New > Project > Import the repo > Deploy
   (framework preset: Other, no build command). Or run `npx vercel --prod` inside the folder.
4. Open the link on your phone and a laptop, and test every page and the scratch-off before sharing.
To change a photo later, replace the file and deploy again.
