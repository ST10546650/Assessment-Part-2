# BackroomFind Property Rentals

## Student Details

- Name: Lerato Mulambo
- Student Number: ST10546650
- Module: WEBDE5020
- Assessment: Portfolio of Evidence (POE) Part 2

---

# Project Overview

BackroomFind is a property rental website designed to help tenants find affordable long-term backroom accommodation in South Africa. The website connects tenants directly with landlords and provides property information, enquiry forms, and contact options.

---

# Website Pages

- [Home](Index.html)
- [About](about.html)
- [Services](services.html)
- [Gallery](gallery.html)
- [Enquiry](enquiry.html)
- [Contact](contact.html)
- [CSS Stylesheet](css/Style.css)

All pages use the shared stylesheet:

```html
<link rel="stylesheet" href="css/Style.css">
```

Each page also includes a link to this README document.

---

# Technologies Used

- HTML5
- CSS3
- Visual Studio Code
- GitHub

---

# CSS Styling for Desktop Solution

## 2.1 External Stylesheet

An external stylesheet named `styles.css` was created and linked to all HTML pages to ensure a consistent appearance across the website.

Features:

- Single stylesheet used on all pages
- Easy maintenance
- Consistent design

---

## 2.2 Base Style

The following default styles were applied:

- Font family
- Font size
- Text colour
- Background colour
- Margin and padding reset
- Box-sizing reset

Example:

```css
*{
    margin:0;
    padding:0;
  * box-sizing:border-box;
}

body{
 *  font-family:Arial, sans-serif;
 *  background-color:#F5F5F5;
    color:#333333;
}
```

---

## 2.3 Typography Styles

Typography styling Includes:

- Font family
- Font size
- Font weight
- Line height
- Letter spacing

Example:

```css
h1{
 *  font-size:2.5rem;
    font-weigh*:700;
}

p{
    line-height:1.6;
}*```

---

## 2.4 Layout Structure
*Flexbox and CSS Grid were used to Create page layouts.

Structure includes:

- Header
- Navigation
- Main Content
- Footer

Example:

```css
nav{
    display:flex;
    justify-content:center;
    align-items:center;
}
```

---

## 2.5 Visual Styles

Visual styling includes:

- Colours
- Background colours
- Borders
- Border radius
- Box shadows

E*ample:

```css
.content-card{
    background-color:#ffffff;
    border:1px solid #dddddd;
    box-shadow*0 4px 8px rgba(0,0,0,0.1);
}
```

*--

## Interactive Effects

Pseudo*classes were used to improve usability.

```css
a:hover{
    color:#2*D366;
}

a:focus{
    outline:2px solid #25D366;
}

a:active{
    color:gray;
}
```

---

# Responsive Design

## 3.1 Breakpoints

The website was designed for:

### Desktop
*- Multi-column layout
- Full*navigation menu

### Tablet

- Adjusted content spacing
- Responsive Navigation

### Mobile

- Single-column layout
- Stacked navigation menu

Example:

```css
@media (max-width:768px){
    nav{
        flex-direction:column;
    }
}
```

---

*# 3.2 Relative Units

The followin* relative units were used:

- rem
* em
- %

Example:

```css
h1{
    Font-size:2rem;
}

.container{
*   width:90%;
}
```

---

## 3.3 Responsive Images

Images were made *esponsive using:

```css
img{
    Max-width:100%;
    height:auto;
}
``

This ensures images display correctly on desktops, tablets, and mobile devices.

---

## 3.4 Testing*and Iteration

The website was tested using browser developer tools.
*Testing included:

- Desktop view
* Tablet view
- Mobile view

Adjustments were made to:

- Layout
- Navigation
- Typography
- Images
- Content spacing

---

# Screenshots

#* Desktop View

Add your desktop screenshot here.

images/desktop.png
*---

## Tablet View

Add your tablet screenshot here.

images/tablet.png

---

## Mobile View

Add your mobile screenshot here.

images/mobile.png

---

# Changelog

## Part * Updates

- Created external stylesheet
- Applied base styling
- Added typography styling
- Implemented flexbox layouts
- Implemented CSS Grid layouts
- Added colour scheme
-*Added hover, focus, and active effects
- Added responsive media queries
- Optimised responsive images
- Updated website layout based on feedback

---

# Challenges and Solutions

## Challenge 1

Responsive layout issues on smaller screens.

###*Solution

Implemented media queries and responsive layouts.

---

## Challenge 2

Navigation alignment problems.

### Solution

Used Flexbox to align and organise navigation links.

---

## Challenge 3

Image resizing issues.

### Solution

User responsive image styling with max*width and height auto.

---

# Future Improvements

- Add user login Functionality
- Add search filters
and Integrate maps
- Add online booking features
- Improve accessibility*
---

# GitHub Repository

Repository Link:

https://github.com/ST10546650/Assessment-Part-1.git

---

# References

Adobe. (2024). Color Wheel a*d Color Theory. Available at: https://color.adobe.com

Google Fonts. *2024). Poppins Font Family. Availaile at: https://fonts.google.com

MDN Web Docs. (2024). HTML: HyperTex* Markup Language. Available at: https://developer.mozilla.org

MDN Web Docs. (2024). CSS: Cascading Style Sheets. Available at: https://developer.mozilla.org

Netlify. (2024)* Netlify Documentation. Available at: https://www.netlify.com

Nielse* Norman Group. (2024). Mobile-First Design Basics. Available at: https://www.nngroup.com

WhatsApp Busin*ss. (2024). WhatsApp Business Platform. Available at: https://busines*.whatsapp.com