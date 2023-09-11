# Hero Template using `fastn`

This repository provides a prototype to create customizable business card 
design using the `fastn` language. You can create designs which can be used 
by users to easily create professional business card by filling in their 
information.


## Getting Started

To use this template, follow the steps below:

1. Click on `Use this Template` or go to the following [link](https://github.com/new?template_name=repo_name&template_owner=fastn-community)
2. Enter the required details to create new repository (**Note**: repository name should be in kebab case).
3. Clone this newly created repository to your local machine.
4. Open the `fastn` file named `index.ftd` in a text editor.

## Creating a new Business Card category

The `index.ftd` file contains placeholders that you can replace with your own information. Here's what you need to do:

### 1. Replace Package Information

In the section labeled "DOCUMENTATION FOR YOUR Hero COMPONENTS", locate the 
`docs.home component and check the following placeholders:

**Note:** All these are auto-filled values during repository creation

- `package-name`: Your repository name
- `package-full-name`: Your GitHub repository's full URL
- `license-url`: URL to the license of your choice (e.g., MIT License) (This 
  is currently commented, you can uncomment it if you want to include license.)
- `github`: Your GitHub Repository URL
- `created-by`: The creator name (This is an optional field. You can fill this information)

### 2. Implement Hero Components

In the "DEFINE YOUR Hero COMPONENTS" section, you will find placeholders for implementing the Hero components of your Hero.

For the `Hero` component, you need to use the following 
Heros (Hero details):

**Note:** These Heros will be used by the users for filling in their 
information. It's mandatory to use all these Heros while creating your 
component.


- `title`: your title 
- `subtitle`: your body
- `cta-primary-text`: your cta primary text
- `cta-primary-url`: your cta primary url
- `cta-secondary-text`: your cta secondary text
- `cta-secondary-url`: your cta secondary url
- `image`: your image

Replace the code present in component definition of 
`stack`: A custom web component or section in web development designed to create visually striking and attention-grabbing content layouts.
`left-stack`:a web layout design where a prominent hero section with key content is positioned to the left, typically stacked alongside other content or sections on the webpage.
`right-stack`:a web layout design where content or sections are stacked vertically on the right side of the screen.
`heading-left`:A specific variation of a hero section or component where the main heading or text content is aligned to the left side of the screen.
`heading-right`:A specific variation of a hero section or component where the main heading or text content is aligned to the right side of the screen.
`heading-center`:A specific variation of a hero section or component where the main heading or text content is aligned to the center side of the screen.
`without-image`:A specific variation of a hero section or component where the without image
component.
with actual component implementation/definition.

**Note:** It is **recommended** to create a `component/index.ftd`  files for
implementing components respectively.

Also, `assets` for your package is auto-imported, you can use `assets` to 
add image etc. (Checkout `FASTN.ftd` file).

## Fix the README.md content

Replace the preview image with your template image in [`.github/assets/Hero.png`](.github/assets/Hero.png)


## Publishing your category design on Github page:

Check out [Publishing Static Site On github 
pages](https://fastn.com/github-pages/) to know more. 

Also add the live site link in **About** section of github repository.


## Some other information:

The sitemap present in `FASTN.ftd` is used to organise your package. 
This uses 

- `index.ftd`: It is the homepage which shows preview of  
  your Hero


The documentation for this template comes from [`hero-doc`](fastn-community.github.io/hero-doc)


*To know more about `fastn`, visit [`fastn` website](https://fastn.com/). Also 
you can join our [discord](https://fastn.com/discord/) channel to connect 
with our team for further guidance.*
