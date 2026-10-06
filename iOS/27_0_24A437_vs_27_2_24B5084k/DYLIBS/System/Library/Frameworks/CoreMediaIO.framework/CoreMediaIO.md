## CoreMediaIO

> `/System/Library/Frameworks/CoreMediaIO.framework/CoreMediaIO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ecf8` | `0x3eb2c` | **`-0x1cc`** |
| `__TEXT.__oslogstring` | `0x4280` | `0x4266` | **`-0x1a`** |

### Other Changes

```diff

-5634.0.0.0.0
+5634.40.2.0.0

-  CStrings:  1036
+  CStrings:  1035
Functions:
~ -[CMIOExtensionProviderHostContext setStreamPropertyValuesWithStreamID:propertyValues:reply:] : 1164 -> 704
CStrings:
- "%s:%d:%s SetProperty - %@"
```
