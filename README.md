# Frugal With Seth — Website

Responsive, static website prepared for GitHub and Vercel.

## Publish

1. Extract this ZIP. Upload its contents (not the enclosing directory) to a GitHub repository.
2. Import that repository into Vercel. Framework preset: **Other**. No build command needed. Output directory: project root.
3. Connect your desired domain in Vercel after reviewing the preview.

## Pages

- `index.html`: Homepage featuring Iceland hero, latest video, travel topics, About Seth and newsletter.
- `about.html`: Seth's story.
- `videos.html`: YouTube feature and channel link.
- `resources.html`: Travel-tip categories.
- `contact.html`: YouTube/newsletter calls to action.

## Update the featured video

Replace `g3fOZIK8Qvo` in `index.html` and `videos.html` with the new YouTube video ID. The featured video is currently **manually curated**; it does not automatically update upon a new upload.

## Forms

The GHL newsletter iframe uses form ID `gMBdgS7zAOevqR2bqvjG` and loads GoHighLevel's form embed script. Test the form, opt-in consent, subscription workflow, thank-you action and mobile iframe before launch. The heading is provided outside the embedded form.

## Imagery

- Seth portrait is loaded from the current Frugal With Seth WordPress media library (external URL).
- Iceland hero and supplemental imagery are hosted by Unsplash (external URLs), not copied from Seth's site. Replace with Seth's own Iceland photographs when available; CSS hero image is in `styles.css`.
- Both supplied logos are local in `/assets`.

## Launch checklist

- Confirm rights/authorization for all photos used.
- Confirm embedded YouTube video and GHL form both work on live HTTPS domain.
- Approve Seth's first-person copy and newsletter claims.
- Verify privacy policy/terms and unsubscribe/consent requirements before collecting emails; add appropriate footer links when available.
- Verify Wayfinder credit and link.
- Replace generic / contact page with an actual email or contact form if Seth supplies one.
