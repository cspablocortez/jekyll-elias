# Jekyll

Jekyll is a static site generator to transform plaintext to static websites.

## Installation

Create a new directory for your project and install the gem:

```sh
gem install jekyll bundler
```

Create a Gemfile:

```sh
bundle init
```

Edit the `Gemfile` and add Jekyll as a dependency:

Inside `Gemfile`:

```sh
gem "jekyll"
```

## Start Project

Create an `index.html` file that uses `Liquid`. To activate it, make sure you have `Front Matter` in your file:

```html
---
title: Home
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{{ page.title }}</title>
</head>
<body>
    <h1>{{ "Hello World!" | downcase }}</h1>
</body>
</html>
```

More about [Liquid](https://jekyllrb.com/docs/liquid/)
More about [Front Matter](https://jekyllrb.com/docs/front-matter/)

<hr>

At the end of class we left off [here](https://jekyllrb.com/docs/step-by-step/04-layouts/#use-layouts).
