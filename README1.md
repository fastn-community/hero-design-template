# Header Component

The **Header Component** is a UI element typically found at the top of a webpage
or application. It serves as a menu or navigation tool, allowing users to easily 
access different sections, pages, or features of the website or app.

With just a few lines of code, you can showcase site logo, site name and sitemap
details (sections and subsections).

## Preview

Here's an example of how the Header Component might look when rendered:

### Header

![header.png](.github/assets/header.png)



## Getting Started

To use the Business Card Component in your `fastn` package, follow these steps:

1. **Add the Header Dependency**: Open your `FASTN.ftd` file and add 
   the following line to include the Header component:
   ```ftd
   -- fastn.dependency: __user_name__.github.io/__repo_name__
   ```
2. **Use the Header Component**: In the file where you want to add 
   the header (e.g., `index.ftd`), you can import the component and 
   use it like this:
    ```ftd
   -- import: __user_name__.github.io/__repo_name__ as header

   -- header.header: My Site
   site-logo: $assets.files.images.ipsum-logo.svg
   site-url: /
   ```
   
## Customization

Feel free to customize the business card by adding, removing, or modifying 
fields.

## Fields

Feel free to reach out if you have any questions or need further assistance. Happy coding!
