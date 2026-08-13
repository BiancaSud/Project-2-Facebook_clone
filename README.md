# Facebook Homepage Clone

A desktop recreation of the Facebook news feed interface, built with HTML and CSS.

**Live site:** https://fb-clone-desktop.netlify.app/  /  
https://biancasud.github.io/Project-2-Facebook_clone/

![Facebook Clone]
<img width="1919" height="958" alt="image" src="https://github.com/user-attachments/assets/eead28ec-cad4-4680-8eb6-fb9dac19ea6e" />


## About

A layout exercise: rebuilding an interface everyone knows, where any misalignment is immediately obvious. Cloning an existing design removes the design decisions and leaves only the CSS problem, which is exactly what made it useful as an early project.

**Desktop only** — this project predates my work on responsive layouts and does not adapt below desktop widths.

## Features

- **Three-column layout** — navigation sidebar, central feed, contacts sidebar
- **Left sidebar** with profile entry, main navigation (Friends, Memories, Saved, Groups, Video, Marketplace) and a user shortcuts group
- **Central feed** — post composer with live video, photo and feeling options, story carousel, and posts carrying author, timestamp, reaction count and comment count
- **Right sidebar** — people you may know with add-friend actions, birthday notifications, and a long contacts list
- **Fixed header** with search and account controls

## Built with

HTML5, CSS3. No frameworks or libraries.

## Running locally

```bash
git clone https://github.com/BiancaSud/Project-2-Facebook_clone.git
cd Project-2-Facebook_clone
```

Open `index.html` in a browser at desktop width.

## What I focused on

Three columns where the outer two stay fixed while the center scrolls — the first layout I built that needed independent scroll regions rather than one flowing page. Matching Facebook's spacing also forced a level of precision I had not needed before: in a familiar interface, a few pixels of drift is visible immediately.

## Possible improvements

- Responsive behavior (the sidebars should collapse well before desktop width)
- Interactive elements — the composer, reactions and comments are presentation only
- Accessibility: proper landmarks and alt text throughout
