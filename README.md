## About

The Cambridge University Astronomical Society website.

This is based off of the [Astro JavaScript web framework](https://astro.build).


## Important files and directories

```text
public/
src/
├── assets/
├── components/
├── layouts/
└── pages/
astro.config.mjs
```

Directories:

- public: where files are stored that are not modified and are served as is.
- assets: where files are passed to the builder to be used (e.g. css).
- components: parts of a page, e.g. the nav-bar or the footer.
- layouts: think of these as types of pages that are reusable, like a home page, info pages, blog posts, or magazine pages.
- pages: these are the pages that get passed to the builder to be converted to the website pages, using the above files as required.

## Running and developing

Every time there is a change to the main branch, the page gets published. As such, **only finalised changes should be pushed to the main branch**. Any test changes should be pushed to their [own branch](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches).

To run this locally to test, you should make sure [node.js is installed](https://nodejs.org/en/download), and then (within the base of this repository) run `npm install`. That should install all the required packages allowing you to then run `npm run dev` which will serve a local instance at [localhost:4321](http://localhost:4321) which updates with saved changes in root directory. 
