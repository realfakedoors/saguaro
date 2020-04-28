# saguaro

![](/static/saguaro-logo.png)

A lightweight CSS framework based on Flexbox.

Adjust to your heart's content, and compile with Sass:
```
sass saguaro.scss output.css
```

## Container

A responsive, all-purpose content box.

```sh
<div class="container">
  <div class="row">
    <div>70px</div>
    <div>70px</div>
    <div>70px</div>
    <div>70px</div>
    <div>70px</div>
    <div>70px</div>
    <div>70px</div>
    <div>70px</div>
    <div>70px</div>
    <div>70px</div>
    <div>70px</div>
    <div>70px</div>
  </div>
</div>
```

![](/static/screenshots/container-desktop.png)
![](/static/screenshots/container-tablet.png)
![](/static/screenshots/container-mobile.png)

## Box

A simple container with a shadow, a border and some padding.

```sh
<div class="box"></div>
```

![](/static/screenshots/box.png)

## Navbar

A basic nav with a dropdown item available.

```sh
<nav class="navbar background-secondary">
  <a class="navbar-item" href="#">Home</a>
  <a class="navbar-item" href="#">About</a>
  <a class="navbar-item" href="#">Contact</a>
  <div class="navbar-item has-dropdown">
    More
    <div class="navbar-dropdown background-saguaro-green">
      <a class="navbar-item" href="#">Company</a>
      <hr class="navbar-divider">
      <a class="navbar-item" href="#">Explore</a>
    </div>
  </div>
</nav>
```

![](/static/screenshots/navbar.png)

## Colors

A few default colors have been provided. Feel free to change them. Use them in any class!

```sh
<h1>Default Colors:</h1>

<div class="background-saguaro-green">background-saguaro-green</div>
<div class="background-primary">background-primary</div>
<div class="background-secondary">background-secondary</div>
<div class="background-warning">background-warning</div>
<div class="background-alert">background-alert</div>

<div class="text-saguaro-green">text-saguaro-green</div>
<div class="text-primary">text-primary</div>
<div class="text-secondary">text-secondary</div>
<div class="text-warning">text-warning</div>
<div class="text-alert">text-alert</div>
```

![](/static/screenshots/default-colors.png)