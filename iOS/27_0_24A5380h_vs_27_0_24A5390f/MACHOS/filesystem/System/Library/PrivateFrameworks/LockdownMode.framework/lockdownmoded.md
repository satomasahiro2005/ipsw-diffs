## lockdownmoded

> `/System/Library/PrivateFrameworks/LockdownMode.framework/lockdownmoded`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f620` | `0x3fc68` | **`+0x648`** |
| `__TEXT.__oslogstring` | `0x3202` | `0x3342` | **`+0x140`** |
| `__DATA_CONST.__const` | `0x1258` | `0x12a8` | **`+0x50`** |
| `__TEXT.__objc_stubs` | `0xf20` | `0xf40` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x19e9` | `0x19f9` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x3d8` | `0x3e4` | **`+0xc`** |
| `__DATA.__objc_data` | `0x540` | `0x548` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x618` | `0x620` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x4a0` | `0x4a8` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0xd2c` | `0xd34` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-128.0.4.0.0
+128.0.5.0.0

-  Functions: 774
-  Symbols:   603
-  CStrings:  670
+  Functions: 778
+  Symbols:   604
+  CStrings:  675
Symbols:
+ _OBJC_CLASS_$_NSThread
CStrings:
+ "Presented Lockdown Mode turn-on alert"
+ "Received UserNotification response dismissing the Lockdown Mode turn-on alert (Later)."
+ "Replacing an already-presented Lockdown Mode turn-on alert with a new one"
+ "Tore down the presented Lockdown Mode turn-on alert (run-loop source removed, dialog cancelled)"
+ "isMainThread"
```
