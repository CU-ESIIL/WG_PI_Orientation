---
layout: default
---

<!doctype html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title>Markdown Slideshow</title>
    <meta name="description" content="A slideshow created with reveal.js and Markdown.">
    <meta name="author" content="Your Name">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reveal.js/dist/reveal.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reveal.js/dist/theme/white.css" id="theme">
    <link rel="stylesheet" href="css/custom.css">
</head>
<body>
    <div class="reveal">
        <div class="slides">
            <section data-markdown>
                <textarea data-template>
                    # Welcome to My Slideshow

                    ---

                    ## Slide 1

                    - Item 1
                    - Item 2
                    - Item 3

                    ---

                    ## Slide 2

                    > "A quote to remember."

                    ---

                    ## Slide 3

                    ### A Subsection

                    1. First item
                    2. Second item
                    3. Third item

                    Note: This is a note for the presenter.
                </textarea>
            </section>
        </div>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/reveal.js/dist/reveal.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/reveal.js/plugin/markdown/markdown.js"></script>
    <script>
        Reveal.initialize({
            plugins: [ RevealMarkdown ]
        });
    </script>
</body>
</html>
