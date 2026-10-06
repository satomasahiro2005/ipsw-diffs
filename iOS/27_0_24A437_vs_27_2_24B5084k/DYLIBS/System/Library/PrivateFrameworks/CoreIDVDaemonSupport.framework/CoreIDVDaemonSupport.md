## CoreIDVDaemonSupport

> `/System/Library/PrivateFrameworks/CoreIDVDaemonSupport.framework/CoreIDVDaemonSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa3660` | `0xa667c` | **`+0x301c`** |
| `__TEXT.__oslogstring` | `0x1e95` | `0x1fe5` | **`+0x150`** |
| `__AUTH_CONST.__const` | `0x4b60` | `0x4bf0` | **`+0x90`** |
| `__AUTH_CONST.__auth_got` | `0x13d0` | `0x1440` | **`+0x70`** |
| `__TEXT.__const` | `0x8210` | `0x8260` | **`+0x50`** |
| `__TEXT.__cstring` | `0x63e9` | `0x6439` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x169c` | `0x16e6` | **`+0x4a`** |
| `__TEXT.__unwind_info` | `0x2d30` | `0x2d68` | **`+0x38`** |
| `__DATA.__data` | `0x1cb8` | `0x1ce0` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x2428` | `0x2444` | **`+0x1c`** |
| `__TEXT.__swift5_fieldmd` | `0x1e58` | `0x1e68` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x290` | `0x294` | **`+0x4`** |

### Other Changes

```diff

-9.42.0.0.0
+9.104.0.0.0

-  Functions: 3849
-  Symbols:   1357
-  CStrings:  715
+  Functions: 3867
+  Symbols:   1363
+  CStrings:  718
Symbols:
+ _swift_bridgeObjectRetain_n
+ _symbolic _____ 20CoreIDVDaemonSupport26AlternativeElementMappingsO
+ _symbolic _____Sg 13CoreIDVShared23ISO18013KnownNamespacesO
+ _symbolic _____Sg 13CoreIDVShared28ISO23220_1_ElementIdentifierO
+ _symbolic _____Sg_ABt 13CoreIDVShared23ISO18013KnownNamespacesO
+ _symbolic _____ySaySS9namespace_SS10identifiertGG s23_ContiguousArrayStorageC
CStrings:
+ "%s:%s is a deprecated identifier that is not allowed in the reader authentication certificate, filtering out of namespaces."
+ "%s:%s is not allowed in the reader authentication certificate and neither is any alternative, filtering out of namespaces."
+ "%s:%s is not allowed in the reader authentication certificate, substituting %s."
+ "namespaces(for:includeNonParsableElements:includeDeprecatedElements:allowableElements:userDefaultsConfiguration:)"
- "namespaces(for:includeNonParsableElements:)"
```
