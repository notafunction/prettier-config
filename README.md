## Usage

```bash
npm add -D @notafunction/prettier-config
```

### package.json

```json
{
    "prettier": "@notafunction/prettier-config"
}
```

### .prettierrc:

```json
"@notafunction/prettier-config"
```

### Extending .prettierignore:

```bash
prettier . --write --ignore-path node_modules/@notafunction/prettier-config/.prettierignore
```
