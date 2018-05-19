# Responsive-Portfolio

## Overview Includes combining two Repos

> This project will be enhancing the `Basic-Portfolio` repo with a mobile-responsive layout.

## Instructions (No Bootstrap)

1. Copy the contents of `Basic-Portfolio` and paste the mentioned files into `Responsive-Portfolio`.

2. If applicable: Be sure not to include any _dot files (e.g. .git, .gitignore)_ from the `Basic-Portfolio` repo.

3. Inside your `Responsive-Portfolio` folder, find your `styles.css` file. 

> Write the media queries at the bottom of styles.css.
    
> Write the media queries at the bottom of styles.css.

4. Use `three @media screen tags`, each with one of these min-widths: `980px`, `768px` and `640px`.

* You use `980px` because you never want any of the content to be cut off. Since the desktop layout is about 960px wide, you want the media queries to kick in before your content gets cut off.

* `768px` is about the width of a tablet and `640px` is about the width of a phone in landscape.

* Make the layout match the following screenshots:

**index.html:**

![Image of `About Me` page](https://github.com/kyoukel/Responsive-Portfolio/blob/master/Portfolio_About.png)

**contact.html:**

![Image of `Contact` page](https://github.com/kyoukel/Responsive-Portfolio/blob/master/Portfolio_Contact.png)

**portfolio.html:**

![Image of `Portfolio` page](https://github.com/kyoukel/Responsive-Portfolio/blob/master/Portfolio_Gallery.png)

5. Make the position of the header static (the default positioning) when the screen is `640px` wide. The header design takes up a lot of room; you don't want it to stick to the top of a small screen and leave no room for the rest of your site.

6. Be sure to include the `viewport tag` in all your HTML files, otherwise your media-queries won't function as expected on mobile devices. (Hint: You won't need to use exact pixels for anything other than the container)

7.	**Protip:** Use the `Chrome extensions Window Resizer and Browser Width` to see the browser dimensions in Chrome.

8.	Deploy your new portfolio (now with media queries!) to GitHub Pages.

### BONUS
•	Incorporate CSS animations in your portfolio. More info: https://www.w3schools.com/css/css3_animations.asp


