## backgroundassets.user

> `/usr/libexec/backgroundassets.user`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5a458` | `0x5abe4` | **`+0x78c`** |
| `__TEXT.__oslogstring` | `0x6db3` | `0x6f94` | **`+0x1e1`** |
| `__TEXT.__auth_stubs` | `0x1900` | `0x1970` | **`+0x70`** |
| `__TEXT.__objc_stubs` | `0x7800` | `0x7860` | **`+0x60`** |
| `__TEXT.__cstring` | `0x41e0` | `0x4230` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x9c6e` | `0x9cae` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0xc90` | `0xcc8` | **`+0x38`** |
| `__TEXT.__eh_frame` | `0x4f8` | `0x530` | **`+0x38`** |
| `__TEXT.__const` | `0x1ac8` | `0x1ae8` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x21a8` | `0x21b8` | **`+0x10`** |
| `__DATA.__data` | `0x12e0` | `0x12e8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x5c0` | `0x5c8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1448` | `0x1450` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x6ee` | `0x6f4` | **`+0x6`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-279.0.1.0.0
+279.0.5.0.0

-  Functions: 1944
-  Symbols:   696
-  CStrings:  2613
+  Functions: 1948
+  Symbols:   704
+  CStrings:  2619
Symbols:
+ _$s10Foundation6LocaleV8LanguageVSHAAMc
+ _$sSH13_rawHashValue4seedS2i_tFTj
+ _$sSa11descriptionSSvg
+ _swift_bridgeObjectRetain_n
+ _swift_release_x27
+ _swift_retain_n
+ _swift_retain_x27
+ _swift_setDeallocating
CStrings:
+ "<Localized Asset Packs Lookup Descriptor | For current profile>"
+ "An empty string was previously recorded as the team identifier for the application with the bundle identifier “%{public}@”; recording “%{public}@” for it…"
+ "Localized asset packs with lookup descriptor: %{public}s"
+ "No team identifier has been previously recorded for the application with the bundle identifier “%{public}@”; recording “%{public}@” for it…"
+ "Resolved language from: %{public}s profile-specific preferred languages: %{public}s"
+ "Resolved language profile-specific preferred languages: %{public}s"
+ "The available language%s %{public}s."
+ "The preferred language%s %{public}s."
+ "allowsConstrainedNetworkAccess"
+ "com.apple.distnoted.matching.trusted"
+ "setAllowsConstrainedNetworkAccess:"
- "Resolved language"
- "Resolved language from: %{public}s"
- "The available languages are %{public}s."
- "The preferred languages are %{public}s."
- "com.apple.distnoted.matching"
```
