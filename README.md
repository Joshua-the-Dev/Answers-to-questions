1. What is the Box model in CSS?
Which CSS properties are a part of it?
Answer:
In web development, the CSS box model refers to how HTML elements are modeled in browser engines and how the dimensions of those HTML elements are derived from CSS properties. It is a fundamental concept for the composition of HTML webpages.
It consists of: margins, borders, padding and the actual content.
It has properties such as: line-height, color, letter-spacing, text-align and much more.

2. What are the advantages of using CSS?
Answer:
CSS has many advantages that enable developers to design a website. Some of these advantages are:
* Better Website Speed
For a website to function efficiently, it should have a faster load time. In modern times, people usually wait for just a couple of seconds for a website to load. So, it’s important to ensure faster speed. For companies wanting to ensure a faster and smooth website experience, CSS becomes paramount to their success.
* Easier to Maintain
CSS is easy to maintain due to less maintenance time. This is because a single line code change affects the entire web page. Also, if improvements are required, then less effort is required to affect changes in the webpage code.
* Consistent Design
You would have seen many websites that are elegant and user-friendly. One thing common to all these websites is consistency in design. CSS enables developers to ensure the style elements are applied consistently across several web pages.
* Time-Saving
Due to faster speed and easier maintenance, CSS saves a lot of time and effort in the web development process due to faster loading time. Here, lesser time ensures designer efficiency.
* Better Device Compatibility
People use different smart devices to view a particular website. It can be a smartphone, PC or laptop. For this purpose, websites are required to be device compatible. CSS ensures the task is done smoothly by providing better compatibility. 
* Positioning of Design Elements
You can change the position of an HTML tag with the help of CSS. You can place the elements like an image on any part of the webpage as and when required.

3. What are the limitations of CSS?
Answer:
CSS stands for Cascading Style Sheets, it is a language used for styling HTML elements.
It has many limitations as a programming language, some of them are as bellows:
* It cannot perform any logical operations like if/else, for/while, +/-, etc.
*  You cannot read your files using CSS.
*  Unable to interact with databases.
*  CSS can’t request a web page.
*  Ascending by selectors is not possible.
*  Limitations of vertical control.
*  No expressions.
*  No column declaration.
*  Pseudo-class not controlled by dynamic behavior.
*  Rules, styles, targeting specific text not possible.
Although using CSS3, you can now add animations to your HTML elements

4. How to include CSS in the webpage?
Answer:
CSS can be added to HTML documents in 3 ways:
* Inline - by using the style attribute inside HTML elements
* Internal - by using a <style> element in the <head>section
* External - by using a <link>element to link to an external CSS file
The most common way to add CSS, is to keep the styles in external CSS files.

5. What are the different types of Selectors in CSS?
Answer:
CSS selectors are used to "find" (or select) the HTML elements you want to style.
We can divide CSS selectors into five categories:
* Simple selectors (select elements based on name, id, class)
* Combinator selectors (select elements based on a specific relationship between them)
* Pseudo-class selectors (select elements based on a certain state)
* Pseudo-elements selectors (select and style a part of an element)
* Attribute selectors (select elements based on an attribute or attribute value)

6. What is a CSS Preprocessor? What are Sass, Less, and Stylus? Why do people use them?
Answer:
A CSS preprocessor is a program that lets you generate CSS from the preprocessor's own unique syntax.
There are many CSS preprocessors to choose from, however most CSS preprocessors will add some features that don't exist in pure CSS, such as mixin, nesting selector, inheritance selector, and so on. These features make the CSS structure more readable and easier to maintain.
LESS
LESS (which stands for Leaner Style Sheets) is a backward-compatible language extension for CSS. LESS follows a declarative styling pattern by nature. This implies that you specify what you want to see not how you want it to be done. This is mostly as a result of its similarities to functional programming which mostly makes it more readable and easier to understand. 
However, this also introduces some difficulty when implementing complex algorithm patterns. As the name implies, LESS is designed to enhance CSS in the leanest way possible with minimal extra features. These features are designed to intuitively follow regular CSS conventions, principles, and paradigms. 
The official LESS documentation quotes “because LESS looks just like CSS, learning it is a breeze.”
SASS
SASS, which stands for Syntactically Awesome Style Sheets. It is equally designed to be compatible with all versions of CSS. It follows an imperative styling pattern which implies that you get to specify how things get done. 
SASS has a wider range of functionalities and features that enable developers to do amazing things and implement very complex algorithms with lesser difficulty. However, this comes at the expense of maintaining a CSS-like look all-round. 
At some point, it tends to feel a lot more like a programming language than a styling language and this makes it more difficult for people (e.g designers) without a programming background to quickly get up to speed with.
STYLUS
Stylus offers a bit more expressiveness while maintaining a much more concise syntax. People with Python backgrounds will very much resonate with its non-curly braced syntax of indentation. However, this is a purely optional feature and one could still stick to the regular CSS syntax. 
It shares striking similarities with LESS, but it has an imperative syntax like SASS. Stylus thrives over SASS and LESS in its support of seamless mixins.

7. What is VH/VW (viewport height/viewport width) in CSS?
VH stands for viewport height and VW is for viewport width. Hence, setting an element to a width value of 50vw means that the element will have a width that’s 50% of the viewport size, and this stays true when the viewport is resized.

8. Difference between reset vs normalize CSS?. How do they differ?
Answer:
Reset CSS: CSS resets aim to remove all built-in browser styling. For example margins, paddings, font-sizes of all elements are reset to be the same. 
Normalize CSS: Normalize CSS aims to make built-in browser styling consistent across browsers. It also corrects bugs for common browser dependencies.

9. What is the difference between inline, inline-block, and block?
Answer:
* An inline element has no line break before or after it, and it tolerates HTML elements next to it.

* A block element has some whitespace above and below it and does not tolerate any HTML elements next to it.

* An inline-block element is placed as an inline element (on the same line as adjacent content), but it behaves as a block element.

10. Is it important to test the webpage in different browsers?
Answer:
Websites are created to run or to be seen in the browsers. They are created to have a good interaction between a developer and a client or a developer to its readers. That’s why in order to gain trust in our clients or to our target market, we should be sure of its consistency and accuracy. Because if one problem occurs to our website, we cannot explain ourselves to all of the people viewing the website real time. And if they encountered an error while reviewing our work, they will just lose their focus on the website at all.
It is very important to check your website in multiple web browsers from an external source. Have you ever noticed that your website looks different on someone else’s computer from outside of your office? Your website might look just fine in Chrome; however, it may look disastrous in Internet Explorer and vice-versa. You have no control over which browser your visitor chooses to use when visiting your website.
The different ways each web browser interprets CSS, HTML, XHTML, and browser plug-ins causes the differences in page display. The browser is a mini operating system that is doing multiple tasks. Browsers offer many new ways of navigating and visualizing your website and the web. The more we ask browsers to do on your website, the slower they become. It is critical in today’s competitive and increasingly global Internet world to know your website’s load times and how your website looks on different types of browsers.

11. What are Pseudo elements and Pseudo classes?
Answer:
Basically a pseudo-class is a selector that assists in the selection of something that cannot be expressed by a simple selector e.g :hover . A pseudo-element however allows us to create items that do not normally exist in the document tree e.g ::after .

12. How do you specify units in the CSS?. What are the different ways to do it?
Answer:
There are different ways to specify units in CSS like px, em, pt, percentage (%). px(Pixel) gives fine-grained control and maintains alignment because 1 px or multiple of 1 px is guaranteed to look sharp. px is not cascade. em maintains relative size. you can have responsive fonts. Em, will cascade 1em is equal to the current font-size of the element or the browser default. If u sent font-size to 16px then 1em = 16px. The common practice is to set default body font-size to 62.5% (equal to 10px).
pt(point) are traditionally used in print. 1pt = 1/72 inch and it is a fixed-size unit.
%(percentage) sets font-size relative to the font size of the body. Hence, you have to set the font-size of the body to a reasonable size.

13. Does margin-top or margin-bottom have an effect on inline elements?
Answer:
No, it doesn’t affect the inline elements. Inline elements flow with the contents of the page.

14. What property is used for changing the font face?
Answer:
The font-family property is used to change the face of a font. The font-style property is used to make a font italic or oblique. The font-variant property is used to create a small-caps effect.

15. What are the differences between adaptive design and responsive design?
Answer:
Responsive Design:
In this design web designers design the user interface of a website in such a manner that whatever device you are using you can access comfortably web page. if we use a web page on the laptop then it splits in large view but if you use the same web page on mobile then it synchronizes itself. web designers simply design it by using only HTML & CSS. designer works with the developer for a better user experience.
Adaptive Design:
In this design web designers design the user interface of a website in such a manner that it creates different layouts of the web page for the different devices. so based on the screen size of the device it loads that layout of the page. it creates the different layouts for different devices like screen size as for 320px, 480px, 760px, 960px, 1200px, 1600px. for different sizes of mobile screens, tablet screens, and many more devices it depicts the size of layouts of the screen and displays the content of the page. web designers have to work more because they have to develop six different pages.

16. How are the CSS selectors matched against the elements by the browser?
Answer:
Browsers read your CSS selectors from right to left. That means that in the selector ul > li a[title=”home”] the first thing thing interpreted is a[title=”home”]. This first part is also referred to as the “key selector” in that ultimately, it is the element being selected.
#main-nav > li { }
If you start by just matching the rightmost part of the selector against your element, then chances are it won’t match and you’re done. If it does match, you have to do more work, but only proportional to your tree depth, which is not that big in most cases.
On the other hand, if you start by matching the leftmost part of the selector… what do you match it against? You have to start walking the DOM, looking for nodes that might match it. Just discovering that there’s nothing matching that leftmost part might take a page a while so browsers match from the right; it gives an obvious starting point and lets you get rid of most of the candidate selectors very quickly.

17. How is border-box different from content-box?
Answer:
* content-box: The width & height of the element only include the content. In other words, the border, padding and margin aren’t part of the width or height. This is the default value.
* border-box: The padding and border are included in the width and height.

18. How is opacity specified in CSS3?
Answer:
The CSS opacity property is used to specify the transparency of an element. In simple word, you can say that it specifies the clarity of the image. 
In technical terms, Opacity is defined as degree in which light is allowed to travel through an object.
Opacity setting is applied uniformly across the entire object and the opacity value is defined in term of digital value less than 1. The lesser opacity value displays the greater opacity. Opacity is not inherited.

19. Why should we use float property in CSS?
Answer:
We use Float in CSS when we want to place a particular content or an image either to left or the right.
If you want to align 2 or more elements next to each other horizontally (which are not inline elements), then you can use float:left or float:right depending on your requirements.
if you use float, after the floated elements, it is always better to have a element with clear:both property. otherwise the container element may act weirdly.
After the arrival of flexbox, float property is not that useful. but it will be useful in some situations where flexbox won’t work.

20. What is a z-index, how does it function?
Answer:
The z-index Css property sets the z-order of a positioned element and its descendants or flex items. Overlapping elements with a larger z-index cover those with a smaller one.
The z-index property in CSS controls the vertical stacking order of elements that overlap. As in, which one appears as if it is physically closer to you. z-index only affects elements that have a position value other than static(the default).

21. What are the properties of flexbox?
Answer:
The flex container properties are:
* flex-direction
* flex-wrap
* flex-flow
* justify-content
* align-items
* align-content

22. What is cascading in CSS?
Answer:
Cascading means pouring down in steps or adding in steps. Style sheets contains codes for styling a html element. And the manner in which the codes are written in style sheet is in the cascading fashion. Or simply, back to back codes in layers for each html element of a html page in style sheet make the cascading style sheet.

23. How to center align a div inside another div?
Answer:
This example describes how we can place a div inside another div.
<!DOCTYPE html>
<html>
<metaname="viewport"content="width=device-width, initial-scale=1.0">
<head>
<title>Placing div within a div</title>
<style>
h1 {  
     color:green; 
     text-size:2vw; 
     padding-left : 47px;  
   } 
h2 {  
     padding-left: 35px; 
     text-size:1vw;  
    }  
</style>  
</head>
<body>
<h1>GeeksforGeeks</h1>  
<h2>Placing div within a div</h2>
<divstyle="background-color:#4dff4d;width:20%;text-align:center;padding:7px;">
<divstyle="background-color:#33cc33;width:50%;text-align:center;padding:2px;">
  <h3style="font-size:2vw;">Example of div inside a div.</h3>
  <pstyle="font-size:2vw;">It has background color = #33cc33.</p>
  <pstyle="font-size:2vw;">This is some text in a div element.</p>
</div>
</div>
</body>
</html>


24. Can you name the four types of @media properties?
Answer:
The four types of @media properties are:
* All ? It’s the default property. Used for all media-type devices.
* Screen ? Used for computer screen, mobile screen.
* Print ? Used for printers.
* Speech ? Used for screen readers.

25. What is the grid system?
Answer:
CSS Grid Layout is a two-dimensional system, meaning it can handle both columns and rows, unlike flexbox which is largely a one-dimensional system (either in a column or a row). A core difference between CSS Grid and Flexbox is that — CSS Grid’s approach is layout-first while Flexbox’s approach is content-first.

26. What are the different ways to hide the element using CSS?
Answer:
There are the following CSS properties use to hide an element.
* Absolute position
* Color
* Clip-path
* Display
* Filter
* Measurements
* Opacity
* Transform
* Visibility

27. What does the :root pseudo-class refer to?
Answer:
The :root CSS pseudo-class matches the root element of a tree representing the the document. In HTML, :root represents the <html> element and is identical to the selector html, except that its specificity is higher.

28. Difference between CSS grid vs flexbox?
Answer:
Dimensions define the primary demarcation between Flexbox and CSS Grid. Flexbox was designed specifically for one-dimensional layouts, while CSS Grid is engineered to enable two-dimensional layouts. Therefore, CSS Grid can easily render rows and columns simultaneously.
In layperson’s terms, CSS Grid presents a larger canvas, while Flexbox offers minute functionality that operates in a restricted space. The grids have been designed for a two-dimensional organization.
However, the two specifications share some common points, and if you know how to use flexible boxes, you will find some concepts that will help you to grasp CSS grids.
In this article, we’ll go through the main differences between Grid and Flexbox, summarized as follows:
* Flexbox is designed for one-dimensional layouts, and Grid for two-dimensional layouts.
* The approach of CSS Grid is the layout first, while the Flexbox approach is primarily the content.
* The Flexbox layout is best suited to application components and small-scale layouts, while the Grid layout is designed for larger-scale layouts that are not linear in design.

29. What does !important mean in CSS?
Answer:
The !important rule in CSS is used to add more importance to a property/value than normal.
In fact, if you use the !important rule, it will override ALL previous styling rules for that specific property on that element!

30. How is margin different from padding in CSS?
Answer:
The main difference between CSS padding and margin is that padding is the space between the element’s content and border (within the element itself), while margin is the space around the border of an element.
  
