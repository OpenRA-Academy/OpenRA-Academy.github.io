# OpenRA Academy 🎓

Welcome to the OpenRA Academy repository. This is a community-driven guide to step up
your gameplay in [OpenRA](https://github.com/OpenRA/OpenRA).

You can reach the Academy at
[openra-academy.github.io](https://openra-academy.github.io).

We have a
[Discord channel](https://discord.com/channels/697855337457516615/697863837952770109)
where you can interact with the community.

## Contribute ✏️

You can contribute by submitting pull requests to the repository. Once approved, the
new content will be automatically deployed to our website.

We use the static website generator [Jekyll](https://jekyllrb.com), and most of our
pages are written in [Markdown](https://guides.github.com/features/mastering-markdown)
(here is a
[Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)).

We use [GitHub Pages](https://pages.github.com) to host the website and automatize 
deployments when a new pull request is merged. Currently, the (temporary) theme is
[Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes). You can get more
information about it in the
[Minimal Mistakes Documentation](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/)

The GitHub interface allows for in-browser modifications. That works well for
minor contributions, but you may want to download a local copy of the repository for extensive contributions.

__Tip__: We suggest to use the free source-code editor
[Visual Studio Code](https://code.visualstudio.com), or its open source counterpart
[VSCodium](https://vscodium.com), to simplify editing and previewing the files
on the fly.

## Run the code 👨‍💻

To run the code locally, you need to
[install Jekyll](https://jekyllrb.com/docs/installation), then download all
the required dependencies by running:
```bash
bundle update
```
You can now start serving the static pages with the following command:
```bash
bundle exec jekyll serve
```
The command should print the local URL to access the website. Usually, that is
[http://127.0.0.1:4000](http://127.0.0.1:4000)
