## amsengagementd

> `/System/Library/PrivateFrameworks/AppleMediaServicesUI.framework/amsengagementd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1da6ac` | `0x1db040` | **`+0x994`** |
| `__TEXT.__swift5_typeref` | `0x6ccb` | `0x6dd7` | **`+0x10c`** |
| `__TEXT.__cstring` | `0xd276` | `0xd316` | **`+0xa0`** |
| `__DATA.__objc_data` | `0x3e68` | `0x3f00` | **`+0x98`** |
| `__TEXT.__const` | `0xeee8` | `0xef68` | **`+0x80`** |
| `__DATA.__data` | `0xa608` | `0xa668` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x11a48` | `0x11a90` | **`+0x48`** |
| `__TEXT.__auth_stubs` | `0x4120` | `0x4160` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x62a0` | `0x6260` | **`-0x40`** |
| `__TEXT.__objc_methname` | `0x8df8` | `0x8dc8` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x74b8` | `0x74e8` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x6004` | `0x6028` | **`+0x24`** |
| `__DATA_CONST.__auth_got` | `0x20a0` | `0x20c0` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0xd428` | `0xd448` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x1168` | `0x1180` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x4654` | `0x463c` | **`-0x18`** |
| `__DATA.__objc_selrefs` | `0x21d8` | `0x21c8` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x4a40` | `0x4a50` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xf78` | `0xf70` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x5f4` | `0x5f8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-8.1.15.0.0
+8.1.20.0.0

-  Functions: 11849
-  Symbols:   1785
-  CStrings:  3395
+  Functions: 11869
+  Symbols:   1788
+  CStrings:  3397
Symbols:
+ _$s10Foundation13__DataStorageC12_deallocatorySv_SitcSgvg
+ _$s10Foundation4DateV2geoiySbAC_ACtFZ
+ _$s10Foundation4DateV2leoiySbAC_ACtFZ
+ _$s9JetEngine19RunLoopWorkerThreadC11PendingTaskVMa
+ _$s9JetEngine19RunLoopWorkerThreadC13scheduleAfter5delay7executeAC11PendingTaskVSd_yyctFTj
+ _swift_getDynamicType
- _$s10Foundation4DateVSLAAMc
- _$sSL2geoiySbx_xtFZTj
- _$sSL2leoiySbx_xtFZTj
CStrings:
+ "JS worker thread unavailable"
+ "JSVirtualMachineStore releasing "
+ "No JS worker thread; failing lookup"
+ "Shed idle memory (released "
+ "Subscription timeout"
+ "Unsupported type in JavaScript payload, substituting null:"
+ "makeExtensionRequest(extensionID:data:options:)"
- "Failed to deep-copy request data, sending original"
- "JSVirtualMachineStore shrinking "
- "Shed idle memory (shrank "
- "promiseWithTimeout:"
- "propertyList:isValidForFormat:"
```
