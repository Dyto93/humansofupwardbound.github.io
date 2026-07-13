# Humans of LBCC Upward Bound

A responsive, single-page starter website for the **Humans of LBCC Upward Bound** personal brand. It uses a black, white, and LBCC-inspired red visual system, with a bold editorial layout based on the supplied reference.

## Files

- `index.html` — page structure and all website copy
- `style.css` — responsive visual design for desktop and mobile

## Preview locally

Double-click `index.html` to open it in a browser. No installation or build step is required.

## Add your own photos

The page currently uses styled placeholders so it can be published without borrowing any images. To add a photo, replace a placeholder figure with an image, for example:

```html
<figure class="media-frame photo-one">
  <img src="assets/images/campus-visit.jpg" alt="Upward Bound students on a campus visit" />
</figure>
```

Then add this once to `style.css`:

```css
.media-frame img,
.media-frame video,
.media-frame iframe {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
}
```

Create an `assets/images` folder beside `index.html` and put your picture files there. Use descriptive `alt` text for every meaningful image.

## Add a video

Replace the `div` with class `video-frame` with a native video or an embedded YouTube/Vimeo iframe. Native video example:

```html
<video class="video-frame" controls poster="assets/images/video-poster.jpg">
  <source src="assets/videos/student-story.mp4" type="video/mp4" />
  Your browser does not support video playback.
</video>
```

For YouTube or Vimeo, use an `iframe` with a clear title and the same `video-frame` class. Keep embedded videos at a 16:9 ratio.

## Publish with GitHub Pages

1. Create a new GitHub repository, such as `humans-of-lbcc-upward-bound`.
2. Upload `index.html`, `style.css`, and any `assets` folder contents to the repository’s top level.
3. On GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder, then save.
6. GitHub will show the public site link after it finishes publishing.

## Before publishing

- Replace the sample email address, phone number, social handle, and address if needed.
- Add official LBCC/Upward Bound imagery only with appropriate permission.
- Confirm that your use of LBCC names and marks follows program and college guidance.
- Update the copyright year in `index.html` when appropriate.

