# what is bootstrap ?

Bootstrap is a popular front-end web development framework that provides pre-built CSS and JavaScript components for creating responsive, mobile-first web pages and applications.

Bootstrap is widely used by developers as it offers a multitude of features, including a grid system, responsive design, and a variety of CSS classes. These features make it easy to create professional-looking websites that are optimized for mobile devices.

Bootstrap is also constantly updated with new features and improvements, so developers can always rely on it for their projects. Additionally, Bootstrap has an active community of developers who contribute to its open-source codebase, which means that users can easily find help and support when needed.

Overall, Bootstrap is a powerful tool for web developers who want to create responsive and mobile-friendly websites quickly and efficiently. Its features and community support make it a reliable choice for any project.

Bootstrap's grid system is one of its most popular features. It enables developers to create responsive layouts that adapt to different screen sizes and devices. The grid system is based on a 12-column layout, which can be easily customized to fit the needs of any project. Developers can use predefined CSS classes to define the size and position of elements on the page, making it easy to create complex layouts without writing custom CSS code.

In addition to the grid system, Bootstrap also offers a wide range of pre-built components, including buttons, forms, navigation menus, and more. These components are designed to be customizable and easy to use, allowing developers to create polished and professional-looking websites quickly and efficiently.

In conclusion, Bootstrap is an essential tool for web developers who want to create responsive and mobile-friendly websites quickly and efficiently. Its grid system, pre-built components, and community support make it a reliable choice for any project, big or small.

```jsx
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Bootstrap demo</title>
</head>
<body>
<h1>Hello, world!</h1>
</body>
</html>
```

```jsx
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KK94CHFLLe+nY2dmCWGMq91rCGa5gtU4mk92HdvYe+M/SXH301p5ILy+dN9+nJOZ" crossorigin="anonymous">
  </head>
  <body>
    <h1>Hello, world!</h1>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ENjdO4Dr2bkBIFxQpeoTz1HIcje39Wm4jDKdf19U8gI4ddQ3GYNS7NTKfAdVQSZe" crossorigin="anonymous"></script>
  </body>
</html>
```

- Those of above code refer we use two links  first links are use in head part use for link css part

the other link we use body part is links for java 

# Why Use Bootstrap?

Advantages of Bootstrap:

- **Easy to use:** Anybody with just basic knowledge of HTML and CSS can start using Bootstrap
- **Responsive features:** Bootstrap's responsive CSS adjusts to phones, tablets, and desktops
- **Mobile-first approach:** In Bootstrap 3, mobile-first styles are part of the core framework
- **Browser compatibility:** Bootstrap is compatible with all modern browsers (Chrome, Firefox, Internet Explorer, Edge, Safari, and Opera)

# Basic Structure of a Bootstrap Grid

The following is a basic structure of a Bootstrap grid:

```jsx
<div class="row">
  <div class="col-*-*"></div>
  <div class="col-*-*"></div>
</div>
<div class="row">
  <div class="col-*-*"></div>
  <div class="col-*-*"></div>
  <div class="col-*-*"></div>
</div>
<div class="row">
  ...
</div>
```

First; create a row (`<div class="row">`). Then, add the desired number of columns (tags with appropriate `.col-*-*` classes). Note that numbers in `.col-*-*` should always add up to 12 for each row.

# Three Equal Columns

| .col-sm-4 | .col-sm-4 | .col-sm-4 |
| --- | --- | --- |

- The following example shows how to get a three equal-width columns starting at tablets and scaling to large desktops. On mobile phones or screens that are less than 768px wide, the columns will automatically

```jsx
<div class="row">
  <div class="col-sm-4">.col-sm-4</div>
  <div class="col-sm-4">.col-sm-4</div>
  <div class="col-sm-4">.col-sm-4</div>
</div>
```

# Two unequal element

| .col-sm-4 | col-sm-8 |
| --- | --- |

The following example shows how to get two various-width columns starting at tablets and scaling to large desktops

```jsx
<div class="row">
  <div class="col-sm-4">.col-sm-4</div>
  <div class="col-sm-8">.col-sm-8</div>
</div>
```

# Bootstrap text / typography

# < small>

In Bootstrap the HTML `<small>` element is used to create a lighter, secondary text in any heading

# Example

# h1 heading secondary text

## h2 heading secondary text

### h3 heading secondary text

# <abbr>

Bootstrap will style the HTML `<abbr>` element in the following way

# Example

The WHO was founded in 1948

# <blockquote>

Bootstrap will style the HTML `<blockquote>` element in the following way:

# Example

For 50 years, WWF has been protecting the future of nature. The world's leading conservation organization, WWF works in 100 countries and is supported by 1.2 million members in the United States and close to 5 million globally

# <dl>

Bootstrap will style the HTML `<dl>` element in the following way:

# Example

**Coffee**- black hot drink**Milk**- white cold drink

# <kbd>

Bootstrap will style the HTML `<kbd>` element in the following way:

# Example

Use ctrl + p to open the Print dialog box

# <pre>

Bootstrap will style the HTML `<pre>` element in the following way:

# Example

`Text in a pre element
is displayed in a fixed-width
font, and it preserves
both      spaces and
line breaks.`