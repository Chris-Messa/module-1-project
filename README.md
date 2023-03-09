# SEO accessibility project

##  Description

- This project was designed with the goal of learning web accessibility practices for enhancing the user experience as well as search engine optimization
- Accessebility on the web has grown more and more important over the history of content on the web. As a full-stack web development student, learning how to implement these best practices is one of the most important things to do. 

## What i've learned

- The given starter code for this project presented a functioning site using HTML and CSS. However, many aspects of the code were in need of proper refactoring to create a more accessible application
- The first step was ensuring the HTML structure made logical sense. For example, ensuring that there was only one `<h1>` element present
- The initial html for this project contained many `<div>` elements. Solely relying on `<div>` for content does work, but it causes a lot of issues for screen readers. To solve this issue, I changed innapropriate `<div>` tags to more semantic tags, such as `<header>` for the header of the page and `<nav>` for the navigation bar
- Initially, the `<title>` of this web page simply read "website". This is not a descriptive title, and so a more appropriate title was given. The new title reflects the main idea of the web page, and includes the SEO keyword. These changes make the web page easier to understand both from the user perspective and from the perspective of a search engine. 
- The images on the page contained no alt text. This means that when a user using a screen reading device comes across the image, there is no way for them to understand what the image is. Appropriate and descriptive alt text was added to solve this issue
- Redundant class names were reduced, and the overall amount of CSS code was dramatically decreased. Once certain elements were changed to more semantic tags, certain css classes became redundant. For example, the "footer" element had a "footer" class. Because the footer class applied to the element that contained the entire footer, it could be removed without affecting the footer style. 
- Finally, appropriate comments were added to both the HTML and CSS files.  

## Screenshots
<figure>
  
  ![An image of the deployed project](https://user-images.githubusercontent.com/39140839/224185109-f6674c60-4ef5-41a7-ba5c-1b1ea052fab7.jpg)
  <figcaption align="center">Fig. 1 Example screenshot of working website</figcaption>
  
</figure>

<figure>
  
![Example screenshot of CSS comments](https://user-images.githubusercontent.com/39140839/224185091-432ff778-cf1d-4422-a288-01e50f9ff36d.jpg)
  
  <figcaption align="center">Fig. 2 Screenshot showing an example of the comments added to the stylesheet</figcaption>
  
</figure>
