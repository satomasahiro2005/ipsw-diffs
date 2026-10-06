## CarPlaySetup

> `/Applications/CarPlaySetup.app/CarPlaySetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x78e4` | `0x7d04` | **`+0x420`** |
| `__TEXT.__objc_stubs` | `0x12a0` | `0x1320` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x2c11` | `0x2c8b` | **`+0x7a`** |
| `__TEXT.__oslogstring` | `0xc6d` | `0xccc` | **`+0x5f`** |
| `__TEXT.__gcc_except_tab` | `0x44` | `0xa0` | **`+0x5c`** |
| `__DATA_CONST.__const` | `0x428` | `0x478` | **`+0x50`** |
| `__TEXT.__cstring` | `0x1b1` | `0x1e6` | **`+0x35`** |
| `__TEXT.__auth_stubs` | `0x3a0` | `0x3d0` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x240` | `0x268` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x8b0` | `0x8d0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x1e0` | `0x1f8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x178` | `0x188` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-799.3.0.0.0
+807.2.0.0.0

-  Functions: 190
-  Symbols:   122
-  CStrings:  563
+  Functions: 193
+  Symbols:   127
+  CStrings:  569
Symbols:
+ _OBJC_CLASS_$_UITraitHorizontalSizeClass
+ _OBJC_CLASS_$_UITraitVerticalSizeClass
+ _objc_release_x25
+ _objc_retain_x24
+ _objc_unsafeClaimAutoreleasedReturnValue
CStrings:
+ "horizontalSizeClass"
+ "onboarding prompt confirmed, proceeding to car key setup: %{public}@"
+ "presenter deallocated before onboarding was confirmed"
+ "registerForTraitChanges:withHandler:"
+ "setNeedsUpdateOfSupportedInterfaceOrientations"
+ "v24@?0@\"<UITraitEnvironment>\"8@\"UITraitCollection\"16"
+ "verticalSizeClass"
- "Onboarding prompt confirmed"
```
