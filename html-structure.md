# Structuring pages with HTML

| [Table of Contents](https://penjoe.github.io/learning-journal/) | [Growth Mindset](https://penjoe.github.io/learning-journal/growth-mindset) | [Markdown](https://penjoe.github.io/learning-journal/markdown) | [Tools of the Trade](https://penjoe.github.io/learning-journal/coders-computer) | [Get Started with Git!](http://penjoe.github.io/learning-journal/git) | [Styling with CSS](http://penjoe.github.io/learning-journal/css) | [Computer Architecture and Logic](https://penjoe.github.io/learning-journal/comp-logic) |

First off, what is HTML? HTML stands for **H**yper **T**ext **M**arkup **L**anguage. It's a code language used primarilly for building web sites. Just about any web page out there has a bare bones foundation written in HTML. And although it has been around for a very long time, it still remains the standard for web development. It may not make a web page very fancy or add many cool features, but without HTML those cool features would never happen. Now that we know what HTML is, how do we use it? It's time to start writting some code!

HTML uses a series of what are called tags i a specific order to tell the browser what information to display. A tag is a bit of syntax between two angle brackets, like this `<html>`. This is the beginning tag of any HTML document. All following tags will go in between the opening and closing tag, closing tag simply meaning there is a forward slash, `/` preceeding the word inside the brackets. The number of tags available to use is quite massve, so you can't be expected to memorize them all. So long as you understand how they should be ordered, the rest can be referenced from a cheat sheet or documentaion guide. Let's play around with a few examples of what HTML looks like.

### **Time to code!**

This is an example of a very bare bones HTML layout:

    <html>
        <body>
            <h1>This is a header tag.</h1>
                <p>This is a paragrah tag. It's used to indicate a block of text.</p>
            <h2>This is a sub-header tag.</h2>
                <p>Notice the difference above between the h1 and h2 tags? Those are different size headers. An h1 tag indicates the largest header and h6 indicates the smallest header. So depending on how important you want something to be, you can use different size headers to relay level of importance.</p>
        </body>
    </html>

The above code is essentially a fully functional HTML document that could be published on the web. While it wouldn't look pretty, the code itself is what matters. There are tons of different options to play with, different tags all with different functions. The best way to know what tag works best in what situation is practice!

#### Here's a quick reference guide to get you started out with some basic HTML tags:

* `<html></html>` This tag indicates that anything between the opening and closing tag is HTML.
* `<body></body>` This tag is used to indicate what should appear within the main browser window.
* `<header></header>` The header tag indicates the section of the document that will appear at the top and would have basic information such as a page title, logo or maybe site navigation.
* `<h1> through <h6>` These are header tags. They can be used as the title or opening statement of any section or block of text.
* `<nav></nav>` This is used to create a navigation bar. You can easily add a list containing links to other pages or other sections of your own site.
* `<ul></ul>` These tags will create an unordered list. Inside this unordered list, add list items, or `<li></li>`. Inside of each list item can be a link used for navigation.
* `<a>` This is an anchor tag. An anchor tag is used to make a hyperlink, allowing you to link to other pages. Using the `href` attribute allows a URL to be added, thus linking to that URL. Here's an example of a working link: `<a href="https://www.google.com>This is a link to Google</a>`
* `<main></main>` This tag is used for the main working section of the page. Most information on the browser page will be displayed within these tags.
* `<section></section>` This tag will give you a smaller working area within the 'main' area. A section can be used for something like a blog aerticle or prduct information. There can be more than one section on a page.

There are tons of other tags that all have a specific purpose. But the above reference list is a good place to get started building your very own web document! 