# Tree View Git Status package

[![Version](https://img.shields.io/apm/v/tree-view-git-status.svg?style=flat-square)](https://atom.io/packages/tree-view-git-status)
[![Downloads](https://img.shields.io/apm/dm/tree-view-git-status.svg?style=flat-square)](https://atom.io/packages/tree-view-git-status)
[![Status Linux & OSX](https://img.shields.io/travis/subesokun/atom-tree-view-git-status.svg?style=flat-square&label=Linux%20%26%20OSX)](https://travis-ci.org/subesokun/atom-tree-view-git-status)
[![Status Windows](https://img.shields.io/appveyor/ci/subesokun/atom-tree-view-git-status.svg?style=flat-square&label=Windows)](https://ci.appveyor.com/project/subesokun/atom-tree-view-git-status)
[![Dependency Status](https://img.shields.io/david/subesokun/atom-tree-view-git-status.svg?style=flat-square)](https://david-dm.org/subesokun/atom-tree-view-git-status)

Show the Git repository status in the Atom tree-view.


### Screenshots

![Screenshot](https://github.com/subesokun/atom-tree-view-git-status/blob/master/screenshot.png?raw=true)

![Screenshot Settings](https://github.com/subesokun/atom-tree-view-git-status/blob/master/screenshot-settings.png?raw=true)

### Installation

```
apm install tree-view-git-status
```

### Features

* Show the Git branch name and commits ahead/behind labels for each project folder.
* Plays nice together with the Atom [project-view](https://github.com/subesokun/atom-project-view) package.
* Customizable styling of the Tree View Git status labels depending on the current active branch.

### CSS Branch Styling

![Screenshot CSS Branch Styling](https://github.com/subesokun/atom-tree-view-git-status/blob/master/screenshot-css-branch-styling.png?raw=true)

Via the user's custom Atom CSS stylesheet (Settings > Themes > "Edit Stylesheet") you can individually style the Tree View Git status labels as shown above. An example stylesheet can be found [here](https://gist.github.com/subesokun/04909f8ff45fbc28faad016559adc267).

### Git Flow support

This plugin sports Git Flow support if you've configured your repository to use
it (via `git flow init`). By default, Octicons are used to indicate the various
states of the flow process, but you can also choose to just show the branch
name in the correct color.

#### "Support" branches not supported

> It's an experimental feature that is currently being worked on. When you try
> using it you'll get warnings telling you not to use it in production.
> — [gitflow wiki][gitflow-wiki-faq]

As the support branch isn't officially supported, the plugin will not apply
any special treatment on support branches. Even with Git Flow enabled, a
support branch will be regarded as a regular branch.

### License

MIT

[gitflow-wiki-faq]: https://github.com/nvie/gitflow/wiki/FAQ
