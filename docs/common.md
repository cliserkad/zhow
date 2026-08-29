## Variables

Setting variables
`VAR_A="value"`

Setting an environment variable
`export VAR_B="value"`

Restrict the scope to a function
```zsh
function_a() {
  local VAR_C="value"
  echo $VAR_C
}
```

## Text Editors

To open the default text editor, use $EDITOR or $VISUAL

`$EDITOR file.txt`

`$VISUAL file.txt`
