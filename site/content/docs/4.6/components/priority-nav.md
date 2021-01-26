---
layout: docs
title: Orange priority nav
description: Add a "more" button when space for navigation items runs short
group: components
toc: true
---

## Scope

The priority nav plugin can be used on [local navigation]({{< docsref "/components/local-navigation" >}}), [navigation tabs]({{< docsref "/components/navs#tabs" >}}) and [navigation pills]({{< docsref "/components/navs#pills" >}}).

## Usage

The plugin is initialised via Javascript.

```js
$('.o-nav-local').prioritynav();
```

## Example

Reduce the width of your browser to see overflowing navigation items moved into a nice dropdown menu.

{{< example >}}
<nav role="navigation" class="o-nav-local navbar-light">
  <ul class="container nav">
    <li class="nav-item"><a class="nav-link active" aria-current="page" href="#">Home</a></li>
    <li class="nav-item"><a class="nav-link" href="#">Introduction</a></li>
    <li class="nav-item"><a class="nav-link" href="#">Usage</a></li>
    <li class="nav-item"><a class="nav-link" href="#">References</a></li>
    <li class="nav-item"><a class="nav-link" href="#">Shopping</a></li>
    <li class="nav-item"><a class="nav-link" href="#">Organisation</a></li>
    <li class="nav-item"><a class="nav-link" href="#">Worldwilde</a></li>
    <li class="nav-item"><a class="nav-link" href="#">Contact Us</a></li>
  </ul>
</nav>
{{< /example >}}

## Options

Used with no parameter, the label 'More' is used as default. For custom labeling use the following:

```js
$('.o-nav-local').prioritynav('Custom label');
```