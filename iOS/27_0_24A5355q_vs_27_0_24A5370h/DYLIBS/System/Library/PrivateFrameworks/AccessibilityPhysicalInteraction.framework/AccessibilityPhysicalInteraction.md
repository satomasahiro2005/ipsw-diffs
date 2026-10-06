## AccessibilityPhysicalInteraction

> `/System/Library/PrivateFrameworks/AccessibilityPhysicalInteraction.framework/AccessibilityPhysicalInteraction`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c3e4` | `0x1c8e4` | **`+0x500`** |
| `__AUTH_CONST.__cfstring` | `0x6e0` | `0x7a0` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x588` | `0x61d` | **`+0x95`** |
| `__TEXT.__cstring` | `0x84e` | `0x8b4` | **`+0x66`** |
| `__DATA_CONST.__const` | `0x778` | `0x7a0` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x1800` | `0x1828` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x190` | `0x1b0` | **`+0x20`** |
| `__TEXT.__const` | `0x4bd` | `0x4cd` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xa30` | `0xa40` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x7e0` | `0x7e8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x20b4` | `0x20bc` | **`+0x8`** |

### Other Changes

```diff

-3229.1.6.0.0
+3232.3.0.0.0

-  Functions: 924
-  Symbols:   1579
-  CStrings:  126
+  Functions: 927
+  Symbols:   1584
+  CStrings:  135
Symbols:
+ -[AXPISystemActionHelper _resolveWebAppBundleIdentifierForBaseBundleID:pid:]
+ GCC_except_table234
+ GCC_except_table243
+ GCC_except_table258
+ GCC_except_table317
+ GCC_except_table702
+ GCC_except_table729
+ _NSClassFromString
+ ___76-[AXPISystemActionHelper _resolveWebAppBundleIdentifierForBaseBundleID:pid:]_block_invoke
+ ___block_descriptor_60_e8_32s40r48r_e12_v24?08^B16lr40l8s32l8r48l8
- GCC_except_table239
- GCC_except_table254
- GCC_except_table315
- GCC_except_table700
- GCC_except_table727
CStrings:
+ "FBSceneManager"
+ "Resolved Web App bundle identifier: %{public}@ (enumerated %lu scenes)"
+ "Skipping focusedApp bundleIdentifier: %@ pid: %d"
+ "Web App lookup: FBSceneManager class=%{public}@ mgr=%{public}@"
+ "bundleIdentifier invoking Reader is %@ pid=%d"
+ "com.apple.webapp"
+ "com.apple.webapp-"
+ "com.apple.webapp.%@"
+ "pid"
+ "sharedInstance"
+ "v24@?0@8^B16"
- "Skipping focusedApp bundleIdentifier: %@"
- "bundleIdentifier invoking Reader is %@"
```
