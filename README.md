# markau-theme

This is the Hugo theme for [my personal Hugo blog](https://markau.dev). It's
pretty heavily tied to the specifics of my blog, so it's probably not perfectly
reusable out-of-the-box. But I like the idea of separating content from
presentation, so here is the theme.

It relies on `dart` for the scss. Currently I'm hosting my blog on Netlify, but
they don't seem to support building themes with `dart` yet, and I don't feel
like doing [GitHub Actions shenanigans](https://www.brycewray.com/posts/2022/05/using-dart-sass-hugo-github-actions-edition/),
so I'm just compiling it myself and including the final output in this repo.
