# JimmyPla6z.github.io — My GitHub Hub

Welcome to my personal GitHub Hub!  
This website is built with static HTML, CSS, and JavaScript and is automatically published using [GitHub Pages](https://pages.github.com/).

It fetches and displays my public GitHub content using the GitHub public API, including:
- **Profile summary:** Avatar, name, bio, and basic stats
- **Repositories:** All my public repositories, sorted by stars
- **Starred repositories:** All public repositories I’ve starred
- **Recent public activity:** Issues, PRs, pushes, and more, as shown by the public GitHub Events API

No private data, authentication, or server-side logic required!

---

## Features

- **Live Data:** The site always shows the latest public info from [my GitHub profile](https://github.com/JimmyPla6z)
- **Single Page App:** All content is loaded dynamically and presented in easy-to-navigate tabs
- **Mobile Friendly:** Responsive layout for desktop and mobile
- **No External Dependencies:** Only uses browser-native HTML, CSS, and JS

---

## How it works

- **index.html** is the main file—just open it in a browser or publish it on GitHub Pages.
- JavaScript fetches my GitHub profile, repos, stars, and public events using the [GitHub REST API](https://docs.github.com/en/rest).
- Only public data is shown. Private or “contributions graph” data is NOT displayed due to API limitations.
- No frameworks or build steps needed.

---

## How to use as a template

1. **Fork this repo** or use it as a template
2. Edit `index.html` and replace all instances of `JimmyPla6z` with your own GitHub username
3. Update the contact info or add your own customizations
4. Push to a branch named `main` (or `master`) and enable GitHub Pages in your repo settings

Your own GitHub Hub will be live at `https://<your-username>.github.io`!

---

## License

MIT License — see [LICENSE](LICENSE) for details.

---

*Built and maintained by [JimmyPla6z](https://github.com/JimmyPla6z)*
