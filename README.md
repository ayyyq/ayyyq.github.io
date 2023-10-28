Thanks for the Github Pages template for academic websites from [academicpages/academicpages.github.io](https://github.com/academicpages/academicpages.github.io) and [jxhe/jxhe.github.io](https://github.com/jxhe/jxhe.github.io).

[//]: # (A Github Pages template for academic websites. This was forked &#40;then detached&#41; by [Stuart Geiger]&#40;https://github.com/staeiou&#41; from the [Minimal Mistakes Jekyll Theme]&#40;https://mmistakes.github.io/minimal-mistakes/&#41;, which is © 2016 Michael Rose and released under the MIT License. See LICENSE.md.)

[//]: # ()
[//]: # (I think I've got things running smoothly and fixed some major bugs, but feel free to file issues or make pull requests if you want to improve the generic template / theme.)

[//]: # ()
[//]: # (### Note: if you are using this repo and now get a notification about a security vulnerability, delete the Gemfile.lock file. )

[//]: # (# Instructions)

[//]: # ()
[//]: # (1. Register a GitHub account if you don't have one and confirm your e-mail &#40;required!&#41;)

[//]: # (1. Fork [this repository]&#40;https://github.com/academicpages/academicpages.github.io&#41; by clicking the "fork" button in the top right. )

[//]: # (1. Go to the repository's settings &#40;rightmost item in the tabs that start with "Code", should be below "Unwatch"&#41;. Rename the repository "[your GitHub username].github.io", which will also be your website's URL.)

[//]: # (1. Set site-wide configuration and create content & metadata &#40;see below -- also see [this set of diffs]&#40;http://archive.is/3TPas&#41; showing what files were changed to set up [an example site]&#40;https://getorg-testacct.github.io&#41; for a user with the username "getorg-testacct"&#41;)

[//]: # (1. Upload any files &#40;like PDFs, .zip files, etc.&#41; to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  )

[//]: # (1. Check status by going to the repository settings, in the "GitHub pages" section)

[//]: # (1. &#40;Optional&#41; Use the Jupyter notebooks or python scripts in the `markdown_generator` folder to generate markdown files for publications and talks from a TSV file.)

[//]: # ()
[//]: # (See more info at https://academicpages.github.io/)

[//]: # ()
[//]: # (## To run locally &#40;not on GitHub Pages, to serve on your own computer&#41;)

[//]: # ()
[//]: # (1. Clone the repository and made updates as detailed above)

[//]: # (1. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`)

[//]: # (1. Run `bundle clean` to clean up the directory &#40;no need to run `--force`&#41;)

[//]: # (1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.)

[//]: # (1. Run `bundle exec jekyll liveserve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.)

[//]: # ()
[//]: # (# Changelog -- bugfixes and enhancements)

[//]: # ()
[//]: # (There is one logistical issue with a ready-to-fork template theme like academic pages that makes it a little tricky to get bug fixes and updates to the core theme. If you fork this repository, customize it, then pull again, you'll probably get merge conflicts. If you want to save your various .yml configuration files and markdown files, you can delete the repository and fork it again. Or you can manually patch. )

[//]: # ()
[//]: # (To support this, all changes to the underlying code appear as a closed issue with the tag 'code change' -- get the list [here]&#40;https://github.com/academicpages/academicpages.github.io/issues?q=is%3Aclosed%20is%3Aissue%20label%3A%22code%20change%22%20&#41;. Each issue thread includes a comment linking to the single commit or a diff across multiple commits, so those with forked repositories can easily identify what they need to patch.)
