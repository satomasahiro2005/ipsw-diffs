## BuddyMigrator

> `/System/Library/DataClassMigrators/BuddyMigrator.migrator/BuddyMigrator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2db1c` | `0x2d6b0` | **`-0x46c`** |
| `__TEXT.__objc_methname` | `0x4d93` | `0x4ced` | **`-0xa6`** |
| `__TEXT.__objc_stubs` | `0x3100` | `0x3080` | **`-0x80`** |
| `__TEXT.__dlopen_cstrs` | `0x2ac` | `0x254` | **`-0x58`** |
| `__DATA_CONST.__cfstring` | `0xae0` | `0xaa0` | **`-0x40`** |
| `__DATA.__objc_selrefs` | `0x1130` | `0x1110` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x12f0` | `0x12d0` | **`-0x20`** |
| `__DATA.__bss` | `0x7d0` | `0x7c0` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x1230` | `0x1220` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x2b8` | `0x2ac` | **`-0xc`** |
| `__DATA.__objc_const` | `0x3ac0` | `0x3ab8` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x928` | `0x920` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x4a8` | `0x4a0` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x1c48` | `0x1c40` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xcf8` | `0xcf0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-5411.101.0.0.0
+5411.103.0.0.0

-  - /usr/lib/swift/libswiftSpriteKit.dylib

-  Functions: 1010
-  Symbols:   423
-  CStrings:  1297
+  Functions: 1007
+  Symbols:   421
+  CStrings:  1290
Symbols:
- _BYPrivacyPrivacyPaneIdentifier
- __swift_FORCE_LOAD_$_swiftSpriteKit
CStrings:
+ "BuddyMigrator: Queueing Diagnostics & Usage mini-buddy for auto-opt-in"
+ "Is the multitasking feature applicable: %{bool}d"
+ "Should the multitasking feature flow be shown: %{bool}d"
- "%s isFeatureApplicable: %{bool}d"
- "%s shouldShowFlow: %{bool}d"
- "BuddyMigrator: Queueing Diagnostics & Usage mini-buddy for re-opt-in"
- "BuddyMigrator: Queueing mini-buddy to show the privacy pane"
- "OBBundle"
- "bundleWithIdentifier:"
- "contentVersion"
- "isDataAndPrivacyBundleEnabled"
- "privacyFlow"
- "softlink:r:path:/System/Library/PrivateFrameworks/OnBoardingKit.framework/OnBoardingKit"
```
