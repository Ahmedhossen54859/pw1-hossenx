
# My Learning Guide Website

**Author:** AH  
**Course:** Web Development Technologies  
**Project report:** ASSIGNMENT 1 PROJECT REPORT.pdf

---

## 1. About the Project

My Learning Guide is a website about the basics of HTML and CSS. I created this website to organise some basic web development topics in one place.

The website has four pages. The Home page introduces the website, the HTML Basics page explains HTML, the CSS Basics page explains CSS, and the Project Process page describes how the website was developed.

The website is mainly for students who are starting to learn web development.

## 2. Project Files

The project folder contains these files and folders:

```text
pw1-hossenx-new/
├── index.html
├── README.md
├── pages/
│   ├── html-basics.html
│   ├── css-basics.html
│   └── process.html
├── css/
│   └── styles.css
├── images/
│   ├── Box_model_CSS.png
│   ├── Box-model.webp
│   ├── Boxmodell-detail.webp
│   ├── CSS_BOX_MODEL.png
│   └── Css_box_model.webp
└── documents/
    └── ASSIGNMENT 1 PROJECT REPORT.pdf
```

The `index.html` file is the home page. The `pages` folder contains the other three pages. The `css` folder contains the stylesheet, and the `images` folder contains the pictures used on the website. The `documents` folder is for the project report.

## 3. Website Sitemap

The website has four main pages. Visitors can use the navigation menu to move between them.

```text
                 Home Page
                index.html
                     |
          +----------+----------+
          |          |          |
          v          v          v
      HTML Basics  CSS Basics  Project Process
      html-basics  css-basics  process.html
         .html       .html
```

All pages use the same CSS file, `css/styles.css`. The images are stored in the `images` folder.

## 4. How to Open the Website

To open the website on a computer:

1. Open the `pw1-hossenx-new` folder.
2. Find `index.html`.
3. Double-click the file to open it in a web browser.
4. Use the navigation menu to open the other pages.

The folders should stay in their original places because the HTML files use relative paths to find the CSS file and images.

## 5. HTML and CSS

### HTML Structure

I used HTML elements such as `header`, `nav`, `main`, `section`, and `footer` to organise the page content. These elements make the structure clearer and help separate different parts of the website.

### CSS Design

I used one external CSS file, `styles.css`, for all four pages. This helps keep the colours, fonts, spacing, and navigation consistent. CSS Grid is used to arrange the images in the gallery.

### Responsive Design

The CSS includes a media query for smaller screens. On narrow screens, the image gallery changes to one column and the navigation menu becomes vertical. This helps the website fit different screen sizes.

### Accessibility

The website uses meaningful navigation links, alternative text for images, and visible keyboard-focus styles. Form controls should also have suitable labels. These features help visitors understand and navigate the website.

## 6. Testing and Validation

I opened the website locally by opening `index.html` in a desktop web browser.

The following checks are important before submission:

- Open each of the four pages.
- Check that the navigation links and images work.
- Check the layout at 360 px, 768 px, and 1280 px.
- Test the website in two desktop browsers.
- Check the HTML using the [W3C HTML Validator](https://validator.w3.org/).
- Check the CSS using the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/).

The validation results and browser tests should be added after the checks are completed. I also need to make sure that the author and licence details for each image match its original source page.

## 7. Image Sources

I used five images related to the CSS box model. Their original source pages are listed below.

**Image 1: Box_model_CSS.png**

- Source: https://commons.wikimedia.org/wiki/File:Box_model_CSS.png
- Local file: `images/Box_model_CSS.png`
- Author and licence: Check the original source page before submission.

**Image 2: Box-model.webp**

- Source: https://commons.wikimedia.org/wiki/File:Box-model.svg
- Local file: `images/Box-model.webp`
- Author and licence: Check the original source page before submission.

**Image 3: Boxmodell-detail.webp**

- Source: https://commons.wikimedia.org/wiki/File:Boxmodell-detail.svg
- Local file: `images/Boxmodell-detail.webp`
- Author and licence: Check the original source page before submission.

**Image 4: CSS_BOX_MODEL.png**

- Source: https://commons.wikimedia.org/wiki/File:CSS_BOX_MODEL.png
- Local file: `images/CSS_BOX_MODEL.png`
- Author and licence: Check the original source page before submission.

**Image 5: Css_box_model.webp**

- Source: https://commons.wikimedia.org/wiki/File:Css_box_model.svg
- Local file: `images/Css_box_model.webp`
- Author and licence: Check the original source page before submission.

The original pages contain the image information and licence conditions. Any changes made to the images should also be recorded correctly.

## 8. AI Assistance
ChatGPT (OpenAI) was used as a supplementary learning and technical support tool during this project.  
It helped me understand HTML and CSS concepts, including semantic HTML, the CSS box model and responsive design.  
I used AI-generated examples to support my learning and adapted the implementation according to my understanding.  
ChatGPT also helped me identify possible errors in HTML structure, image paths and links.  
I reviewed the suggested corrections and used relevant feedback to improve my code.  
AI was used to review parts of the project against the assignment requirements and identify areas for improvement.  
I am responsible for the final implementation and will verify the code, image licences and actual testing results before submission.


## 9. Conclusion

This project helped me practise the basics of HTML and CSS. I learned how to organise a website into several pages, use one stylesheet for a consistent design, add images, and adjust the layout for smaller screens. Testing the website is also important for finding and correcting errors.


