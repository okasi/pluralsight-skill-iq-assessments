# Building Websites with HTML, CSS, and JavaScript

---

### Q: In HTML, what is the purpose of the size attribute?
#### A: To specify the length of an input field

---

### Q: A project recently suffered a security breach because the team used the hidden input type to store sensitive information. In hindsight, what fact, if known, could have prevented this breach from occurring?
#### A: That values stored with the hidden input type are visible in any browser's developer tools or "View Source" 

---

### Q: At a simple level, what does the cascade of Cascading Style Sheets (CSS) mean?
#### A: That the order of CSS rules matters 

---

### Q: You must change the direction in which the flex items are displayed on an e-commerce website. Which CSS rule will change the direction to the right of the flex container? 
#### A: 
```
.box {
          display: flex;
          flex-direction: row-reverse;
  }
```

---

### Q: You are building a mobile application and are using localStorage to temporarily store data. What function could you use to add a key and value to localStorage?
#### A: setItem()

---

### Q: Which CSS snippet will adjust the space between the columns of a grid layout?
#### A:
```
.grid-container {
  display: grid;
  grid-column-gap: 50px;
  grid-template-columns: auto auto auto;
}
```
---

### Q: You want to embed an image, which is a diagram, in an HTML page so the document flow is NOT affected if the image is removed from the page. How would you achieve this?
#### A: Use the `<figure>` tag to specify the container, then place images inside it with `<img>`. 

---

### Q: You are developing a website. You must display some data as a graph on one of the web pages. How will you achieve this?
#### A: Use the `<canvas>` element.

---

### Q: You created a Google Chrome extension and are storing data with localStorage. How can you manually view your browser's localStorage data with Chrome DevTools?
#### A: Go to the Application tab, and in the Storage section expand Local Storage.

---

### Q: CSS sprites are memory friendly because of their single-file nature. What other performance benefit can you gain through accessing images using sprites?
#### A: They reduce network bandwidth usage.

---

### Q: You are writing the first few lines of a website with HTML Upon rendering the document you receive an error stating: "Error: "DOCTYPE" declaration not allowed in instance." What could you do to fix this?
#### A: Remove the `<html>` tag.

---

### Q: What HTML tag can you use to explicitly create a new document outline?
#### A: `<article>`

---

### Q: Which is a good use case for inline CSS styling on an HTML file?
#### A: Developing an HTML email that cannot link to an external stylesheet

---

### Q: You are working on a movie streaming platform that must display timed text tracks on the video. How can you do this?
#### A: Create a .vtt file and specify in the `<track>` element of the video tag on the site

---

### Q: You want to set a relationship between a document linked using the `<a>` tag and the current document. How can you do this?
#### A: Set the rel attribute of the `<a>` tag to next.

---

### Q: Which code can you use to take a CSS block div with a width that is not specified and make it smaller on the right side?
#### A: margin-right: 5px;

---

### Q: What is the advantage of using Portable Network Graphics?
#### A: They support alpha transparency.

---

### Q: In CSS, the relative units of measurement are based on some other value. In the case of ems, what value are they relative to?
#### A: The font size of the container element

---

### Q: You must use a CSS property that can both place an element on either the left or right side of its container, and have other inline elements wrap around it. What property should you choose?
#### A: Float

---

### Q: You inserted a Google map into your website but the map is not displaying. Instead, all you see is an error that says "This page didn't load Google Maps correctly." You open the JavaScript console and find a "MissingKeyMapError." What is the most likely explanation for this error?
#### A: An API key is not being used.

---

### Q: What should be the value of the rel attribute of the link tag used to specify the favicon for a web page?
#### A: icon

---

### Q: Which link type does HTML5 highly recommend for your website page linking?
#### A: Relative

---

### Q: How does a browser handle JavaScript and HTML?
#### A: The browser reads HTML first and creates a content tree. The browser parses JavaScript separately as the `<script>` tag encounters it.

---

### Q: As far as webpage layouts are concerned, what does CSS Flexbox (Flexible Box Layout) do better than CSS Grid?
#### A: Align content inside elements

---

### Q: Below are CSS rules that set the background of an HTML element as a gradient:
```
.horizontal-gradient {
  background: linear-gradient(blue, pink);
}
```
### When you apply the rule, a gradient ranging from a dark blue to a light pink shows. You want the gradient to show from left to right, however. How can you adjust the current CSS to accommodate this feature?
#### A: Add to right, before blue

---

### Q: You are designing a webpage for a client that needs a fast, static page to market its business. The client had problems with page fonts loading very slowly in the past and wants to ensure that this is not an issue moving forward. The page fonts the client uses are generally common fonts. What can you do to ensure better load times for fonts in this case?
#### A: Compress the font file so it takes up less space.

---

### Q: You are working on a site and one of the web pages has a lot of content. To reduce the text, you want to have an interactive widget a user can open and close to see contents on demand. How can you achieve this?
#### A: Use the <details> element

---

### Q: You have an ordered list with a display property inline-block and must use a nav element to wrap it. What will happen when you do this?
#### A: You will create a horizontal navigation bar.

---

### Q: You are aligning text on a webpage meant for posting scientific research results using CSS. So far, your layout has remained clean and intactcas it was when you first designed the page. You apply text-align: justify; to one of your blog text paragraphs, however, and it makes the page less readable. Why did this most likely happen?
#### A: The justify rule can make paragraphs with many long words in them look jumbled.  

---

### Q: On what parameter do browsers limit localStorage size allocated to a website?
#### A: per domain

---

### Q: transform is one of the major properties with CSS transform. Which is the other?
#### A: transform-origin

---

### Q: A campaign in your Google Analytics account has been running for a week and now you must show some results for the campaign moving forward. What must you add to your destination URLs to collect results data?
#### A: Campaign parameters

---

### Q: You want to use the character code U+007E in a document written in HTML4 to display a ~ symbol, but are encountering a problem where the code renders as itself rather than the desired symbol. What could be the reason for this?
#### A: HTML4 uses the default character set 8859-1, so you must specify the correct charset in the `<meta>` element.

---

### Q: You want to use cookies and the Fetch API to read server-side data but are having trouble. After a successful login there is a cookie header in future requests, but Fetch is ignoring those headers, and all your requests made with Fetch are unauthorized. What can you do to fix this issue?
#### A: 
#### Enable cookies with the following script:
```
fetch(url, {
credentials: "same-origin"
}).then(...).catch(...);
```
---

### Q: You included a subtitle feature in your video using the following code, but the subtitle is not showing. What is the problem with this code?
```
video width="640" height="480" controls>
  <source src="hello.mp4" type="video/mp4" />
  <source src="hello.webm" type="video/webm" />
  <track kind="subtitles" srclang="en" label="English" />
</video>
```
#### A: The .vtt for the track element was not specified

---

### Q: Which storage type would you use if you want to ensure that changes made to the data in a tab do NOT affect other tabs?
#### A: sessionStorage

---

### Q: You must include navigation links that take a user to a spot within the document they are reading or to another document. What HTML element should you use? 
#### A: nav
