# `noWillUpdateSetState.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/compiler/lint/rules/react/noWillUpdateSetState.test.ts --update-snapshots` to update.

## `react no will update set state`

### `0`

```

 unknown:4:12 lint/react/noWillUpdateSetState ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Avoid calling this.setState in the componentWillUpdate method.

    2 │         class Hello extends React.Component {
    3 │           componentWillUpdate() {
  > 4 │             this.setState({
      │             ^^^^^^^^^^^^^
    5 │               name: 'John'
    6 │             });

  ℹ Updating state immediately before a scheduled render causes a second render that can causevisual
    layout thrashing.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `0: formatted`

```
class Hello extends React.Component {
	componentWillUpdate() {
		this.setState({
			name: "John",
		});
	}
}

```

### `1`

```

 unknown:5:12 lint/react/noWillUpdateSetState ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Avoid calling this.setState in the componentWillUpdate method.

    3 │           componentWillUpdate() {
    4 │             foo();
  > 5 │             this.setState({
      │             ^^^^^^^^^^^^^
    6 │               name: 'John'
    7 │             });

  ℹ Updating state immediately before a scheduled render causes a second render that can causevisual
    layout thrashing.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `1: formatted`

```
class Hello extends React.Component {
	componentWillUpdate() {
		foo();
		this.setState({
			name: "John",
		});
	}
}

```

### `2`

```

 unknown:4:12 lint/react/noWillUpdateSetState ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Avoid calling this.setState in the componentWillUpdate method.

    2 │         class Hello extends Component {
    3 │           componentWillUpdate() {
  > 4 │             this.setState({
      │             ^^^^^^^^^^^^^
    5 │               name: 'John'
    6 │             });

  ℹ Updating state immediately before a scheduled render causes a second render that can causevisual
    layout thrashing.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `2: formatted`

```
class Hello extends Component {
	componentWillUpdate() {
		this.setState({
			name: "John",
		});
	}
}

```

### `3`

```

 unknown:5:12 lint/react/noWillUpdateSetState ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Avoid calling this.setState in the componentWillUpdate method.

    3 │           componentWillUpdate() {
    4 │             foo();
  > 5 │             this.setState({
      │             ^^^^^^^^^^^^^
    6 │               name: 'John'
    7 │             });

  ℹ Updating state immediately before a scheduled render causes a second render that can causevisual
    layout thrashing.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `3: formatted`

```
class Hello extends Component {
	componentWillUpdate() {
		foo();
		this.setState({
			name: "John",
		});
	}
}

```

### `4`

```

 unknown:4:12 lint/react/noWillUpdateSetState ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Avoid calling this.setState in the componentWillUpdate method.

    2 │         class Hello extends React.Component {
    3 │           UNSAFE_componentWillUpdate() {
  > 4 │             this.setState({
      │             ^^^^^^^^^^^^^
    5 │               name: 'John'
    6 │             });

  ℹ Updating state immediately before a scheduled render causes a second render that can causevisual
    layout thrashing.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `4: formatted`

```
class Hello extends React.Component {
	UNSAFE_componentWillUpdate() {
		this.setState({
			name: "John",
		});
	}
}

```

### `5`

```

 unknown:4:12 lint/react/noWillUpdateSetState ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Avoid calling this.setState in the componentWillUpdate method.

    2 │         class Hello extends Component {
    3 │           UNSAFE_componentWillUpdate() {
  > 4 │             this.setState({
      │             ^^^^^^^^^^^^^
    5 │               name: 'John'
    6 │             });

  ℹ Updating state immediately before a scheduled render causes a second render that can causevisual
    layout thrashing.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `5: formatted`

```
class Hello extends Component {
	UNSAFE_componentWillUpdate() {
		this.setState({
			name: "John",
		});
	}
}

```

### `6`

```
✔ No known problems!

```

### `6: formatted`

```
class Hello extends React.Component {
	componentWillUpdate() {
		if (condition) {
			this.setState({
				name: "John",
			});
		}
	}
}

```

### `7`

```
✔ No known problems!

```

### `7: formatted`

```
class Hello extends React.Component {
	componentWillUpdate() {
		condition &&
		this.setState({
			name: "John",
		});
	}
}

```

### `8`

```
✔ No known problems!

```

### `8: formatted`

```
class Hello extends React.Component {
	componentWillUpdate() {
		condition
			? this.setState({
					name: "John",
				})
			: undefined;
	}
}

```
