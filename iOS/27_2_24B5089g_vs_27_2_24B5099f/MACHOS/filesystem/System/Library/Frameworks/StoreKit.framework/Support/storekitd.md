## storekitd

> `/System/Library/Frameworks/StoreKit.framework/Support/storekitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5dbe78` | `0x5dbc44` | **`-0x234`** |
| `__TEXT.__eh_frame` | `0x376d8` | `0x37808` | **`+0x130`** |
| `__TEXT.__unwind_info` | `0x164c0` | `0x16518` | **`+0x58`** |
| `__TEXT.__cstring` | `0x1eaf5` | `0x1eb45` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x4330` | `0x4370` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x746f` | `0x749f` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x21a8` | `0x21c8` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x71178` | `0x71198` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xc5c0` | `0xc5e0` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0xcc00` | `0xcc18` | **`+0x18`** |
| `__DATA.__data` | `0x13540` | `0x13550` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x18d0` | `0x18e0` | **`+0x10`** |
| `__TEXT.__const` | `0x3f8a0` | `0x3f8b0` | **`+0x10`** |
| `__TEXT.__objc_classname` | `0x26af` | `0x269f` | **`-0x10`** |
| `__TEXT.__objc_methname` | `0x11749` | `0x11759` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x1ec0` | `0x1ed0` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x2f10` | `0x2f1c` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x43f8` | `0x4400` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1080` | `0x1088` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0xbe08` | `0xbe10` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x1004` | `0x100c` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-816.1.14.0.0
+816.1.16.0.0

-  Functions: 38154
-  Symbols:   1810
-  CStrings:  7150
+  Functions: 38160
+  Symbols:   1815
+  CStrings:  7152
Symbols:
+ _$s10Foundation4DateV2geoiySbAC_ACtFZ
+ _$s10Foundation4DateV2leoiySbAC_ACtFZ
+ _$sSd10FoundationE19_bridgeToObjectiveCSo8NSNumberCyF
+ _SecCertificateCopyNotValidAfterDate
+ _SecCertificateCreateWithData
+ _kSecCertificateLifetime
- _$sSL2geoiySbx_xtFZTj
CStrings:
+ "01:01:39"
+ "Failed to read the expiration date of the Octane signing certificate"
+ "Sep 28 2026"
+ "ams_isManagedAppleID"
- "22:45:18"
- "Sep 13 2026"
```
