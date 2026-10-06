## SpringBoardHome

> `/System/Library/PrivateFrameworks/SpringBoardHome.framework/SpringBoardHome`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x38ad98` | `0x38b490` | **`+0x6f8`** |
| `__TEXT.__oslogstring` | `0xf170` | `0xf320` | **`+0x1b0`** |
| `__AUTH_CONST.__objc_const` | `0x58d60` | `0x58d98` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x3eba4` | `0x3ebd4` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x16e00` | `0x16e20` | **`+0x20`** |
| `__DATA.__data` | `0x9618` | `0x9638` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1cb40` | `0x1cb58` | **`+0x18`** |
| `__TEXT.__cstring` | `0x18ae3` | `0x18af3` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xf860` | `0xf870` | **`+0x10`** |
| `__AUTH.__data` | `0xc58` | `0xc60` | **`+0x8`** |
| `__AUTH_CONST.__auth_got` | `0x1d80` | `0x1d88` | **`+0x8`** |

### Other Changes

```diff

-226.0.2.0.0
+226.0.4.0.0

-  Functions: 24683
-  Symbols:   33633
-  CStrings:  4569
+  Functions: 24687
+  Symbols:   33636
+  CStrings:  4575
Symbols:
+ -[SBHCalendarApplicationIcon makeIconLayerWithInfo:traitCollection:context:options:]
+ -[SBHIconManager iconModel:shouldConsiderDefaultLocationAsDesignatedForIconWithIdentifier:]
+ GCC_except_table1064
+ GCC_except_table1118
+ GCC_except_table1120
+ GCC_except_table1136
+ GCC_except_table1143
+ _os_variant_has_internal_diagnostics
- GCC_except_table1063
- GCC_except_table1116
- GCC_except_table1119
- GCC_except_table1135
- GCC_except_table1142
CStrings:
+ "Added icon based on default icon state"
+ "Calendar icon image provider changed; date is now %{public}@ in time zone %{public}@, notifying delegate: %{public}@"
+ "Calendar icon image provider observing %{public}@; date is %{public}@ in time zone %{public}@"
+ "Calendar icon image provider stopping observation of significant time change notification: %{public}@"
+ "Calendar icon rendering layer at %.0fx%.0f@%.0fx as %{public}@"
+ "com.apple.SiriApp"
```
