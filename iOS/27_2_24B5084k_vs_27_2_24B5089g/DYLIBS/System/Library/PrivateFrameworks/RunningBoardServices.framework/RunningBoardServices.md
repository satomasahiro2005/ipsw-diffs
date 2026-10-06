## RunningBoardServices

> `/System/Library/PrivateFrameworks/RunningBoardServices.framework/RunningBoardServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x41bf4` | `0x42210` | **`+0x61c`** |
| `__TEXT.__cstring` | `0x4853` | `0x492e` | **`+0xdb`** |
| `__AUTH.__objc_data` | `0x1658` | `0x1590` | **`-0xc8`** |
| `__DATA_DIRTY.__objc_data` | `0x14c8` | `0x1590` | **`+0xc8`** |
| `__AUTH_CONST.__cfstring` | `0x5fc0` | `0x6040` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d68` | `0x1d98` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x5ba8` | `0x5bd8` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1808` | `0x1818` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x4f0` | `0x4f8` | **`+0x8`** |
| `__DATA.__data` | `0x620` | `0x619` | **`-0x7`** |

### Other Changes

```diff

-1084.40.3.0.1
+1084.40.6.0.0

-  Functions: 2329
-  Symbols:   4001
-  CStrings:  1063
+  Functions: 2334
+  Symbols:   4007
+  CStrings:  1067
Symbols:
+ +[RBSProcessIdentity _applicationIdentityMatchingPersona:fromIdentities:]
+ -[RBSProcessIdentity applicationIdentityWithError:]
+ -[RBSProcessMonitorConfiguration _ensureVisibilityNamespaceIsTracked]
+ -[RBSProcessMonitorConfiguration wantsVisibilityChangesOnly]
+ _NSUnderlyingErrorKey
+ __errorWithRequestCode
CStrings:
+ "RBSProcessIdentity does not represent a LSApplicationIdentity"
+ "could not resolve LSApplicationRecord for bundleIdentifier"
+ "could not resolve LSApplicationRecord for jobLabel"
+ "no LSApplicationIdentity in application record"
```
