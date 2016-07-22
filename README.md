
<!---

This README is automatically generated from the comments in these files:
paper-card.html

Edit those files, and our readme bot will duplicate them over here!
Edit this file, and the bot will squash your changes :)

The bot does some handling of markdown. Please file a bug if it does the wrong
thing! https://github.com/PolymerLabs/tedium/issues

-->

[![Build status](https://travis-ci.org/PolymerElements/paper-card.svg?branch=master)](https://travis-ci.org/PolymerElements/paper-card)

_[Demo and API docs](https://elements.polymer-project.org/elements/paper-card)_


##&lt;paper-card&gt;

Material design: [Cards](https://www.google.com/design/spec/components/cards.html)

`paper-card` is a container with a drop shadow.

Amazing inline demo:
<!---
```html
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
  
    <link rel="import" href="../iron-demo-helpers/demo-snippet.html">
    <link rel="import" href="../iron-demo-helpers/demo-pages-shared-styles.html">
  
    <link rel="import" href="../iron-collapse/iron-collapse.html">
    <link rel="import" href="../iron-icons/iron-icons.html">
    <link rel="import" href="../iron-icons/communication-icons.html">
    <link rel="import" href="../iron-icons/hardware-icons.html">
    <link rel="import" href="../iron-icons/social-icons.html">
    <link rel="import" href="../iron-flex-layout/iron-flex-layout.html">
    <link rel="import" href="../paper-button/paper-button.html">
    <link rel="import" href="../paper-checkbox/paper-checkbox.html">
    <link rel="import" href="../paper-icon-button/paper-icon-button.html">
    <link rel="import" href="../paper-styles/color.html">
    <link rel="import" href="../paper-styles/typography.html">
    <link rel="import" href="paper-card.html">
    <style is="custom-style">
      .cafe-header { @apply(--paper-font-headline); }
      .cafe-light { color: var(--paper-grey-600); }
      .cafe-location {
        float: right;
        font-size: 15px;
        vertical-align: middle;
      }
      .cafe-reserve { color: var(--google-blue-500); }
      iron-icon.star {
        --iron-icon-width: 16px;
        --iron-icon-height: 16px;
        color: var(--paper-amber-500);
      }
      iron-icon.star:last-of-type { color: var(--paper-grey-500); }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<paper-card image="demo/donuts.png">
  <div class="card-content">
    <div class="cafe-header">Cafe Basilico
      <div class="cafe-location cafe-light">
        <iron-icon icon="communication:location-on"></iron-icon>
        <span>250ft</span>
      </div>
    </div>
    <div class="cafe-rating">
      <iron-icon class="star" icon="star"></iron-icon>
      <iron-icon class="star" icon="star"></iron-icon>
      <iron-icon class="star" icon="star"></iron-icon>
      <iron-icon class="star" icon="star"></iron-icon>
      <iron-icon class="star" icon="star"></iron-icon>
    </div>
    <p>$・Italian, Cafe</p>
    <p class="cafe-light">Small plates, salads &amp; sandwiches in an intimate setting with 12 indoor seats plus patio seating.</p>
  </div>
  <div class="card-actions">
    <p>Tonight's availability</p>
    <div class="horizontal justified">
      <paper-icon-button icon="icons:event"></paper-icon-button>
      <paper-button>5:30PM</paper-button>
      <paper-button>7:30PM</paper-button>
      <paper-button>9:00PM</paper-button>
    </div>
    <paper-button class="cafe-reserve">Reserve</paper-button>
  </div>
</paper-card>
```
Example:

```html
<paper-card heading="Card Title">
  <div class="card-content">Some content</div>
  <div class="card-actions">
    <paper-button>Some action</paper-button>
  </div>
</paper-card>
```

Example - top card image:

```html
<paper-card heading="Card Title" image="/path/to/image.png" alt="image">
  ...
</paper-card>
```

### Accessibility

By default, the `aria-label` will be set to the value of the `heading` attribute.

### Styling

The following custom properties and mixins are available for styling:

| Custom property | Description | Default |
| --- | --- | --- |
| `--paper-card-background-color` | The background color of the card | `--primary-background-color` |
| `--paper-card-header-color` | The color of the header text | `#000` |
| `--paper-card-header` | Mixin applied to the card header section | `{}` |
| `--paper-card-header-text` | Mixin applied to the title in the card header section | `{}` |
| `--paper-card-header-image` | Mixin applied to the image in the card header section | `{}` |
| `--paper-card-header-image-text` | Mixin applied to the text overlapping the image in the card header section | `{}` |
| `--paper-card-content` | Mixin applied to the card content section | `{}` |
| `--paper-card-actions` | Mixin applied to the card action section | `{}` |
| `--paper-card` | Mixin applied to the card | `{}` |


