
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

Example:
<!---
```html
<script src="../webcomponentsjs/webcomponents-lite.js"></script>
<link rel="import" href="../iron-icons/iron-icons.html">
<link rel="import" href="../iron-icons/communication-icons.html">
<link rel="import" href="../paper-button/paper-button.html">
<link rel="import" href="../paper-icon-button/paper-icon-button.html">
<link rel="import" href="../paper-styles/color.html">
<link rel="import" href="../paper-styles/typography.html">
<link rel="import" href="paper-card.html">
<style is="custom-style">
  paper-card {
    max-width: 500px;
  }
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
    <p class="cafe-light">Small plates, salads &amp; sandwiches in an intimate setting.</p>
  </div>
  <div class="card-actions">
    <div class="horizontal justified">
      <paper-icon-button icon="icons:event"></paper-icon-button>
      <paper-button>5:30PM</paper-button>
      <paper-button>7:30PM</paper-button>
      <paper-button>9:00PM</paper-button>
      <paper-button class="cafe-reserve">Reserve</paper-button>
    </div>
  </div>
</paper-card>
```
