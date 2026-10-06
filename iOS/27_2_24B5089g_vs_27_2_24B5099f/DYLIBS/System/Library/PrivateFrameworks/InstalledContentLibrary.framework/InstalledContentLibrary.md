## InstalledContentLibrary

> `/System/Library/PrivateFrameworks/InstalledContentLibrary.framework/InstalledContentLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd3cb8` | `0xd3e20` | **`+0x168`** |
| `__AUTH.__objc_data` | `0x1260` | `0x1148` | **`-0x118`** |
| `__DATA_DIRTY.__objc_data` | `0x4b0` | `0x5c8` | **`+0x118`** |
| `__DATA_DIRTY.__data` | `0x50` | `0xb0` | **`+0x60`** |
| `__AUTH.__data` | `0xd8` | `0x80` | **`-0x58`** |
| `__TEXT.__cstring` | `0x18c2e` | `0x18c7e` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0xd6c0` | `0xd700` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0xac00` | `0xac40` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x5ec4` | `0x5ef4` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x31e8` | `0x3208` | **`+0x20`** |
| `__TEXT.__const` | `0xdb50` | `0xdb40` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x5d0` | `0x5d4` | **`+0x4`** |

### Other Changes

```diff

-1680.40.8.0.1
+1680.40.14.0.0

-  Functions: 2511
-  Symbols:   3889
-  CStrings:  2307
+  Functions: 2513
+  Symbols:   3892
+  CStrings:  2309
Symbols:
+ -[ICLBundleRecord isInstallationHoldActive]
+ -[ICLBundleRecord setIsInstallationHoldActive:]
+ _OBJC_IVAR_$_ICLBundleRecord._isInstallationHoldActive
CStrings:
+ "Failed to get app launch prohibition state from %@ : %@"
+ "isInstallationHoldActive"
```
