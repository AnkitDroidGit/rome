# `restrictedGlobals.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/compiler/lint/rules/js/restrictedGlobals.test.ts --update-snapshots` to update.

## `restricted globals`

### `0`

```

 unknown:1:12 lint/js/restrictedGlobals ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Do not use the global variable event.

    console.log(event);
                ^^^^^

  ℹ Use a local variable instead.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `0: formatted`

```
console.log(event);

```

### `1`

```

 unknown:1:4 lint/js/restrictedGlobals ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Do not use the global variable event.

    foo(event)
        ^^^^^

  ℹ Use a local variable instead.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `1: formatted`

```
foo(event);

```

### `2`

```
✔ No known problems!

```

### `2: formatted`

```
function foo(event) {
	console.info(event);
}

```
