# HTML, advanced

## Holberont school project - specialisation Full stack -

In this project, you will implement from scratch a webpage from a designer file.<br>
For this first project, you will focus on the HTML structure only - no CSS, no style - just pure HTML semantic.<br>

### Task 1 : Header
In first time, we create the header with the logo and a menu with 3 links.
```
<body>
    <header>
        <div>
            <a href="#">
                <img src="image.jpg" alt="logo">
            </a>
        </div>
        <div>
            <ul>
                <li><a href="#">Link 1</a></li>
                <li><a href="#">Link 2</a></li>
                <li><a href="#">Link 3</a></li>
            </ul>
        </div>
    </header>
</body>
```

### Task 2 : Banner
Under the header, add a main element with inside a section element.
In this section, you have 2 div :
- Title with paragraphe and button
- Title with 4 divs within img, h3 and paragraphe
```
<main>
    <section>
        <div>
            <h1>Title</h1>
            <p>3 WORDS</p>
            <button>Button</button>
        </div>
        <div>
            <h2>Title</h2>
            <div>
                <div>
                    <img src="image1.jpg" alt="image 1">
                    <h3>Name1</h3>
                    <p>SUB-TITLE</p>
                </div>
                <-- 3 idem div -->
            </div>
        </div>
    </section>
</main>
```

### Task 3 : Quote
Under the banner, we will add the quote block:
The quote section is inside the main, create a new section for the quote.
Inside, add a block containing with an image and another block with inside a quote tag, an author quote and a text.
```
<section>
    <div>
        <img src="image5.jpg" alt="image 5">
        <div>
            <blockquote>
                <p>QUOTE</p>
            </blockquote>
            <p>Author</p>
            <p>Sub-Title</p>
        </div>
    </div>
</section>
```

### Task 4 : Videos
Let’s now add the videos list:<br>
New section with inside An heading tag, a block containing the 4 video block, each of them are composed with : An image, an heading, a text, a block for the author : image and heading, and finally a block for the rating with a block image and text.
```
<section>
    <h1>Title</h1>
    <div>
        <div>
            <img src="image6.jpg" alt="image 6">
            <h2>Title</h2>
            <p>TEXT</p>
            <div>
                <img src="image6-1.jpg" alt="image 6-1">
                <h3>Title</h3>
            </div>
            <div>
                <div>
                    <img src="star.png" alt="Star">
                    <img src="star.png" alt="Star">
                    <img src="star.png" alt="Star">
                    <img src="star.png" alt="Star">
                    <img src="star.png" alt="Star">
                </div>
                <p>Text</p>
            </div>
        </div>
        <-- Add 3 more time this div for video -->

    </div>
</section>
```

### Task 5 : Membership
Membership section is similar as the videos list.<br>
After the videos list section, add a new section containing:<br>
An heading, A block with inside 4 block item - each block defined with:
- An image
- An heading
- A text
And finally a button.
```
 </section>
    <h1>TITLE</h1>
    <div>
        <div>
            <img src="image10.jpg" alt="image 10">
            <h2>Title</h2>
            <p>TEXT</p>
        </div>
        <div>
            <img src="image11.jpg" alt="image 11">
            <h2>Title</h2>
            <p>TEXT</p>
        </div>
        <div>
            <img src="image12.jpg" alt="image 12">
            <h2>Title</h2>
            <p>TEXT</p>
        </div>
        <div>
            <img src="image13.jpg" alt="image 13">
            <h2>Title</h2>
            <p>TEXT</p>
        </div>
    </div>
    <button>BUTTON</button>
</section>
```

### Task 6 : FAQ
The FAQ section is ending the page before the footer.<br>
Add a section for the FAQ with inside:
- A block that contains 2 “row block”
- Each “row block” contains 2 “item block”
- Each “item block” is composed of: An heading and a text.
```
<section>
    <h1>TITLE</h1>
    <div>
        <div>
            <div>
                <h2>Title</h2>
                <p>TEXT</p>
            </div>
            <div>
                <h2>Title</h2>
                <p>TEXT</p>
            </div>
        </div>
        <div>
            <div>
                <h2>Title</h2>
                <p>TEXT</p>
            </div>
            <div>
                <h2>Title</h2>
                <p>TEXT</p>
            </div>
        </div>
    </div>
</section>
```

### Task 7 : Footer
After the last section, outside of the main, add a footer :
- A global block (used later for centering the footer content), inside this block: A row block with an image, a block with inside images with link
- A text.
```
<footer>
    <div>
        <div>
            <div>
                <img src="image14.jpg" alt="image 14">
            </div>
            <div>
                <a href="#">
                    <img src="link1.png" alt="Link 1">
                </a>
                <a href="#">
                    <img src="link2.png" alt="Link 2">
                </a>
                <a href="#">
                    <img src="link2.png" alt="Link 3">
                </a>
            </div>
        </div>
        <p>Text</p>
    </div>
</footer>
```
