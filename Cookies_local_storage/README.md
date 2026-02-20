# Cookies & Local Storage

## Description

This project explores how browsers store data client-side using **Cookies**, **Local Storage**, and **Session Storage**. Each task builds on the previous one, progressively introducing more advanced concepts through a series of vanilla JavaScript HTML pages.

## Setup

```bash
npm install
node_modules/.bin/webpack-dev-server
```

Access pages at `http://localhost:8080/<filename>.html`

## Tasks Overview

| File | Description |
|------|-------------|
| `0-index.html` | Set and display cookies using basic inputs |
| `1-index.html` | Set cookies with expiration date (10 days) |
| `2-index.html` | Read cookies with a `getCookie` function |
| `3-index.html` | Delete cookies and build a mini login/logout app |
| `4-index.html` | Use `js-cookie` library for all cookie operations |
| `5-index.html` | Basic shopping cart using Local Storage |
| `6-index.html` | Basic shopping cart using Session Storage |
| `7-index.html` | Advanced shopping cart with quantities using Session Storage |

## Requirements

- Vanilla JavaScript only (except Task 4 which uses `js-cookie` via CDN)
- No frameworks
- All DOM manipulation done via JavaScript
- `src/index.js` must stay empty — all JS lives in `<script>` tags inside HTML files

## Repository

- **GitHub repository:** `holbertonschool-web_front_end`
- **Directory:** `Cookies_local_storage`