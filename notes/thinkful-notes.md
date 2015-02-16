#Thinkful Notes

### Goal

[Matisse](http://www.moma.org/interactives/exhibitions/2014/)
Joe Ledbetter

### HTML & CSS

#### Positioning
- 1200x800 for header or any starting size

######Center
1. text-align: center 
2. Set the width of an element and declaring margin-left: auto;, margin-right:auto;
1. inline 2. block elements

#####Approach
As far as building a webpage from scratch is concerned, I find it easiest to start simple and build it up piece by piece. That usually makes it easier to create clear and concise code. So, you could:
1. Create a new index.html file.
2. Add the HTML meta-tags.
3. Make each major HTML element (i.e. nav, divs, footer, etc)
4. Make the smaller HTML elements (i.e. h1-h6, p, etc)
5. Create a new style.css file
6. Add the CSS cross-browser boilerplate.
7. Write the CSS to style the major HTML elements.
8. Write the CSS to style the smaller HTML elements.

#### Semantic HTML
- Use "classes" to link specific HTML elements to CSS selectors
- Use "classes" to link specific HTML elements to CSS selectors.
- Stack several CSS classes into one selector so they all have the same styles.
- Name elements by their function (not what they do)
- Target certain tags within a class by using the class > element selector, i.e. .social > li to target all of the list items within the ".social" class.
- Use disply: inline-block; to have all the items within a list display in a single horizontal line.
- Use "em" instead of any fixed measurements (pt, inches, etc.)
- Although relative, 1 em is usually equivelant to 16pt font size
- Each block level element has 3 levels of space around it -- 1) padding, 2) border, and 3) margin.
- Make block elements bigger by adding padding to move the border out. (The text won't get bigger, but the border around the text will grow.)
- Adjust margins to push other elements away from your element. Margins keep the border the same but add additional space.

#### Misc Notes


### CSS 
- A class is a group of elements that are the same or similar. (group of people)
- An ID is a singular identifier of ONE html tag. (one persons needs special drink)

```
.paragraph-class {
  color:purple;
}
#paragraph-id {
color: blue;
}
```

#### Responsive Design
- % widths in css
 - consider the content users need
-  a simple single-column layout on phones to more complex, grid-based layouts on tablets and desktops
-  creating media queries at common device sizes—320, 480, 768, 1024, and 1280—but these conventions are outdated with modern smartphones

git pull "url" 
git push https://github.com/slang800/chazsouthard.com

git pull https://github.com/slang800/chazsouthard.com

###Resources
- [Shay Howe's Advanced HTML & CSS](http://learn.shayhowe.com/)
- [Emmet cheat sheet](http://docs.emmet.io/cheat-sheet/)
- [The Git Book](http://git-scm.com/book/en/v2)
- [CSS box-sizing](http://css-tricks.com/box-sizing/)
- [Font Smoothing](http://maxvoltar.com/archive/-webkit-font-smoothing)
- [CSS Vocabulary](http://apps.workflower.fi/vocabs/css/en)
- [CSS transitions](http://css-tricks.com/almanac/properties/t/transition/)
- [CSS keyframes](http://css-tricks.com/almanac/properties/a/animation/)
- [Git Remotes.. also covered in The Git Book](http://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging)
- [Thinkful Github Pages Guide](http://www.thinkful.com/learn/a-guide-to-using-github-pages/)
- [HTML character codes](http://www.ascii.cl/htmlcodes.htm)
- [Branching & Merging](http://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging) 

