# My Markdown Sample

Hello, this is a markdown document. The key features include:

1. Open-source
2. Text-based syntax
3. Exports to PDF and HTML

> According to [Glen][1], this is a nice free, open-source program. Feel free to agree or disagree, but always provide evidence and cite your references for your claim.

[1]: https://www.coulthard.com/ "Coulthard.com"

## Section 1: Paragraphs

This is **the first content** that we'll be discussing. I have used a longer paragraph here in order to demonstrate word wrapping and how generated output will look in both HTML and PDF formats. The various notetaking programs will take different approaches to rendering and converting from markdown to PDF, but most will make use of [Pandoc](https://pandoc.org/).

## Section 2: Media

Markdown allows for the insertion of images and videos. However, the various *flavours* of markdown handle media differently, with only a few of them allowing **iframe embeds**. 

### Images

![Okanagan College](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT8bG7rSg7bHiHkMYuqoNbAhDht7DqS8oQt0IVK1nUH3rTt1oWq "Inserted from encrypted website")

### Giphy&#46;com GIFs

<!---
The heading above uses &#46; instead of a
period to stop the automatic URL linking.
--->

![Office Space](https://media.giphy.com/media/l3fQg5KqDwny04gus/giphy.gif)

### YouTube - Academic Writing in Markdown (640 x 360)

Direct link to [YouTube](https://www.youtube.com/watch?v=hpAJMSS8pvs) video.

<iframe width="640" height="360" src="https://www.youtube.com/embed/hpAJMSS8pvs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Techsmith Screencast iFrame (746 x 420)

Direct link to [Excel 01 - Lesson 01](https://www.screencast.com/t/YT9ULay2V24) video.

<iframe class="embeddedObject shadow resizable" name="embedded_content" scrolling="no" frameborder="0" type="text/html" 
        style="overflow:hidden;" src="https://www.screencast.com/users/GlenCoulthard/folders/Private/media/1f45458b-f986-4b74-9fa2-064d300abc16/embed" height="420" width="746" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

### Vimeo iFrame (800x450)

Direct link to [Excel 01 - Lesson 01](https://vimeo.com/137637301) video.

<iframe src="https://player.vimeo.com/video/137637301" width="800" height="450" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>

### TED Talk iFrame (746 x 420)

David McCandless on Data Visualization

<iframe src="https://embed.ted.com/talks/david_mccandless_the_beauty_of_data_visualization" width="746" height="420" style="position:relative;left:0;top:0;width:746;height:420" frameborder="0" scrolling="no" allowfullscreen></iframe>

### Google Map Embed

This example was taken from http://embedgooglemap.net.

<div class="mapouter"><div class="gmap_canvas"><iframe width="600" height="500" id="gmap_canvas" src="https://maps.google.com/maps?q=7000%20College%20Way%2C%20Vernon%2C%20BC&t=&z=13&ie=UTF8&iwloc=&output=embed" frameborder="0" scrolling="no" marginheight="0" marginwidth="0"></iframe></div><style>.mapouter{position:relative;text-align:right;height:500px;width:600px;}.gmap_canvas {overflow:hidden;background:none!important;height:500px;width:600px;}</style></div>

## Section 3: Code

Here is some bash script for you to review. Remember to use `sudo` for these commands.

```bash
# First, update your system
sudo apt update
sudo apt -y upgrade
# Now let's install some stuff
sudo apt install curl wget htop neofetch
```

Notice the HTML's syntax highlighting.

```html
<h1>Hello World</h1>
<p class="Tidy">This is an html paragraph and list.</p>
<ul>
    <li>One</li>
    <li>Two</li>
</ul>
<a href="http://www.coulthard.com">Coulthard.com</a>
```

## Section 4: Diagrams

Now for a mermaid flowchart diagram with font-awesome icons.

```mermaid
graph LR
A[Hard edge] -->B(Round edge)
    B --> C{Decision}
    C -->|One| D[fa:fa-ban Forbidden]
    C -->|Two| E[fa:fa-spinner Proceed]
```

How about a simple mermaid sequence diagram?

```mermaid
sequenceDiagram
A->>B: How are you?
B->>A: Great!
```

And, lastly, here is a mermaid gantt diagram.

```mermaid
gantt
dateFormat YYYY-MM-DD
section S1
T1: 2019-01-01, 12d
section S2
T2: 2019-01-11, 14d
section S3
T3: 2019-01-31, 9d
```

## Section 5: Tables, Checklists, and Math

### Tables

Tables are straightforward and colons can be used to align columns.

| Tables   | Are           | Cool  |
| -------- |:-------------:| -----:|
| col 3 is | right-aligned | $1600 |
| col 2 is | centered      | $12   |
| col 1 is | left-aligned  | $1    |

### Check Lists

What do I need to do today? Well, let's prepare a task list.

- [ ] Go to the market
- [x] Vacuum the floor
- [ ] Buy more wine

### Math Equations

**Some KaTeX/LaTeX ($) equations are supported.**

$f(x)$ 

$\sigma = \sqrt{ \frac{1}{N} \sum_{i=1}^N (x_i -\mu)^2}$

This equation is inline: $p={1\over q}$ 

>_See https://upmath.me for more LaTeX equations._ 

**You can also use AsciiMath/MathML blocks (\$$).**

$$
E = mc^2
$$

$$
x = {-b \pm \sqrt{b^2-4ac} \over 2a}
$$

## Section 6: Miscellaneous Features

### Icons, Footnotes, and Keyboard Buttons

Here are some basic emojis and a footnote[^1].  
:smile:  :beer:  :cat:  :dog: :santa: :heart:

How about a few keyboard graphics using `<kbd>`?  
PRESS: <kbd>Ctrl</kbd>+<kbd>F9</kbd> to proceed  
PRESS: <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> to reboot

[^1]: Emojis are small digital images, icons, or symbols used to express an idea or emotion. Here is the [complete list of github markdown emoji markup](https://gist.github.com/rxaviers/7360908).

### Definitions and Abbreviations/Acronyms

HTML
: Definition 1

CSS
: Definition 2a
: Definition 2b
  
*[HTML]: Hyper Text Markup Language 
*[CSS]: Cascading Style Sheet

### Admonitions and Alerts

Engage the reader with these message boxes.
:::success
Yes, **success** :tada:
:::

:::info
This is an **info** message :mega:
:::

:::warning
Watch for this lightning **warning** :zap:
:::

:::danger
Think **danger** if you smell smoke. :fire:
:::
