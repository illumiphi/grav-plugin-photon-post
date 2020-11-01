<a href="https://photon-platform.net/">
    <img src="https://photon-platform.net/user/images/photon-logo-banner.png" alt="photon" title="photon" align="right" height="120" />
</a>


# photon ✴ Post

## v0.1.0

---


> pages for posts and post collections

- [configuration](#configuration)
- [templates](#templates)
- [scaffolds](#scaffolds)
- [scss](#scss)
- [assets](#assets)
- [languages](#languages)

# configuration
blueprints.yaml

fields:
- enabled

Before configuring this plugin, you should copy the `user/plugins/photon-post/photon-post.yaml` to `user/config/plugins/photon-post.yaml` and only edit that copy.

Here is the default configuration and an explanation of available options:

```
enabled: true

```

Note that if you use the admin plugin, a file with your configuration, and named photon-post.yaml will be saved in the `user/config/plugins/` folder once the configuration is saved in the admin.


# blueprints

```sh
blueprints
└── post.yaml
```

### Post
post.yaml
extends: article
fields:
- header.post
  - .notes

# templates

```sh
templates
├── _articles
│   ├── _block
│   │   ├── post_header_excerpt.html.twig
│   │   └── post_header.html.twig
│   └── posts-showcase.html.twig
├── post.html.twig
└── posts.html.twig
```

# scaffolds

```sh
scaffolds
└── post.md
```

# scss

```sh
scss
├── articles
│   ├── _post.scss
│   └── _posts.scss
├── templates
│   ├── _post.scss
│   └── _posts.scss
└── post.scss
```

# assets

```sh
assets
├── post.css
├── post.css.map
└── post.js
```

# languages

```sh
languages
└── en.yaml
```


## Installation

- all photon plugins are installed as git submodules. More on that later.



## Configuration


## Usage

Select template type when creating a new page

## Credits


## To Do

- [ ] Future plans, if any


copyright &copy; 2020
