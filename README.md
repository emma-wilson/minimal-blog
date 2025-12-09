# Minimal blog website template

A Jekyll website template inspired by the [minimal light](https://github.com/yaoyao-liu/minimal-light) theme by [yaoyao-liu](https://github.com/yaoyao-liu).

## Features

- Minimal personal / academic website template
- Jekyll website that can be automatically deployed using GitHub Pages
- Desktop and mobile friendly
- Designed for sharing publications and resources
- Built-in blog

## Directory structure

```
.
├── _data/
|    └── nagivation.yml                 # File for adding pages to navigation menu
|    └── publications.yml               # File for adding publications
|    └── resources.yml                  # File for adding resources
├── _includes/
|    └── blog.html                      # HTML layout for list of blog posts (how posts added to _posts/ will be displayed on blogs page)
|    └── navigation.html                # HTML layout for navigation menu (how items added to _data/navigation.yml will be displayed)
|    └── publications.html              # HTML layout for publications (how items added to _data/publications.yml will be displayed)
|    └── resources.html                 # HTML layout for resources (how items added to _data/resources.yml will be displayed)
├── _layouts/
|    └── default.html                   # HTML layout for default pages
|    └── post.html                      # HTML layout for blog posts
├── _posts/
|    └── 2025-12-08-my-first-blog.md    # Example blog post
├── _site/                              # Folder created by Jekyll
├── .jekyll-cache                       # File created by Jekyll
├── assets
|    └── css
|        └── styles.css                 # CSS stylesheet
|    └── images
|        └── profile.png                # Profile picture
├── config.yml                          # The Jekyll site configuration file
├── blog.md                             # Add content to the Blog page
├── Gemfile                             # Gemfile required by Ruby
├── Gemfile.lock                        # File created by Jekyll
├── index.md                            # Add content to the Home page
├── LICENSE                             # Repository license
├── README.md                           # This file
├── research.md                         # Add content to the Research page
└── resources.md                        # Add content to the Resources page
```

## Using this template

To build your own website using this template:

### Step 1: Fork this repository

Fork this repository and change the name to `your-username.github.io`. This will also be the URL of your new website.

### Step 2: Customise your website

First, customise the information in the `_config.yml` file. To change the profile picture, replace the image file in `assets/img`.

Then, you can edit the site content in the Markdown files, e.g, `index.md`, and add publications and resources using the `publications.yml` and `resources.yml` files in the `_data` folder.

### Step 3: Add blog posts

Create and edit blog posts in the `_posts` folder.

### Step 4: Additional customisation

You can edit the HTML and CSS files in this repository to edit other parts of your website. For instance, in `assets/css/styles.css` you can edit `--primary-color` and `--secondary-color` variables to change the website colours.

### Step 5 Deploy on GitHub Pages

Your repository will need to be public for you to deploy your website using GitHub pages. In your GitHub repository settings, navigate to the `Pages` tab nder `Code and automation`. On that page, under the heading `Build and deployment` and subheading `Branch`, select `main` and then hit save. It may take up to 10 minutes for your website to deploy each time you make a change.

## Additional resources

- [GitHub Pages documentation](https://docs.github.com/en/pages)
- [Jekyll Step by Step Tutorial](https://jekyllrb.com/docs/step-by-step/01-setup/) - useful if you want to work with your website locally