# Svelte Snippets

This Extension adds snippets for Svelte.

## Features

Snippets for `script`, `markup` and `css` sections.

Example:

`$if` will expand to:

```html
{#if condition}
<!-- content -->
{/if}
```

`$eachindexkey` will expand to:

```html
{#each items as item, index (key)}
<!-- content -->
{/each}
```

`$global` will expand to:

```html
:global() {

}
```

**Many other snippets like:**

`$ifelse`, `$each`, `$eachindex`, `$eachkey`, `$await`, `$awaitthen`, `$import`, `$transition`, `$animate`, `$easing`, `$motion`, `$store`, `$internal`, `$$if`, `$$block`, `$$`, `$onmount`, `$ondestroy`, `$beforeupdate`, `$afterupdate`, `$writable`, `$readable`, `$html`, `$state`, `$derived`, `$effect`, `$effectpre`, `$derived`, `$derivedby`, `$snippet`, `$render`, `$props`, `$bindable`, `$runes`, `$window`, `$body`, `$head`, `$debug`, `$html`, `$element`, `$class`, `$use`, `$self`, `$namespace`, `$accesors`, `$immutable`, `$action`, `$action-params`, `$action-params-update`, `$tick`, `$get-context`, `$set-context`, `$dispatch`, `$dispatch-event`, `$sveltets`, `$doc`, `$modifier`

## Release Notes

### 0.1.2

-   Added `$modifier`, `$get-store`

### 0.1.1

-   Added `$doc`

### 0.1.0

-   Updated README format.
-   Added `$sveltets`

### 0.0.9

-   Fix on filenamePatterns for match only `*.svelte.js` and `*.svelte.ts` files instead of `*.js` and `*.ts` (Remains match on `*.svelte`)
-   Scripts cleanup
-   Added Changelog from 0.0.8 to README

### 0.0.8

-   Added $component, $window, $body, $head, $debug, $html, $element, $class, $use, $self, $namespace, $accessors, $immutable, $action, $action-params, $action-params-update, $tick, $get-context, $set-context, $dispatch, $dispatch-event

### 0.0.7

-   Added Svelte 5 snippets for runes like $state, $derived, $props, $bindable, $effect, $effectpre, $derived, $derivedby and also $snippet, $render and $runes

### 0.0.6

-   Fixed `$eachindex` and `$eachindexkey`

### 0.0.5

-   Snippets should work when working with Typescript

### 0.0.4

-   Fixed `$internal`

### 0.0.3

-   Updated documentation.
-   Added `$html`, `$on`

### 0.0.2

-   Renamed `$svelte` to `$global` for the CSS `global` snippet

### 0.0.1

-   Initial release of Svelte Snippets by MrAmericanMike

---

## Requests - Ideas

Do you have a request or idea for the extension. Please post it on our [Discussion Board](https://github.com/MrAmericanMike/sveltesnippets/discussions) on GitHub

---

## Pending features

Determine if it's possible for a snippets extension to have a configuration option and use it so the final user can decide if they want single or double quotes

---

**Enjoy!**

