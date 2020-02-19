# Styling with CSS

While HTML will give you the bones of a web page, CSS is used to make that web page presentable. CSS, which stands for Cascading Style Sheets, tells the browser what everything is supposed to look like. This is accomplished by selecting an element to style and then applying a ruleset, indicating how that element should be presented. Here's a quick example:
```
body {
    background-color: yellow;
}
```
In this example, the background of the `<body>` in the HTML will be yellow. Here's a breakdown of the above CSS:
* `body` is the selector, the element of HTML you are wanting to style
* `background-color` is the property, meaning what aspect you are trying to style of that element
* `yellow` is the value, the setting you want to apply to the chosen property

All together, this is refered to as a ruleset. A ruleset can apply to one thing or to multiple, depending on the selector used. You can select a specific HTML tag like we did above, or use specific CSS selectors to indicate specific parts. Class is a common selector for CSS. For class, you can write a specific attribute into an HTML tag, like this `<p class="example">`. This means that by selecting the class "example" in CSS, you would be styling the paragraph within those tags. In CSS, you would write:
```
.example {
    font-family: helvetica;
}
```
This would make that paragraph with the "example" class attribute to be in Helvetica font. Only that paragraph would be styled unless you added that specific class elsewhere. To reference a class in CSS, simply add a `.` before the class value, like in the example. `.example` was the class selector. There are a lot of other selectors you can use depending on the reuslts you are looking for.

### How the rulesets are followed:

As the name inplies, CSS rules cascade. If you have identical selectors giving different rulesets, whichever ruleset comes last will be applied. Also, if one ruleset has a more specific selector than the other, the more specific selector will take precedence. It's important to keep this in mind so you'll be able to keep track of what rulesets are being followed. In the case you want one specific selector to be followed before others of the same type, simply add `!important` after the value to indicate it should be applied first. Any value applied to an element will also apply to any of that element's child elements.

### Adding a bit of color:

Adding color is a very easy way to breathe some life into your web page. With CSS, you can add color to part or all of any element you want. You can specify what color value you want in one of three ways:
* RGB values: This goes off of how much red, blue and green are used using values between 0 and 255. An example would be 50,30,60. 
* Hex codes: These are six-digit codes that represent how much red, blue and green are used, preceeded by a `#`. `#ee3e80` is an example of a hex code. 
* Color names: There are 147 predefined color names recognized by browsers, for example 'green' or 'cyan'.
* Click [**HERE**](https://color.adobe.com/create) for a fun tool for picking colors!

Using these three methods, you can change the color value of any element using CSS. There are tons of benefits to changing the color of a document. Contrast can make font easier to read. Certain colors can draw attention to areas you want users to focus on. It also makes it more exciting and user friendly.

With the newest version of CSS, CSS3, you can also adjust color opacity. This is doen with the RGBA property whereas the 'A' stands for aplha. Using a number between 0.0 and 1, you can change the opacity of your color to add yet another flavor to your web page. CSS3 has also added a color property called `hsl` and `hsla`. Hsla stands for hue, saturation, lightness and alpha. This just gives a further level of customizaton for adding color to a web page.