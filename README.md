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
:global() { }
```

**Many other snippets like:**

`$ifelse`, `$each`, `$eachindex`, `$eachkey`, `$await`, `$awaitthen`, `$import`, `$transition`, `$animate`, `$easing`, `$motion`, `$store`, `$internal`, `$$if`, `$$block`, `$$`, `$onmount`, `$ondestroy`, `$beforeupdate`, `$afterupdate`, `$writable`, `$readable`, `$html`, `$state`, `$derived`, `$effect`, `$effectpre`, `$derived`, `$derivedby`, `$snippet`, `$render`, `$props`, `$bindable`, `$runes`

## Release Notes

### 0.0.7

Added Svelte 5 snippets for runes like $state, $derived, $props, $bindable, $effect, $effectpre, $derived, $derivedby and also $snippet, $render and $runes

### 0.0.6

Fixed `$eachindex` and `$eachindexkey`

### 0.0.5

Snippets should work when working with Typescript

### 0.0.4

Fixed `$internal`

### 0.0.3

Updated documentation. Added `$html`, `$on`

### 0.0.2

Renamed `$svelte` to `$global` for the CSS `global` snippet

### 0.0.1

Initial release of Svelte Snippets by MrAmericanMike

---

## Requests - Ideas

Do you have a request or idea for the extension. Please post it on our [Discussion Board](https://github.com/MrAmericanMike/sveltesnippets/discussions) on GitHub

---

## Pending features

Determine if it's possible for a snippets extension to have a configuration option and use it so the final user can decide if they want single or double quotes

---

**Enjoy!**

