## HealthRecordsPlugin

> `/System/Library/PrivateFrameworks/HealthRecordsPlugin.framework/HealthRecordsPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x979f` | `0x978f` | **`-0x10`** |

### Other Changes

```diff

-7027.0.64.0.0
+7027.0.67.2.1
CStrings:
+ "SELECT %@, %@, %@ FROM %@ WHERE %@ = ? AND %@ = ? AND %@ = ?"
+ "SELECT %@, %@, %@, %@, %@ FROM %@ WHERE %@ = ? AND %@ = ? AND %@ = ? AND %@ = ? AND (%@ = ? OR %@ > ?)"
+ "SELECT res.%@                     FROM %@ AS res                     LEFT JOIN %@ AS last ON res.%@ = last.%@                     WHERE res.%@ = ? AND (last.%@ < ? OR last.%@ IS NULL)"
+ "SELECT res.%@, res.%@, res.%@, last.%@                     FROM %@ AS res                     LEFT JOIN %@ AS last ON res.%@ = last.%@                     WHERE res.%@ = ?"
- "SELECT %@, %@, %@ FROM %@ WHERE %@ LIKE ? AND %@ LIKE ? AND %@ = ?"
- "SELECT %@, %@, %@, %@, %@ FROM %@ WHERE %@ LIKE ? AND %@ LIKE ? AND %@ = ? AND %@ LIKE ? AND (%@ = ? OR %@ > ?)"
- "SELECT res.%@                     FROM %@ AS res                     LEFT JOIN %@ AS last ON res.%@ = last.%@                     WHERE res.%@ LIKE ? AND (last.%@ < ? OR last.%@ IS NULL)"
- "SELECT res.%@, res.%@, res.%@, last.%@                     FROM %@ AS res                     LEFT JOIN %@ AS last ON res.%@ = last.%@                     WHERE res.%@ LIKE ?"
```
