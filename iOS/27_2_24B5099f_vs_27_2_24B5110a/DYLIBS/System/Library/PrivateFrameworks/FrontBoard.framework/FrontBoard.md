## FrontBoard

> `/System/Library/PrivateFrameworks/FrontBoard.framework/FrontBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0xb690` | `0xb6f8` | **`+0x68`** |
| `__TEXT.__objc_methlist` | `0x5ab0` | `0x5af0` | **`+0x40`** |
| `__TEXT.__text` | `0x844c8` | `0x84508` | **`+0x40`** |
| `__AUTH_CONST.__cfstring` | `0x8ec0` | `0x8ee0` | **`+0x20`** |
| `__TEXT.__cstring` | `0xb4cf` | `0xb4e1` | **`+0x12`** |
| `__DATA_CONST.__objc_selrefs` | `0x3838` | `0x3848` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x958` | `0x95c` | **`+0x4`** |

### Other Changes

```diff

-1153.2.1.0.0
+1153.2.2.0.0

-  Functions: 3172
-  Symbols:   4769
-  CStrings:  1774
+  Functions: 3174
+  Symbols:   4772
+  CStrings:  1775
Symbols:
+ -[FBSceneSnapshotContext isAlternateLayout]
+ -[FBSceneSnapshotContext setAlternateLayout:]
+ _OBJC_IVAR_$_FBSceneSnapshotContext._alternateLayout
CStrings:
+ "isAlternateLayout"
```
