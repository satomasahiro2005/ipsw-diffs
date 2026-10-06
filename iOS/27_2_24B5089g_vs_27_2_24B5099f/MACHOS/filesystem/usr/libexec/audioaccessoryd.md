## audioaccessoryd

> `/usr/libexec/audioaccessoryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25c168` | `0x25c078` | **`-0xf0`** |
| `__TEXT.__eh_frame` | `0x2d90` | `0x2db8` | **`+0x28`** |
| `__DATA.__data` | `0x59e0` | `0x59c0` | **`-0x20`** |
| `__TEXT.__cstring` | `0x59113` | `0x59133` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1160` | `0x1158` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-41.4.0.0.0
+41.6.0.0.0

-  Symbols:   1708
+  Symbols:   1707
Symbols:
+ _$s10Foundation4DateV2geoiySbAC_ACtFZ
- _$s10Foundation4DateVSLAAMc
- _$sSL2geoiySbx_xtFZTj
Functions:
~ sub_1001e5a58 : 26352 -> 26048
~ sub_1001ff324 -> sub_1001ff1f4 : 7584 -> 7604
~ sub_10020e300 -> sub_10020e1e4 : 164 -> 168
~ sub_10020e3a4 -> sub_10020e28c : 148 -> 152
~ sub_10022bad8 -> sub_10022b9c4 : 32 -> 68
CStrings:
+ "Head gestures were unexpectedly disabled on %@? Please file a radar and attach ALL nearby devices' sysdiagnoses."
- "Head gestures were unexpectedly disabled on %@? Please file a radar."
```
