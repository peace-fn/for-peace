# Just Thinking of You ♡

A cute single-page website designed for GitHub Pages.

## Publish on GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` (and the `images` folder if you add photos).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select your main branch and `/ (root)`.
6. Save. GitHub will give you your Pages URL.

## Add your photos

Create an `images` folder and add your photos. In `index.html`, replace a placeholder like:

```html
<div class="photo">
  <div><strong>📷 First meet</strong><small>Replace with your photo</small></div>
</div>
```

with:

```html
<div class="photo">
  <img src="images/first-meet.jpg" alt="Our first meet">
</div>
```

Repeat for the other timeline cards.

## Customize

Search `index.html` for the text in quotes and replace it with your own memories, inside jokes, dates, or messages.
