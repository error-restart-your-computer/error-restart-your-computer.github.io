# ERROR — my little corner of the internet

A personal website. Plain HTML, CSS and a little JavaScript — no frameworks, no build step, no dependencies.

**Live:** [error.is-a.dev](https://error.is-a.dev) · [error-restart-your-computer.github.io](https://error-restart-your-computer.github.io)

**Source:** [github.com/error-restart-your-computer/error-restart-your-computer.github.io](https://github.com/error-restart-your-computer/error-restart-your-computer.github.io)

## What's here

| File                | What it does                                      |
| ------------------- | ------------------------------------------------- |
| `index.html`        | The whole site — markup, styles and scripts       |
| `404.html`          | Custom "your computer needs to restart" 404 page  |
| `favicon.png`       | Tab icon (the `:(` from a BSOD, cropped and centered) |
| `chess.png`         | Chess screenshot shown in the project modal       |
| `chess-brilliant.png` | Chess watch-mode screenshot in the modal         |

## Features

- **Projects grid** — Chess, SATISFY and Password Generator, each clickable for a detail modal with the full feature list and a GitHub link
- **Language filter** — All / C++ / Python buttons filter the project cards
- **Sections** — About, Working on, Languages, Interests, Find me
- **Custom scrollbar** — thin, plain, matches the theme
- **Fully responsive** — one column on phones, grid on desktop
- **Light on the eyes of machines** — semantic HTML, keyboard-accessible modals, `prefers-reduced-motion` respected

## Easter eggs

There are two. Finding the first one is easy: type `restart` anywhere on the page.

The second one is for people who open developer tools.

## Run it locally

```sh
git clone https://github.com/error-restart-your-computer/error-restart-your-computer.github.io.git
cd error-restart-your-computer.github.io
python3 -m http.server 8000
```

Then open http://localhost:8000. You can also just open `index.html` directly in a browser — it needs no server.

## Deploying

Push to the [error-restart-your-computer.github.io](https://github.com/error-restart-your-computer/error-restart-your-computer.github.io) repository and GitHub Pages publishes it automatically. The `error.is-a.dev` domain is a CNAME pointed at that repo via [is-a.dev](https://is-a.dev).

When you add images or pages, push those files too — otherwise the links will 404 on the live site.

---

Made by **error_restart_your_computer** · [GitHub](https://github.com/error-restart-your-computer) · [Discord](https://discordapp.com/users/1305891894106128464)
