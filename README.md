# Clone

A front-end clone of Instagram's core UI — feed, stories, chat, search, and profile pages — built with plain HTML, CSS, and JavaScript.

![Status](https://img.shields.io/badge/status-in%20development-yellow)
![License](https://img.shields.io/badge/license-MIT-blue)
![Version](https://img.shields.io/badge/version-1.0.0-lightgrey)

🔗 **Live Preview:** [truelineofficail-hub.github.io/clone](https://truelineofficail-hub.github.io/clone/)

[
![Front Page Screenshot](./image/post/27.jpg)

]

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [Testing](#testing)
- [License](#license)
- [Contact](#contact)

## Features

- 📱 Instagram-style feed with posts, likes, and captions
- 📖 Stories bar with clickable profile avatars
- 💬 Chat page UI
- 🔍 Search page UI
- 👤 Profile page
- 🎨 Responsive layout mimicking Instagram's design language
- ⚡ No build step required — pure HTML/CSS/JS

## Tech Stack

- **HTML5** — page structure
- **CSS3** — styling and responsive layout
- **JavaScript (vanilla)** — interactivity
- **GitHub Pages** — hosting/deployment

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/truelineofficail-hub/clone.git
   cd clone
   ```
2. No dependencies to install — this is a static site.
3. Open `index.html` directly in your browser, **or** serve it locally:
   ```bash
   npx serve .
   ```
   (or use the VS Code "Live Server" extension)

## Usage

Once running locally or via GitHub Pages, navigate between pages using the bottom/top nav bar:

| Page | Path |
|------|------|
| Feed | `index.html` / `pages/feed.html` |
| Chat | `pages/chat.html` |
| Search | `pages/search.html` |
| Profile | `pages/profile.html` |

To add a new post to the feed, duplicate a post block in `feed.html` and update the image, username, and caption:

```html
<div class="post">
  <img class="post-image" src="image/post/your-image.jpg" alt="Post">
  <p><strong>username</strong> Your caption here</p>
</div>
```

## Project Structure

```
clone/
├── index.html
├── pages/
│   ├── feed.html
│   ├── chat.html
│   ├── search.html
│   └── profile.html
├── image/
│   ├── pfp/       # profile pictures
│   └── post/       # post images
├── css/
├── js/
└── README.md
```

## Configuration

This project has no environment variables or build configuration — all content (images, captions, usernames) is edited directly in the HTML files or a JS data file, depending on your setup.

## Contributing

Contributions are welcome!

1. Fork the repo
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add feature"`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

Please avoid committing real personal photos or private data — use placeholder/stock images only.

## Testing

This is a static site with no automated test suite. To verify changes:

1. Open each page in a browser and check layout/responsiveness
2. Validate HTML at [validator.w3.org](https://validator.w3.org)
3. Test on mobile viewport sizes (DevTools device toolbar)

## License

Distributed under the MIT License. See `LICENSE` for details.

## Contact

Maintainer: [Your Name / GitHub handle]
Issues & suggestions: open a GitHub Issue on this repo
