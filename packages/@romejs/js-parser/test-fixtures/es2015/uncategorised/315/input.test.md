# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 315`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "input.js"
		end: Object {
			column: 33
			index: 33
			line: 1
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSForOfStatement {
			await: false
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 33
					index: 33
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			right: JSReferenceIdentifier {
				name: "list"
				loc: Object {
					filename: "input.js"
					identifierName: "list"
					end: Object {
						column: 20
						index: 20
						line: 1
					}
					start: Object {
						column: 16
						index: 16
						line: 1
					}
				}
			}
			left: JSVariableDeclaration {
				kind: "const"
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 12
						index: 12
						line: 1
					}
					start: Object {
						column: 5
						index: 5
						line: 1
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "x"
							loc: Object {
								filename: "input.js"
								identifierName: "x"
								end: Object {
									column: 12
									index: 12
									line: 1
								}
								start: Object {
									column: 11
									index: 11
									line: 1
								}
							}
						}
						init: undefined
						loc: Object {
							filename: "input.js"
							end: Object {
								column: 12
								index: 12
								line: 1
							}
							start: Object {
								column: 11
								index: 11
								line: 1
							}
						}
					}
				]
			}
			body: JSExpressionStatement {
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 33
						index: 33
						line: 1
					}
					start: Object {
						column: 22
						index: 22
						line: 1
					}
				}
				expression: JSCallExpression {
					loc: Object {
						filename: "input.js"
						end: Object {
							column: 32
							index: 32
							line: 1
						}
						start: Object {
							column: 22
							index: 22
							line: 1
						}
					}
					callee: JSReferenceIdentifier {
						name: "process"
						loc: Object {
							filename: "input.js"
							identifierName: "process"
							end: Object {
								column: 29
								index: 29
								line: 1
							}
							start: Object {
								column: 22
								index: 22
								line: 1
							}
						}
					}
					arguments: Array [
						JSReferenceIdentifier {
							name: "x"
							loc: Object {
								filename: "input.js"
								identifierName: "x"
								end: Object {
									column: 31
									index: 31
									line: 1
								}
								start: Object {
									column: 30
									index: 30
									line: 1
								}
							}
						}
					]
				}
			}
		}
	]
}
```
