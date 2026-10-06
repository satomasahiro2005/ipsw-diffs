## MobileMailUI

> `/System/Library/PrivateFrameworks/MobileMailUI.framework/MobileMailUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ec7c` | `0x4e92c` | **`-0x350`** |
| `__TEXT.__gcc_except_tab` | `0x9938` | `0x98c0` | **`-0x78`** |
| `__TEXT.__cstring` | `0x349c` | `0x342c` | **`-0x70`** |
| `__AUTH_CONST.__cfstring` | `0x31a0` | `0x3140` | **`-0x60`** |
| `__AUTH_CONST.__objc_const` | `0x8028` | `0x7fd8` | **`-0x50`** |
| `__TEXT.__oslogstring` | `0x2397` | `0x2367` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x2a80` | `0x2a58` | **`-0x28`** |
| `__TEXT.__objc_methlist` | `0x5314` | `0x5304` | **`-0x10`** |
| `__DATA_CONST.__const` | `0x1378` | `0x1370` | **`-0x8`** |
| `__DATA_CONST.__got` | `0xb50` | `0xb48` | **`-0x8`** |
| `__DATA_CONST.__objc_catlist` | `0x30` | `0x28` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x4250` | `0x4258` | **`+0x8`** |
| `__TEXT.__swift5_reflstr` | `0x3a` | `0x41` | **`+0x7`** |

### Same-size Content Changes

- `__TEXT.__ustring`

### Other Changes

```diff

-3901.100.1.2.14
+3901.200.34.0.0

-  - /System/Library/PrivateFrameworks/MIME.framework/MIME

-  Functions: 1767
-  Symbols:   3590
-  CStrings:  682
+  Functions: 1764
+  Symbols:   3583
+  CStrings:  678
Symbols:
- -[NSError(MessageContentView) mf_markupString]
- _EMErrorDomain
- _MFMIMEErrorDomain
- __OBJC_$_CATEGORY_INSTANCE_METHODS_NSError_$_MessageContentView
- __OBJC_$_CATEGORY_NSError_$_MessageContentView
- __OBJC_$_PROP_LIST_NSError_$_MessageContentView
- _messageForFragment
CStrings:
- "<html dir=auto><body><i><font color=#888>%@</font></i></body></html>"
- "Failed to find a message for error: %{public}@"
- "MESSAGE_CAUSED_PROBLEM"
- "MESSAGE_UNAVAILABLE"
```
