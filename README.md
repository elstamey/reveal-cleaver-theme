reveal-cleaver-theme
================

[Reveal.js](https://github.com/hakimel/reveal.js/) theme for [cleaver](https://github.com/jdan/cleaver). Take the best of both worlds!

Small demo (sorry for image quality, will work on it) using [cleaver-template](https://github.com/sudodoki/cleaver-template)
![Sample usage](https://github.com/sudodoki/reveal-cleaver-theme/raw/image/sample.gif)


How to use this?
================
Drop this line in your metadata (first paragraph in your presentation)  
`theme: elstamey/reveal-cleaver-theme`

Have any question/proposals?
============================
Don't hesitate to open issue, or just to do regular fork-feature branch-pull request thing on me. Source is in [source branch](https://github.com/sudodoki/reveal-cleaver-theme/tree/source).
After modifying files in `*_source` folder need to run

```shell
cat css_source/reveal_base.css css_source/fonts_inlined.css css_source/league_theme.css  css_source/hljs.css css_source/extra.css > style.css
cat js_source/reveal.min.js js_source/reveal-init.js > script.js
```
