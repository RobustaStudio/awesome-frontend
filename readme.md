# Awesome Frontend

Collection of awesome tools and libraries for building interfaces.

## Animation and Parallax

* [Lax.js](https://github.com/alexfoxy/lax.js)

  <details><summary>Details</summary>

  > Simple & light weight (3kb minified & zipped) vanilla javascript plugin to create smooth & beautiful animations when you scrolllll! Harness the power of the most intuitive interaction and make your websites come alive!

  Mainly used to create parallax effects

  **Pros**

  * Predefined sets for parallax with very simple configuration rules
  * Can be enabled / disabled / reinitialized (for window resize)
  * Support custom animation rules

  **Cons**

  * Custom animations are not easy to configure
  * Cannot define a threshold for the predefined sets
  </details>

## UI components

### Images comparison

* [Image Compare Viewer](https://image-compare-viewer.netlify.app/)

  <details><summary>Details</summary>

  > Compare before and after images, for grading, CGI and other retouching comparisons. Vanilla Javascript, zero dependencies.

  **Pros**

  * Dependency Free
  * Works very well on mobile and touch friendly devices
  * Support vertical and horizontal modes
  * Simple markup and simple setup
  * Actively maintained
  </details>

### Sliders

* [Swiper.js](https://swiperjs.com/)

  <details><summary>Details</summary>

  > The most modern mobile touch slider

  **Pros**

  * Dependency Free
  * Works very well on mobile and touch friendly devices
  * Easy to define bullets and navigation buttons
  * Support RTL
  * Different modes like fixed number of slides, auto width, variable height, free mode, multi-row, nested sliders ...
  * Allow spaces between slides
  * Built-in lazy loading
  * Expose events
  </details>

## Utilities

* [in-view.js](https://github.com/camwiegert/in-view)

  <details><summary>Details</summary>

  > Get notified when a DOM element enters or exits the viewport. A small (~1.9kb gzipped), dependency-free, javascript utility for IE9+.

  **Pros**

  * Dependency Free, small in size
  * Dead simple to implement
  
  **Cons**
  
  * Original author archived the repository, this means it's deprecated and won't recieve fixes and updates
  * Use MutationObserver. Currently IntersectionObserver is way more performant
  * Some options like `threshold` cannot be defined per instance. It's global
  </details>

 * [NanoID](https://zelark.github.io/nano-id-cc/)

<details><summary>Details</summary>

> NanoID is a tiny, secure, URL-friendly, unique string ID generator for JavaScript. It’s a great alternative to UUID, optimized for speed and small bundle size.

**Pros**

* Super lightweight (less than 1KB)  
* Extremely fast ID generation  
* Perfect for client-side apps, especially React  
* No dependencies  
* Secure: uses cryptographic random values  
* Great for generating user IDs, keys, filenames, etc.

</details>

## Vue

Use these when shopping for Vue libraries.

### UI Utilities

#### Form Validation

* [vee-validate](https://github.com/logaretm/vee-validate)

  <details><summary>Details</summary>

  > Template Driven Validation Framework for Vue.js

  **Pros**

  * Dependency Free
  * Actively Maintained
  * Localization Support
  * Async and Custom Rules Support
  </details>

#### I18n

* [vue-i18n](https://kazupon.github.io/vue-i18n/)

  <details><summary>Details</summary>

  > Vue I18n is internationalization plugin for Vue.js

  **Pros**

  * Most Popular
  * Actively Maintained
  * App-level translations as well as component-level translations

  **for Nuxt use the `nuxt-i18n` module that uses this under the hood.**

  </details>

### UI components

### Sliders

* [hooper](https://github.com/baianat/hooper)

  <details><summary>Details</summary>

  > A customizable accessible carousel slider optimized for Vue

  **Cons**

  * No longer maintained

  **Pros**

  * Most Popular
  * Touch, Keyboard, Mouse Wheel, and Navigation support
  * SSR Support
  * Easily customizable through rich API and addons

  </details>
