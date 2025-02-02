# openSnippets

![openSnippets](images/openSnippets1.png)

openSnippets is a platform for sharing and exploring creative code snippets using p5.js!

link to: [openSnippets](https://www.opensnippets.com/)\
link to: [about page](https://www.opensnippets.com/about.html)

![openSnippets](images/openSnippets2.png)

![openSnippets](images/openSnippets3.png)

![openSnippets](images/openSnippets4.png)

![openSnippets](images/openSnippets5.png)

![openSnippets](images/openSnippets6.png)


### How to Create a Snippet

Each snippet needs to have two main functions:

-   `setup()`: This function runs once when the program starts.
-   `draw()`: This function runs continuously after setup(), creating animation.

To ensure your snippet works well on our platform, please use a dynamic canvas size:

```
function setup() {
  createCanvas(windowWidth, windowHeight);
  // Your setup code here
}

function draw() {
  // Your drawing code here
}
```

### Example Snippet

Here's a simple example to get you started:

```
function setup() {
  createCanvas(windowWidth, windowHeight);
  background(220);
}

function draw() {
  if (mouseIsPressed) {
    fill(0);
  } else {
    fill(255);
  }
  ellipse(mouseX, mouseY, 80, 80);
}
```

This snippet does the following:

1.  Creates a canvas that fills the window
2.  Sets a light gray background
3.  Draws a circle at the mouse position
4.  The circle is black when the mouse is pressed, white when it's not

### Learn More

Ready to dive deeper? Check out the [p5.js tutorials](https://p5js.org/tutorials/) for more in-depth guides and examples.

### Tips for Using openSnippets

For the best coding experience, we recommend using the [p5.js editor](https://editor.p5js.org/) to write your code. You can then paste it here to post your snippet!

When you create a snippet, the app first serves a JPG file as a preview. If you want to see the live canvas, simply click on the preview to load it.

We categorize code lengths into four categories:

-   0 -- 256 characters : **tiny**
-   256 -- 512 characters : **short**
-   512 -- 1024 characters : **medium**
-   1024+ characters : **long**

Join our community on [Discord](https://discord.gg/your-discord-link) and [Twitter](https://twitter.com/your-twitter-handle) to share and discuss your experiences with openSnippets!

[Back to Projects](projects.html)
