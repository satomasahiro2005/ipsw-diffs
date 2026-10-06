## AppServerSupport

> `/System/Library/PrivateFrameworks/AppServerSupport.framework/AppServerSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7d50` | `0x7e1c` | **`+0xcc`** |
| `__AUTH_CONST.__objc_const` | `0x1840` | `0x1870` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xb2c` | `0xb54` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x680` | `0x690` | **`+0x10`** |
| `__TEXT.__const` | `0x80` | `0x88` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x200` | `0x1f8` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x120` | `0x124` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-3298.2.1.0.0
+3298.40.20.0.0

-  Functions: 200
-  Symbols:   525
+  Functions: 203
+  Symbols:   529
Symbols:
+ +[OSLaunchdJob _createSubmitExtensionRequest:overlay:domain:properties:]
+ +[OSLaunchdJob _submitExtension:overlay:domain:properties:error:]
+ -[OSLaunchdJobProperties label]
+ -[OSLaunchdJobProperties setLabel:]
+ _OBJC_IVAR_$_OSLaunchdJobProperties._label
- +[OSLaunchdJob _submitExtension:overlay:domain:error:]
```
