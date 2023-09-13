# Hero Template using `fastn`

This repository provides a prototype to create customizable business card 
design using the `fastn` language. You can create designs which can be used 
by users to easily create professional business card by filling in their 
information.

## Getting Started

To use this template, follow the steps below:

1. Click on `Use this Template` or go to the following [link](https://github.com/new?template_name=hero-design-template&template_owner=fastn-community)
2. Enter the required details to create new repository (**Note**: repository name should be in kebab case).
3. Clone this newly created repository to your local machine.
4. Open the `fastn` file named `index.ftd` in a text editor.

## Creating a new Hero category

The `index.ftd` file contains placeholders that you can replace with your own information. Here's what you need to do:

### 1. Replace Package Information

In the section labeled "DOCUMENTATION FOR YOUR HERO COMPONENTS", locate the 
`docs.home component and check the following placeholders:

**Note:** All these are auto-filled values during repository creation

- `package-name`: Your repository name
- `package-full-name`: Your GitHub repository's full URL
- `license-url`: URL to the license of your choice (e.g., MIT License) (This 
  is currently commented, you can uncomment it if you want to include license.)
- `github`: Your GitHub Repository URL
- `created-by`: The creator name (This is an optional field. You can fill this information)

### 2. Implement Hero Components

In the "DEFINE YOUR HERO COMPONENTS" section, you will find placeholders for 
implementing the Hero components of your Hero.

For the `Hero` component, you need to use the following properties (Hero 
details):

**Note:** These properties will be used by the users for filling in their 
information. It's mandatory to use all these properties while creating your 
component.

#### Hero stack

A Hero stack component typically arrange its elements in stack form, i.e. 
one after other. *The name of component is `stack`.*

#### Hero Left stack

A Hero left stack component typically positioned its elements to the left in 
stack form. *The name of component is `left-stack`.*

#### Hero Heading Left

A Hero Heading Left component aligns its the main heading or text content  
to the left side of the screen. *The name of component is `heading-left`.*

#### Hero Heading Right

A Hero Heading Right component aligns its the main heading or text content  
to the right side of the screen. *The name of component is `heading-right`.*

#### Hero Heading Center

A Hero Heading Right component aligns its the main heading or text content  
to the center side of the screen. *The name of component is `heading-center`.*


The following properties are available for `Hero Left stack`, `Hero Heading 
Left`, `Hero Heading Right` and `Hero Heading Center` components:

- `title`: your title 
- `subtitle`: your body
- `cta-primary-text`: your cta primary text
- `cta-primary-url`: your cta primary url
- `cta-secondary-text`: your cta secondary text
- `cta-secondary-url`: your cta secondary url
- `image`: your image


#### Hero Without Image

A Hero Without Image component does not have image element. *The name of 
component is `without-image`.*

The following properties are available:

- `title`: your title
- `subtitle`: your body
- `cta-primary-text`: your cta primary text
- `cta-primary-url`: your cta primary url
- `cta-secondary-text`: your cta secondary text
- `cta-secondary-url`: your cta secondary url


**Note:** It is **recommended** to create a `components/stack.ftd`,  
`components/left-stack.ftd`, `components/heading-left.ftd`,   
`components/heading-right.ftd`, `components/heading-center.ftd` and
`components/without-image.ftd` files for implementing components respectively.

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
