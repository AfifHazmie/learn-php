<a href="https://github.com/drshahizan/learn-php/stargazers"><img src="https://img.shields.io/github/stars/drshahizan/learn-php" alt="Stars Badge"/></a>
<a href="https://github.com/drshahizan/learn-php/network/members"><img src="https://img.shields.io/github/forks/drshahizan/learn-php" alt="Forks Badge"/></a>
<a href="https://github.com/drshahizan/learn-php/pulls"><img src="https://img.shields.io/github/issues-pr/drshahizan/learn-php" alt="Pull Requests Badge"/></a>
<a href="https://github.com/drshahizan/learn-php/issues"><img src="https://img.shields.io/github/issues/drshahizan/learn-php" alt="Issues Badge"/></a>
<a href="https://github.com/drshahizan/learn-php/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/drshahizan/learn-php?color=2b9348"></a>
![](https://visitor-badge.glitch.me/badge?page_id=drshahizan/learn-php)

Don't forget to hit the :star: if you like this repo.

# Utility
Bootstrap CSS utility classes are a set of pre-defined classes that can be used to apply quick and easy styles to HTML elements. These classes allow you to add various styles, such as text alignment, padding, margin, and color, to your HTML elements without writing custom CSS.

Bootstrap CSS utility classes are categorized into various types, such as display, flexbox, spacing, text, border, color, and sizing. Here are some commonly used Bootstrap CSS utility classes:

Sure, here's a table describing some of the commonly used Bootstrap CSS utility classes:

| Item                  | Description                                                       | Example                                       |
|-----------------------|-------------------------------------------------------------------|-----------------------------------------------|
| `d-none`              | Hide an element on all devices                                     | `<div class="d-none">...</div>`              |
| `d-sm-none`           | Hide an element on devices smaller than or equal to small        | `<div class="d-sm-none">...</div>`           |
| `d-md-none`           | Hide an element on devices smaller than or equal to medium       | `<div class="d-md-none">...</div>`           |
| `d-lg-none`           | Hide an element on devices smaller than or equal to large        | `<div class="d-lg-none">...</div>`           |
| `d-xl-none`           | Hide an element on devices smaller than or equal to extra large  | `<div class="d-xl-none">...</div>`           |
| `d-block`             | Display an element as a block-level element                       | `<div class="d-block">...</div>`             |
| `d-inline`            | Display an element as an inline-level element                      | `<div class="d-inline">...</div>`            |
| `d-inline-block`      | Display an element as an inline-level block container              | `<div class="d-inline-block">...</div>`      |
| `d-flex`              | Create a flexbox container                                          | `<div class="d-flex">...</div>`              |
| `align-items-center`  | Vertically center the flex items in a container                    | `<div class="d-flex align-items-center">...</div>` |
| `justify-content-center` | Horizontally center the flex items in a container               | `<div class="d-flex justify-content-center">...</div>` |
| `p-3`                 | Add padding to an element. The number represents the size of the padding.  | `<div class="p-3">...</div>`   |
| `m-3`                 | Add margin to an element. The number represents the size of the margin.   | `<div class="m-3">...</div>`   |
| `text-center`         | Horizontally center the text in an element                         | `<h1 class="text-center">...</h1>`           |
| `text-muted`          | Set the color of the text to a muted gray color                     | `<p class="text-muted">...</p>`              |
| `border`              | Add a border to an element                                          | `<div class="border">...</div>`              |
| `border-top`                   | Add a border to the top of an element                                | `<div class="border-top">...</div>`          |
| `border-bottom`       | Add a border to the bottom of an element                             | `<div class="border-bottom">...</div>`       |
| `border-primary`      | Set the border color to the primary color                            | `<div class="border border-primary">...</div>`|
| `bg-primary`          | Set the background color to the primary color                        | `<div class="bg-primary">...</div>`           |
| `text-white`          | Set the text color to white                                          | `<p class="text-white">...</p>`              |
| `rounded`             | Add rounded corners to an element                                    | `<div class="rounded">...</div>`             |
| `rounded-circle`      | Create a circular shape for an element                               | `<div class="rounded-circle">...</div>`      |
| `w-50`                | Set the width of an element to 50%                                   | `<div class="w-50">...</div>`  |
| `h-50`                | Set the height of an element to 50%                                  | `<div class="h-50">...</div>`                |
| `img-fluid`           | Make an image responsive                                             | `<img src="..." class="img-fluid">`          |
| `text-uppercase`      | Convert the text to uppercase                                        | `<h1 class="text-uppercase">...</h1>`         |
| `text-lowercase`      | Convert the text to lowercase                                        | `<h1 class="text-lowercase">...</h1>`         |
| `text-capitalize`     | Capitalize the first letter of each word in the text                | `<h1 class="text-capitalize">...</h1>`        |
| `font-weight-bold`    | Set the font weight to bold                                          | `<p class="font-weight-bold">...</p>`         |
| `font-italic`         | Set the font style to italic                                         | `<p class="font-italic">...</p>`              |
| `text-truncate`       | Truncate the text and add ellipsis at the end if it overflows       | `<p class="text-truncate">...</p>`            |
| `text-wrap`           | Wrap the text to the next line if it overflows                       | `<p class="text-wrap">...</p>`                |
| `text-break`          | Break the text at the end of the line if it overflows                | `<p class="text-break">...</p>`               |
| `text-nowrap`         | Prevent the text from wrapping to the next line                       | `<p class="text-nowrap">...</p>`              |

These utility classes can be used to quickly add styles and modify the layout of elements in a Bootstrap-powered web page.

## Code
An example of a webpage that uses Bootstrap utility classes to create a simple and responsive layout:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Bootstrap Utility Classes Example</title>
    <link
      rel="stylesheet"
      href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
    />
  </head>
  <body>
    <header class="bg-dark text-white py-3">
      <div class="container">
        <div class="row">
          <div class="col-6">
            <h1>My Website</h1>
          </div>
          <div class="col-6 text-right">
            <p>Welcome, Dr MSO</p>
          </div>
        </div>
      </div>
    </header>
    <div class="container mt-3">
      <div class="row">
        <div class="col-md-8">
          <h2>Latest News</h2>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla quis
            molestie quam. Morbi quis ante velit. Pellentesque vel dolor at eros
            varius lacinia in vel magna. Sed rhoncus, libero ac scelerisque
            rutrum, est quam consectetur arcu, non volutpat nibh nunc non nisi.
          </p>
        </div>
        <div class="col-md-4">
          <h2>Upcoming Events</h2>
          <ul class="list-group">
            <li class="list-group-item">Event 1</li>
            <li class="list-group-item">Event 2</li>
            <li class="list-group-item">Event 3</li>
          </ul>
        </div>
      </div>
    </div>
    <footer class="bg-dark text-white py-3">
      <div class="container">
        <div class="row">
          <div class="col-12 text-center">
            <p>&copy; 2023 My Website</p>
          </div>
        </div>
      </div>
    </footer>
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
  </body>
</html>

```

In this example, Bootstrap utility classes are used to:

- Set the background color and text color of the header and footer using the `bg-dark` and `text-white` classes
- Create a row with two columns that are sized differently on small and medium screens using the `row` and `col-*` classes
- Add spacing between the header and the main content using the `mt-3` class
- Create a list of events using the `list-group` and `list-group-item` classes
- Center the text in the footer using the `text-center` class. 

The HTML code also includes links to the Bootstrap CSS and JavaScript files hosted on CDNs, which are necessary to use Bootstrap.

## Contribution 🛠️
Please create an [Issue](https://github.com/drshahizan/learn-php/issues) for any improvements, suggestions or errors in the content.

You can also contact me using [Linkedin](https://www.linkedin.com/in/drshahizan/) for any other queries or feedback.

![](https://visitor-badge.glitch.me/badge?page_id=drshahizan)
