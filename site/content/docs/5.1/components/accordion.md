---
layout: docs
title: Accordion
description: Build vertically collapsing accordions in combination with our Collapse JavaScript plugin.
group: components
aliases:
  - "/components/"
  - "/docs/5.1/components/"
toc: true
---

## How it works

The accordion uses [collapse]({{< docsref "/components/collapse" >}}) internally to make it collapsible. To render an accordion that's expanded, add the `.open` class on the `.accordion`.

{{< callout info >}}
{{< partial "callout-info-prefersreducedmotion.md" >}}
{{< /callout >}}

## Example

Click the accordions below to expand/collapse the accordion content.

{{< example >}}
<div class="accordion" id="accordionExample">
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingOne">
      <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
        Accordion Item #1
      </button>
    </h2>
    <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>This is the first item's accordion body.</strong> It is shown by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingTwo">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
        Accordion Item #2
      </button>
    </h2>
    <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>This is the second item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingThree">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
        Accordion Item #3
      </button>
    </h2>
    <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>This is the third item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
</div>
{{< /example >}}

<!-- Boosted mod: no .accordion flush -->

### Sizes

Add `.accordion-lg` or `.accordion-sm` for additional sizes.

{{< example >}}
<div class="row">
  <div class="col-md-6 col-lg-5">
    <div class="accordion accordion-sm" id="accordionExampleSmall">
      <div class="accordion-item">
        <h2 class="accordion-header" id="headingOneSmall">
          <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOneSmall" aria-expanded="true" aria-controls="collapseOneSmall">
            Accordion Item #1
          </button>
        </h2>
        <div id="collapseOneSmall" class="accordion-collapse collapse show" aria-labelledby="headingOneSmall" data-bs-parent="#accordionExampleSmall">
          <div class="accordion-body">
            <strong>This is the first item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
          </div>
        </div>
      </div>
      <div class="accordion-item">
        <h2 class="accordion-header" id="headingTwoSmall">
          <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwoSmall" aria-expanded="false" aria-controls="collapseTwoSmall">
            Accordion Item #2
          </button>
        </h2>
        <div id="collapseTwoSmall" class="accordion-collapse collapse" aria-labelledby="headingTwoSmall" data-bs-parent="#accordionExampleSmall">
          <div class="accordion-body">
            <strong>This is the second item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
          </div>
        </div>
      </div>
      <div class="accordion-item">
        <h2 class="accordion-header" id="headingThreeSmall">
          <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThreeSmall" aria-expanded="false" aria-controls="collapseThreeSmall">
            Accordion Item #3
          </button>
        </h2>
        <div id="collapseThreeSmall" class="accordion-collapse collapse" aria-labelledby="headingThreeSmall" data-bs-parent="#accordionExampleSmall">
          <div class="accordion-body">
            <strong>This is the third item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="col-md-6 col-lg-7">
    <div class="accordion accordion-lg" id="accordionExampleLarge">
      <div class="accordion-item">
        <h2 class="accordion-header" id="headingOneLarge">
          <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOneLarge" aria-expanded="true" aria-controls="collapseOneLarge">
            Accordion Item #1
          </button>
        </h2>
        <div id="collapseOneLarge" class="accordion-collapse collapse show" aria-labelledby="headingOneLarge" data-bs-parent="#accordionExampleLarge">
          <div class="accordion-body">
            <strong>This is the first item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
          </div>
        </div>
      </div>
      <div class="accordion-item">
        <h2 class="accordion-header" id="headingTwoLarge">
          <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwoLarge" aria-expanded="false" aria-controls="collapseTwoLarge">
            Accordion Item #2
          </button>
        </h2>
        <div id="collapseTwoLarge" class="accordion-collapse collapse" aria-labelledby="headingTwoLarge" data-bs-parent="#accordionExampleLarge">
          <div class="accordion-body">
            <strong>This is the second item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
          </div>
        </div>
      </div>
      <div class="accordion-item">
        <h2 class="accordion-header" id="headingThreeLarge">
          <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThreeLarge" aria-expanded="false" aria-controls="collapseThreeLarge">
            Accordion Item #3
          </button>
        </h2>
        <div id="collapseThreeLarge" class="accordion-collapse collapse" aria-labelledby="headingThreeLarge" data-bs-parent="#accordionExampleLarge">
          <div class="accordion-body">
            <strong>This is the third item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
{{< /example >}}

### Always open

Omit the `data-bs-parent` attribute on each `.accordion-collapse` to make accordion items stay open when another item is opened.

{{< example >}}
<div class="accordion" id="accordionPanelsStayOpenExample">
  <div class="accordion-item">
    <h2 class="accordion-header" id="panelsStayOpen-headingOne">
      <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#panelsStayOpen-collapseOne" aria-expanded="true" aria-controls="panelsStayOpen-collapseOne">
        Accordion Item #1
      </button>
    </h2>
    <div id="panelsStayOpen-collapseOne" class="accordion-collapse collapse show" aria-labelledby="panelsStayOpen-headingOne">
      <div class="accordion-body">
        <strong>This is the first item's accordion body.</strong> It is shown by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="panelsStayOpen-headingTwo">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#panelsStayOpen-collapseTwo" aria-expanded="false" aria-controls="panelsStayOpen-collapseTwo">
        Accordion Item #2
      </button>
    </h2>
    <div id="panelsStayOpen-collapseTwo" class="accordion-collapse collapse" aria-labelledby="panelsStayOpen-headingTwo">
      <div class="accordion-body">
        <strong>This is the second item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="panelsStayOpen-headingThree">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#panelsStayOpen-collapseThree" aria-expanded="false" aria-controls="panelsStayOpen-collapseThree">
        Accordion Item #3
      </button>
    </h2>
    <div id="panelsStayOpen-collapseThree" class="accordion-collapse collapse" aria-labelledby="panelsStayOpen-headingThree">
      <div class="accordion-body">
        <strong>This is the third item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
</div>
{{< /example >}}

### Dark variant

Accordions come with a dark variant: `.accordion-dark`.

{{< example >}}
<div class="accordion accordion-dark" id="accordionPanelsDarkExample">
  <div class="accordion-item">
    <h2 class="accordion-header" id="panelsDark-headingOne">
      <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#panelsDark-collapseOne" aria-expanded="true" aria-controls="panelsDark-collapseOne">
        Accordion Item #1
      </button>
    </h2>
    <div id="panelsDark-collapseOne" class="accordion-collapse collapse show" aria-labelledby="panelsDark-headingOne" data-bs-parent="#accordionPanelsDarkExample">
      <div class="accordion-body">
        <strong>This is the first item's accordion body.</strong> It is shown by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="panelsDark-headingTwo">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#panelsDark-collapseTwo" aria-expanded="false" aria-controls="panelsDark-collapseTwo">
        Accordion Item #2
      </button>
    </h2>
    <div id="panelsDark-collapseTwo" class="accordion-collapse collapse" aria-labelledby="panelsDark-headingTwo" data-bs-parent="#accordionPanelsDarkExample">
      <div class="accordion-body">
        <strong>This is the second item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="panelsDark-headingThree">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#panelsDark-collapseThree" aria-expanded="false" aria-controls="panelsDark-collapseThree">
        Accordion Item #3
      </button>
    </h2>
    <div id="panelsDark-collapseThree" class="accordion-collapse collapse" aria-labelledby="panelsDark-headingThree" data-bs-parent="#accordionPanelsDarkExample">
      <div class="accordion-body">
        <strong>This is the third item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
</div>
{{< /example >}}

## Accessibility

Please read the [collapse accessibility section]({{< docsref "/components/collapse#accessibility" >}}) for more information.

## Sass

### Variables

{{< scss-docs name="accordion-variables" file="scss/_variables.scss" >}}
