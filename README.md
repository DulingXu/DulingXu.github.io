# Duling Xu Homepage

This is a lightweight static homepage for Duling Xu, inspired by the AcademicPages-style layout at `guan-jw.github.io`.

## Files

- `index.html`: homepage content
- `assets/css/style.css`: page styling

## Local Preview

Open `index.html` directly in a browser, or run a simple static server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## GitHub Pages

Push this folder to a repository such as `duling-xu.github.io`, then enable GitHub Pages from the repository settings.

## Photo

The page currently uses an initials avatar (`DX`). To use a real photo:

1. Add a profile image at `assets/images/photo.jpg`.
2. Replace the `.avatar` block in `index.html` with:

```html
<img class="avatar-img" src="assets/images/photo.jpg" alt="Duling Xu" />
```

3. Add this CSS:

```css
.avatar-img {
  width: 168px;
  height: 168px;
  border-radius: 50%;
  object-fit: cover;
  border: 1px solid var(--line);
  margin-bottom: 22px;
}
```
