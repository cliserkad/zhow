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

## Determine if command is available

Posix compliant

```zsh
if command -v your_command &> /dev/null; then
  echo "We can use it!"
fi
```

Using `which` utility

```zsh
if which your_command &> /dev/null; then
  echo "We can use it!"
fi
```
