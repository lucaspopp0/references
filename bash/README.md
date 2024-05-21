# bash

## for loops

#### loop through array

```bash
for fruit in "${fruits[@]}"; do
  echo "$fruit"
done
```

#### loop through lines in variable

```bash
while IFS='' read -r line || [[ -n "$line" ]]; do
    echo "$line"
done <<< "$multiline_var"
```
