## jetpackassetd

> `/System/Library/PrivateFrameworks/JetCore.framework/Support/jetpackassetd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb1b20` | `0xb3b54` | **`+0x2034`** |
| `__TEXT.__cstring` | `0x5dd4` | `0x5ed4` | **`+0x100`** |
| `__TEXT.__const` | `0x3d20` | `0x3de8` | **`+0xc8`** |
| `__DATA_CONST.__const` | `0x2ea0` | `0x2f58` | **`+0xb8`** |
| `__TEXT.__swift5_reflstr` | `0xf18` | `0xfa8` | **`+0x90`** |
| `__DATA.__bss` | `0x4080` | `0x4100` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0x11bd` | `0x1207` | **`+0x4a`** |
| `__DATA.__data` | `0x1c58` | `0x1ca0` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x2900` | `0x2940` | **`+0x40`** |
| `__DATA.__common` | `0x170` | `0x1a8` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x1274` | `0x12a8` | **`+0x34`** |
| `__TEXT.__auth_stubs` | `0x2e70` | `0x2ea0` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x8480` | `0x84b0` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x414` | `0x444` | **`+0x30`** |
| `__DATA_CONST.__auth_ptr` | `0x728` | `0x748` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x10cc` | `0x10e8` | **`+0x1c`** |
| `__DATA_CONST.__auth_got` | `0x1740` | `0x1758` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x338` | `0x350` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x518` | `0x52c` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x780` | `0x790` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x234` | `0x244` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x8d4` | `0x8e0` | **`+0xc`** |
| `__TEXT.__swift5_proto` | `0x270` | `0x274` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x170` | `0x174` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-10.0.42.0.0
+10.0.43.0.0

-  Functions: 2131
-  Symbols:   1148
-  CStrings:  714
+  Functions: 2153
+  Symbols:   1155
+  CStrings:  720
Symbols:
+ _$s7JetCore0A22PackAssetDaemonMessageO7prewarmyAcA0E14PrewarmRequestVcACmFWC
+ _$s7JetCore16DaemonNoResponseVACycfC
+ _$s7JetCore16DaemonNoResponseVMn
+ _$s7JetCore20DaemonPrewarmRequestVAA0cE4TypeAAMc
+ _$s7JetCore20DaemonPrewarmRequestVMa
+ _$s7JetCore20DaemonPrewarmRequestVMn
+ _swift_retain_x22
+ _swift_retain_x27
- _swift_retain_x28
CStrings:
+ "Daemon.listener.activate"
+ "Deferred cached-asset bookkeeping failed: "
+ "Failed to activate XPC listener: "
+ "Prewarm request received from client: "
+ "jetpackassetd.main.sandbox.init"
+ "listenerActivation"
```
