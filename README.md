# README

This is a birthday card for my old man. Can be found [here](https://pops-bday-card-2024.netlify.app)

May repurpose for other cards in the future though.

## Open repo locally

The animation to open and close is done with CSS so you can simply open the index.html in the browser to view it

or run this cli command in the directory of the repo:

```bash
open -a 'brave browser.app' index.html
```

but to view the confetti animation you need to run a server

pull one up in the directory of the repo by running:

```bash
python3 -m http.server 8000
```

then go to `http://localhost:8000/` in the browser

## Fixes

- [ ] Doesn't work on mobile because I'm using a hover event
- [ ] Problem with card being too zoomed in on different browsers
