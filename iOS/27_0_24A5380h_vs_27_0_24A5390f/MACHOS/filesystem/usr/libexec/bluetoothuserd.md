## bluetoothuserd

> `/usr/libexec/bluetoothuserd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6eff0` | `0x6fe00` | **`+0xe10`** |
| `__DATA.__objc_const` | `0x1ae8` | `0x1c20` | **`+0x138`** |
| `__DATA.__data` | `0x2450` | `0x2580` | **`+0x130`** |
| `__TEXT.__constg_swiftt` | `0x1728` | `0x17bc` | **`+0x94`** |
| `__TEXT.__swift5_typeref` | `0x15da` | `0x165c` | **`+0x82`** |
| `__TEXT.__const` | `0x2e38` | `0x2eb8` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x2a75` | `0x2ad5` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x3380` | `0x33d0` | **`+0x50`** |
| `__TEXT.__objc_classname` | `0x4aa` | `0x4fa` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x1210` | `0x1260` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0xd14` | `0xd60` | **`+0x4c`** |
| `__TEXT.__objc_stubs` | `0x16e0` | `0x1720` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x13a0` | `0x13e0` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0xc14` | `0xc48` | **`+0x34`** |
| `__DATA.__objc_selrefs` | `0x890` | `0x8a0` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x1e90` | `0x1ea0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xf50` | `0xf58` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x610` | `0x618` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x550` | `0x558` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x90` | `0x98` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xe8` | `0xec` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2700.43.0.0.0
+2700.46.1.1.0

-  Functions: 1804
-  Symbols:   835
-  CStrings:  1102
+  Functions: 1822
+  Symbols:   837
+  CStrings:  1109
Symbols:
+ _OBJC_CLASS_$_NSLock
+ _swift_retain_x10
CStrings:
+ "_TtCC14bluetoothuserd25DarwinNotificationManager24EventStreamObserverToken"
+ "darwinEventStreamToken"
+ "eventStreamObservers"
+ "id"
+ "lock"
+ "nextObserverID"
+ "unlock"
```
