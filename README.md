# Neat

## Description
This is a fork of Ghost Ease theme with many new features (hierarchical model and dark mode). Its focus is clean and functional design and fully customizable structure. 

The theme is compatible with the latest Ghost 5. For more details see the features section below.

![](https://raw.githubusercontent.com/mycodeblossom/resources/master/Neat/home_light_theme.png)
![](https://raw.githubusercontent.com/mycodeblossom/resources/master/Neat/home_dark_theme.png)

## Neat is good for

You can use the theme Neat for ghost for: 
* tech blog
* documentation
* blogs which need hierarchical organization

All features are developed and production ready

## Demo
Visit the demo sites:
 * https://datascientyst.com/
 * https://softhints.com/

     
## Features

* Dark mode
* Hierarchical structure for home page and left side navigation. For more information check hierarchical_structure.md.
![](https://github.com/mycodeblossom/resources/blob/master/Neat/drop_down_menu.png?raw=true)
* Featured posts flagged with custom icon 
![](https://raw.githubusercontent.com/mycodeblossom/resources/master/Neat/featured_posts.png)
* JQuery free :)
* 3 column layout for posts:
    * navigation for categories and sub-categories
    * post content
    * TOC generated using the heading of the post (2 levels managed)
![](https://github.com/mycodeblossom/resources/blob/master/Neat/post.png?raw=true)
* custom not found page (404)
![](https://github.com/mycodeblossom/resources/blob/master/Neat/not_found_page.png?raw=true)
* Code highlighting using prismJs
* custom color palette to use in post (so it looks good in dark and light mode)
* Generic Elements (check post_elements.md):
    * info boxes
    * tables
    * collapsible
    
Check more in: How to configure Neat

## Install Neat

1. [Download this theme](https://github.com/mycodeblossom/Neat/archive/refs/heads/main.zip)
2. Log into Ghost, and go to the `Design` settings area to upload the zip file

## How to customize Neat

 Please visit: How to configure Neat
## Support

If you have any questions or issues with the Neat theme, please refer to the theme repository for support or create an issue on the repository's issue tracker.
Want to contribute?

New features, ideas, suggestions and pull requests are welcome!

# Development

Styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
yarn

# Run build & watch for changes
yarn dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/ease.zip`, which you can then upload to your site.

```bash
yarn zip
```

# Copyright & License

Copyright (c) 2013-2023 Ghost Foundation - Released under the [MIT license](LICENSE).
