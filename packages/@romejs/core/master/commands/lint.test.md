# `lint.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/core/master/commands/lint.test.ts --update-snapshots` to update.

## `smoke`

### `console`

```
[2K[1G[2K[1G[2K[1G
 project/index.js:1 lint/js/undeclaredVariables ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ The unknownVariable variable is undeclared.

    unknownVariable
    ^^^^^^^^^^^^^^^

 project/index.js lint/pendingFixes FIXABLE ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Pending formatting and recommended autofixes

     1 │ + unknownVariable;
     2 │ + 

  ℹ To apply fixes and formatting run
  $ rome lint index.js --save 

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

ℹ Fixes available. To apply recommended fixes and formatting run
$ rome lint --save
ℹ To choose fix suggestions run
$ rome lint --review
✖ Found 2 problems

```

### `files`

```
# index.js
unknownVariable

# rome.json
{
	"files": {
		"vendorPath": "../remote"
	}
}

```

## `smoke save`

### `console`

```
[2K[1G[2K[1G[2K[1G
 project/index.js:1:4 lint/js/undeclaredVariables OUTDATED ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ The unformatted variable is undeclared.

  > 1 │ if (unformatted) {
      │     ^^^^^^^^^^^
    2 │  swag;
    3 │ }

  ⚠ This file has been changed since the diagnostic was produced and may be out of date

 project/index.js:2:1 lint/js/undeclaredVariables OUTDATED ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ The swag variable is undeclared.

    1 │ if (unformatted) {
  > 2 │  swag;
      │  ^^^^
    3 │ }

  ⚠ This file has been changed since the diagnostic was produced and may be out of date

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✔ 1 file updated
✖ Found 2 problems

```

### `files`

```
# index.js
if (unformatted) {
	swag;
}

# rome.json
{
	"files": {
		"vendorPath": "../remote"
	}
}

```
