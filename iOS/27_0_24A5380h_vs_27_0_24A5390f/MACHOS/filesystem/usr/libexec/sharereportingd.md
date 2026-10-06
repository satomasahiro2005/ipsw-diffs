## sharereportingd

> `/usr/libexec/sharereportingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x446dc` | `0x44bc4` | **`+0x4e8`** |
| `__TEXT.__auth_stubs` | `0x1470` | `0x14d0` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0xbbd` | `0xc0f` | **`+0x52`** |
| `__DATA.__data` | `0x17f0` | `0x1830` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0xa40` | `0xa70` | **`+0x30`** |
| `__TEXT.__cstring` | `0x2837` | `0x2867` | **`+0x30`** |
| `__TEXT.__const` | `0x3a68` | `0x3a48` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0x7c0` | `0x7a0` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x28e8` | `0x28d0` | **`-0x18`** |
| `__TEXT.__swift5_fieldmd` | `0xdec` | `0xdd4` | **`-0x18`** |
| `__DATA.__bss` | `0x5480` | `0x5490` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x330` | `0x340` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x85e` | `0x84e` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x8e3` | `0x8d3` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x2f8` | `0x2f0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x288` | `0x290` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-94.0.0.0.0
+95.0.0.0.0

+  - /usr/lib/swift/libswift_StringProcessing.dylib

-  Functions: 1406
-  Symbols:   494
-  CStrings:  384
+  Functions: 1401
+  Symbols:   503
+  CStrings:  383
Symbols:
+ _$s17_StringProcessing14RegexComponentP5regexAA0C0Vy0C6OutputQzGvgTj
+ _$s17_StringProcessing5RegexV06_regexA07versionACyxGSS_SitcfC
+ _$s17_StringProcessing5RegexV10wholeMatch2inAC0E0Vyx_GSgSs_tKF
+ _$s17_StringProcessing5RegexV5MatchV13dynamicMemberqd__s7KeyPathCyxqd__G_tcluig
+ _$s17_StringProcessing5RegexV5MatchVMn
+ _$s17_StringProcessing5RegexVMn
+ _$s17_StringProcessing5RegexVyxGAA0C9ComponentAAMc
+ _$sSS14_fromSubstringySSSshFZ
+ _$sSSySsSnySS5IndexVGcig
+ _swift_getKeyPath
- _$s10Foundation3URLV36_unconditionallyBridgeFromObjectiveCyACSo5NSURLCSgFZ
CStrings:
+ "#/(?<base>https://www\\.icloud\\.com/[^/]+/[^#]+)(#.*)?/#"
- "asset-file-url"
- "fileURL"
```
