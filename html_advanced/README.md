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
- Title with <p> and <button>
- Title with 4 divs within <img>, <h3> and <p>
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