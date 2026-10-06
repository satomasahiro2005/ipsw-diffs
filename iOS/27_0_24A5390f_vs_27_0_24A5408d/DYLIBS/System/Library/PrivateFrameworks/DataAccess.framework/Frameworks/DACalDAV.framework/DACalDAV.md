## DACalDAV

> `/System/Library/PrivateFrameworks/DataAccess.framework/Frameworks/DACalDAV.framework/DACalDAV`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3677c` | `0x36b4c` | **`+0x3d0`** |
| `__AUTH_CONST.__objc_const` | `0x8c20` | `0x8c50` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x4594` | `0x45bc` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x2800` | `0x2818` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x338` | `0x33c` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-2707.0.0.0.0
+2708.0.0.0.0

-  Functions: 1089
-  Symbols:   2539
+  Functions: 1092
+  Symbols:   2543
Symbols:
+ -[CalDAVMove setSucceeded:]
+ -[CalDAVMove succeeded]
+ -[MobileCalDAVAccountRefreshActor _commitDestinationExternalIDForMoveItem:]
+ GCC_except_table39
+ GCC_except_table42
+ GCC_except_table62
+ GCC_except_table71
+ _OBJC_IVAR_$_CalDAVMove._succeeded
- GCC_except_table38
- GCC_except_table41
- GCC_except_table61
- GCC_except_table70
CStrings:
+ "3"
- "#"
```
