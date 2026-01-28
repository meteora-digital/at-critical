# at-critical

Adds support for custom `@critical` at-rules in SCSS files, providing syntax highlighting, validation, and IntelliSense support.

```scss
@critical filename.css {
	.class {
		display: block;
	}
}
```

## Features

- **Syntax highlighting** for `@critical` blocks (same styling as `@include`/`@mixin`)
- **Validation suppression** - Eliminates "unknown at-rule" warnings for `@critical`
- **IntelliSense support** - Auto-completion and documentation for `@critical`
- **CSS custom data** integration for proper language service support
- **Filename highlighting** - `filename.css` parameters are highlighted as functions

## Usage

Simply write `@critical filename.css { ... }` blocks in your `.scss` files. The extension provides:

1. **Auto-completion**: Type `@` or `@c` to see `@critical` suggestions
2. **Snippet insertion**: Auto-completes with proper structure and placeholders
3. **Error suppression**: No more red underlines for this custom syntax
4. **Documentation**: Hover information for the `@critical` at-rule

## Configuration

The extension includes the following configurable options:

- `at-critical.enableValidation`: Enable @critical at-rule validation support (default: `true`)
- `at-critical.suppressWarnings`: Suppress 'unknown at-rule' warnings for @critical (default: `true`)

## Publisher

Ranfurly

## License
MIT License
