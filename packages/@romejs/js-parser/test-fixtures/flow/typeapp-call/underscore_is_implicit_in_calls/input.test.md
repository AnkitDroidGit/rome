# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > typeapp-call > underscore_is_implicit_in_calls`

```javascript
Program {
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 19
      line: 3
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  comments: Array [
    CommentLine {
      id: '0'
      value: '@flow'
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 7
          index: 7
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
    }
  ]
  body: Array [
    ExpressionStatement {
      leadingComments: Array ['0']
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 10
          index: 18
          line: 2
        }
        start: Object {
          column: 0
          index: 8
          line: 2
        }
      }
      expression: CallExpression {
        arguments: Array []
        leadingComments: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 9
            index: 17
            line: 2
          }
          start: Object {
            column: 0
            index: 8
            line: 2
          }
        }
        callee: ReferenceIdentifier {
          name: 'test'
          leadingComments: undefined
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 4
              index: 12
              line: 2
            }
            start: Object {
              column: 0
              index: 8
              line: 2
            }
          }
        }
        typeArguments: FlowTypeParameterInstantiation {
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 7
              index: 15
              line: 2
            }
            start: Object {
              column: 4
              index: 12
              line: 2
            }
          }
          params: Array [
            FlowGenericTypeAnnotation {
              id: ReferenceIdentifier {
                name: '_'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 6
                    index: 14
                    line: 2
                  }
                  start: Object {
                    column: 5
                    index: 13
                    line: 2
                  }
                }
              }
              typeParameters: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 6
                  index: 14
                  line: 2
                }
                start: Object {
                  column: 5
                  index: 13
                  line: 2
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