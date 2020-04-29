# saguaro

![](/static/saguaro-logo.png)

A lightweight CSS framework based on Flexbox.

Adjust to your heart's content, and compile with Sass:
```
sass saguaro.scss output.css
```

# Documentation

* [Colors](#colors)
* [Container](#container)
* [Box](#box)
* [Navbar](#navbar)
* [Form Elements](#form-elements)
* [Buttons](#buttons)
* [Divider](#divider)
* [Hero](#hero)
* [Image](#image)
* [Card](#card)
* [Media Object](#media-object)

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

## Form Elements

Standard generic form controls.

```sh
<div class="form">
  <div class="field">
    <label class="label">Text Field</label>
    <input class="text-input" type="text" placeholder="enter text input...">
  </div>
  <div class="field">
    <label class="label">Select Box</label>
    <select class="select-input">
      <option>Dropdown</option>
      <option>Choose from options</option>
      <option>Make a selection!</option>
    </select>
  </div>
  <div class="field">
    <label class="label">Text Area</label>
    <textarea class="text-area" placeholder="a larger, resizable text box."></textarea>
  </div>
  <div class="field">
    <label class="label">
      <input type="checkbox" class="checkbox">
        Checkbox
    </label>
  </div>
  <div class="field">
    <label class="label">Radio Buttons</label>
    <label class="label radio-label">
      <input class="radio-button" type="radio" name="question">
      Yes
    </label>
    <label class="label radio-label">
      <input class="radio-button" type="radio" name="question">
      No
    </label>
  </div>
</div>
```

![](/static/screenshots/form-elements.png)

## Buttons

A simple, all-purpose button.

```sh
<div class="buttons">
  <button class="button background-saguaro-green">Submit</button>
  <button class="button background-primary">Submit</button>
  <button class="button background-secondary">Submit</button>
  <button class="button background-warning">Submit</button>
  <button class="button background-alert">Submit</button>
</div>
<div class="buttons">
  <button class="button text-saguaro-green">Submit</button>
  <button class="button text-primary">Submit</button>
  <button class="button text-secondary">Submit</button>
  <button class="button text-warning">Submit</button>
  <button class="button text-alert">Submit</button>
</div>
```

![](/static/screenshots/buttons.png)

## Divider

A prominent horizontal rule for separating content.

```sh
<h2>A divider such as the one below</h2>
<hr class="divider">
<h2>can help you separate your content!</h2>
```

![](/static/screenshots/divider.png)

## Hero

A banner to showcase content.

```sh
<div class="hero">
  <h1 class="hero-title">Hero Title</h1>
  <h2 class="hero-subtitle">hero subtitle</h2>
</div>
```

![](/static/screenshots/hero.png)

## Image

An image container with a title and subtitle.

```sh
<div class="image-container">
  <img src="coolspot.png">
  <h2 class="image-text">
    Cool Spot (or simply Spot) was a <br /> mascot for 7 Up in the United States.
  </h2>
  <h3 class="image-subtext">
    He is an anthropomorphic version of the red dot in the 7 Up logo.
  </h3>
</div>
```

![](/static/screenshots/image.png)

## Card

A container with a main image and content below.

```sh
<div class="card">
  <div class="card-image">
    <img src="/omega_weapon.jpg">
  </div>
  <div class="card-content">
    <div class="media">
      <div class="img">
        <img src="/omega_weapon.jpg">
      </div>
      <p class="title">Omega Weapon</p>
      <p class="subtitle">one BAD mamma-jamma.</p>
    </div>
    <div class="content">
      Omega Weapon is an optional "super-boss" in Final Fantasy VIII. To prepare for this fight, you are highly advised to max every stat you possibly can.
    </div>
  </div>
</div>
```

![](/static/screenshots/card.png)

## Media Object

A useful image/title/subtitle combo.

```sh
<div class="box">
  <div class="media">
    <div class="img">
      <img src="ralph.jpg">
    </div>
    <div class="media-content">
      <p class="title">Ralph The Chocobo</p>
      <p class="subtitle">@chocobo_ralph</p>
    </div>
  </div>
</div>
```

![](/static/screenshots/media.png)
