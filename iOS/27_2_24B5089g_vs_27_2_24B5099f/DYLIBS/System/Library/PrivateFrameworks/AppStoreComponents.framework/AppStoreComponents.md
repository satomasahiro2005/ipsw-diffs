## AppStoreComponents

> `/System/Library/PrivateFrameworks/AppStoreComponents.framework/AppStoreComponents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x90cb4` | `0x90d2c` | **`+0x78`** |
| `__AUTH_CONST.__objc_const` | `0xfa98` | `0xfac8` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x8c3c` | `0x8c54` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x3214` | `0x3226` | **`+0x12`** |
| `__DATA_CONST.__objc_selrefs` | `0x3ef0` | `0x3f00` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x884` | `0x888` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-27.1.7.0.0
+27.1.11.0.0

-  Functions: 3821
-  Symbols:   5959
+  Functions: 3823
+  Symbols:   5962
Symbols:
+ -[ASCLockupView hiddenReason]
+ -[ASCLockupView setHiddenReason:]
+ _OBJC_IVAR_$_ASCLockupView._hiddenReason
Functions:
~ -[ASCLockupView setLockupSize:] : 148 -> 200
~ -[ASCLockupView setHidden:] : 92 -> 8
+ -[ASCLockupView setHiddenReason:]
+ -[ASCLockupView setWebBrowserFlowType:]
CStrings:
+ ":"
+ "Current process is not eligible to use %{public}@ lockup view size, keeping %{public}@ and hiding lockup"
- "*"
- "Current process is not eligible to use %{public}@ lockup view size, keeping %{public}@"
```
