## CalDAV

> `/System/Library/PrivateFrameworks/CalDAV.framework/CalDAV`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37658` | `0x3771c` | **`+0xc4`** |
| `__AUTH_CONST.__objc_const` | `0x9f38` | `0x9f60` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x2c18` | `0x2c20` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x4f2c` | `0x4f34` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x624` | `0x628` | **`+0x4`** |

### Other Changes

```diff

-1166.0.0.0.0
+1166.1.1.0.0

-  Functions: 1513
-  Symbols:   3282
+  Functions: 1514
+  Symbols:   3285
Symbols:
+ -[CalDAVGetCalendarItemTask initWithURL:appSpecificCalendarItemClass:]
+ _OBJC_IVAR_$_CalDAVGetCalendarItemTask._appSpecificCalendarItemClass
+ __OBJC_$_INSTANCE_VARIABLES_CalDAVGetCalendarItemTask
```
