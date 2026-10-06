## AirDrop

> `/System/Library/PrivateFrameworks/Sharing.framework/PlugIns/AirDrop.appex/AirDrop`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1dbb0` | `0x1f86c` | **`+0x1cbc`** |
| `__TEXT.__auth_stubs` | `0x15b0` | `0x1700` | **`+0x150`** |
| `__TEXT.__oslogstring` | `0xa3d` | `0xb2d` | **`+0xf0`** |
| `__TEXT.__eh_frame` | `0xb30` | `0xa60` | **`-0xd0`** |
| `__DATA_CONST.__auth_got` | `0xae8` | `0xb90` | **`+0xa8`** |
| `__DATA.__objc_const` | `0x1d20` | `0x1dc0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x9da` | `0xa7a` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0x419c` | `0x421c` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x750` | `0x718` | **`-0x38`** |
| `__TEXT.__swift5_reflstr` | `0x16f` | `0x19f` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x9b0` | `0x988` | **`-0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x168` | `0x18c` | **`+0x24`** |
| `__DATA.__data` | `0x998` | `0x9b8` | **`+0x20`** |
| `__DATA.__objc_data` | `0x3a8` | `0x3c0` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x108` | `0x120` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xcb8` | `0xcc8` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0xffb` | `0xfeb` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0x98` | `0x8c` | **`-0xc`** |
| `__TEXT.__swift5_typeref` | `0x424` | `0x42e` | **`+0xa`** |
| `__DATA.__objc_ivar` | `0xbc` | `0xc4` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x450` | `0x458` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x100` | `0x108` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x4c` | `0x44` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x34` | `0x30` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-2124.10.2.2.2
+2126.10.4.0.0

-  Functions: 469
-  Symbols:   365
-  CStrings:  895
+  Functions: 463
+  Symbols:   370
+  CStrings:  913
Symbols:
+ _SFBundleIDFromAuditToken
+ _os_signpost_id_generate
+ _swift_release_x25
+ _swift_retain_n
+ _swift_retain_x24
CStrings:
+ " enableTelemetry=YES "
+ "Picker.Browse"
+ "Picker.Present"
+ "Picker.SelectPerson"
+ "Picker.SelectPersonWithMetadata"
+ "Picker.Tap"
+ "Picker.TransferStarted"
+ "[Error] Interval already ended"
+ "_signpostPickerBrowseBegan"
+ "_signpostPickerPresentBegan"
+ "browseState"
+ "cellInitiator=%{public, signpost.telemetry:number1}d"
+ "com.apple.camera"
+ "com.apple.mobileslideshow"
+ "endpointUUID=%{public}s"
+ "endpointUUID=%{public}s transferID=%{public}s"
+ "pickerSignposter"
+ "presentState"
```
