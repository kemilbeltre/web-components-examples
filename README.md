# web-components-examples
A series of web components examples, related to the MDN web components documentation at https://developer.mozilla.org/en-US/docs/Web/Web_Components.

The following examples are available:

* [defined-pseudo-class](defined-pseudo-class). A very simple example that shows how the <code>[:defined pseudo-class](https://developer.mozilla.org/en-US/docs/Web/CSS/:defined)</code> works.
* [element-details](element-details) — <code>&lt;element-details&gt;</code>. Displays a box containing an HTML element name and description. Provides an example of an autonomous custom element that gets its structure from a <code>&lt;template&gt;</code> element (that also has its own styling defined), and also contains <code>&lt;slot&gt;</code> elements populated at runtime. [See element-details live](https://mdn.github.io/web-components-examples/element-details/).
* [expanding-list-web-component](expanding-list-web-component) — <code>&lt;ul is="expanding-list"&gt;</code>. Creates an unordered list with expandable/collapsible children. Provides an example of a customized built-in element (the class inherits from <code>HTMLUListElement</code> rather than <code>HTMLElement</code>). [See expanding-list live](https://mdn.github.io/web-components-examples/expanding-list-web-component/).
* [life-cycle-callbacks](life-cycle-callbacks) — <code>&lt;custom-square l="" c=""&gt;</code>. A trivial example web component that creates a square colored box on the page. The demo also includes buttons to create, destroy, and change attributes on the element, to demonstrate how the [web components life cycle callbacks](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_custom_elements#Using_the_lifecycle_callbacks) work [See life-cycle-callbacks live](https://mdn.github.io/web-components-examples/life-cycle-callbacks/).
* [popup-info-box-web-component](popup-info-box-web-component) — <code>&lt;popup-info img="" text=""&gt;</code>. Creates an info icon that when focused displays a popup info box. Provides an example of an autonomous custom element that takes information from its attributes, and defines structure and basic style in an attached shadow DOM. [See popup-info-box live](https://mdn.github.io/web-components-examples/popup-info-box-web-component/).
* [simple-template](simple-template) — A very simple trivial example that quickly demonstrates usage of the <code>&lt;template&gt;</code> and <code>&lt;slot&gt;</code> elements. [See simple-template live](https://mdn.github.io/web-components-examples/simple-template/).
* [word-count-web-component](word-count-web-component) — <code>&lt;word-count&gt;</code>. When added to an element, counts all the words inside that element and displays them inside an attached shadow DOM. It also contains an interval that periodically updates the word count as it changes. Provides an example of a customized built-in element (the class inherits from <code>HTMLParagraphElement</code> rather than <code>HTMLElement</code>). [See word-count live](https://mdn.github.io/web-components-examples/word-count-web-component/).