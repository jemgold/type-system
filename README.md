# type-system
towards composable web typography


## notes
```
const styles = compose(
  dropCap(),
  alignment(…),
  maxLines(2),
  textFit({
    scale: [
      …
    ]
  })
)(text)
