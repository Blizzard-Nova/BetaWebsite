# BetaWebsite

A small, beginner-level HTML website built for practice and experimentation. As the homepage puts it, the site doesn't serve any particular purpose and is just a way of "testing the waters" with HTML.

## Pages

| File | Description |
| ---- | ----------- |
| `index.html` | Landing page titled "BETATEST" with a welcome message and a link to the next page |
| `Page1.html` | A "Points" page with a link to a YouTube video, a link to the login page, a small image-decorated ordered list (Games, Anime, Movies) and a nested unordered list (Novels, Mangas, Comics) |
| `login.html` | A dummy registration form for practicing HTML form elements |

The repository also contains a `.github/workflows` folder for GitHub Actions.

## Navigation

```
index.html  →  Page1.html  →  login.html
```

## HTML Concepts Practiced

- Basic document structure (`<!DOCTYPE html>`, `<head>`, `<body>`, `<title>`)
- Hyperlinks to internal pages and external sites (`<a>`)
- Images with set dimensions (`<img>`)
- Ordered and nested unordered lists (`<ol>`, `<ul>`, `<li>`)
- Forms and inputs: text, email, password, date, radio buttons, checkboxes, a dropdown and submit/reset buttons
- Built-in browser validation with the `required` attribute
- HTML comments

## Getting Started

No installation or build step is needed.

```bash
git clone https://github.com/Blizzard-Nova/BetaWebsite.git
cd BetaWebsite
```

Then open `index.html` in any web browser.

## Notes

- The login form is a front-end demo only. It uses `method="GET"` and has no backend, so nothing is stored or authenticated.
- Do not enter real personal information into the form. With `GET`, submitted values (including the password) appear in the page URL.

## Ideas for Improvement

- Add CSS for styling and a consistent layout
- Make the pages responsive with a viewport meta tag
- Add `alt` text to images and group the radio buttons by sharing the same `name`
- Add JavaScript for client-side form handling
- Host the site with GitHub Pages

## License

No license has been specified yet.
