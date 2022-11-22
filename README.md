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

`$ifelse`, `$each`, `$eachindex`, `$eachkey`, `$await`, `$awaitthen`, `$import`, `$transition`, `$animate`, `$easing`, `$motion`, `$store`, `$internal`, `$$if`, `$$block`, `$$`, `$onmount`, `$ondestroy`, `$beforeupdate`, `$afterupdate`, `$writable`, `$readable`, `$html`

## Release Notes

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

