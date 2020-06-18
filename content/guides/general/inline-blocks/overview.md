---
title: 'Overview'
---

This guide will show you how to set up inline editing and inline blocks based on a simple [create-react-app](https://reactjs.org/docs/create-a-new-react-app.html) demo. The steps will be associated with tagged commits on this [demo repo](https://github.com/tinacms/inline-blocks-demo) for reference.

By the end of this guide, you should have a good understanding of how to set-up and work with inline editing and inline blocks. While this guide doesn't cover every single field or potential usecase, it should give you enough of a base to create Inline Editing experiences in your own projects.

<iframe width="100%" height="398" src="https://www.youtube.com/embed/4qGz0cP_DSA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

The video above gives some reference as to what inline blocks look like in Tina. The demo we are going to set up will be more simple than what is shown in the video, but it should give you some inspiration around what's possible!

## Set-up the demo repo

To get started, you'll need to clone [the repo](https://github.com/tinacms/inline-blocks-demo), install the dependencies & checkout the [**step 1 tag**](). At this point, the demo is set up with a TinaCMS instance and renders a simple `Hero` component with hard-coded data.

<!-- TODO: fill these in -->

```bash
git clone git@github.com:tinacms/inline-blocks-demo.git
cd inline-editing-demo
git checkout --some-tag...
yarn install
yarn start # Navigate to localhost:3000
```

![Inline Editing demo at install](/img/inline-editing-guide/step1-install.png)

Note that the _demo isn't meant to be a 'starter'_. It is for educational purposes to help you get familiar with the inline editing API.

// _FOR REVIEWERS_: for now, just branch off of master in the [demo](https://github.com/tinacms/inline-blocks-demo) until we have it properly configured. The `runthrhough-1` (messed up the spelling lol) branch has the final state if you need to reference.

### [‍👋 Checkout Step 1]()

> This [commit]() is your starting place for working through this demo. Skip to the [final version of the repo]() if you get stuck or need a reference at any point.