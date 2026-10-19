## CoreMediaIO

> `/System/Library/Frameworks/CoreMediaIO.framework/CoreMediaIO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3eb2c` | `0x3ecf8` | **`+0x1cc`** |
| `__TEXT.__oslogstring` | `0x4266` | `0x4280` | **`+0x1a`** |

### Other Changes

```diff

-  CStrings:  1035
+  CStrings:  1036
Functions:
~ -[CMIOExtensionProviderHostContext setStreamPropertyValuesWithStreamID:propertyValues:reply:] : 704 -> 1164
CStrings:
+ "%s:%d:%s SetProperty - %@"
```
