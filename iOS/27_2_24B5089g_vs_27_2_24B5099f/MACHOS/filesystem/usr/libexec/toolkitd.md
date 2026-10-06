## toolkitd

> `/usr/libexec/toolkitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa3524` | `0xa3e98` | **`+0x974`** |
| `__TEXT.__eh_frame` | `0x5f30` | `0x5fc0` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x18fc` | `0x194c` | **`+0x50`** |
| `__DATA.__objc_const` | `0x738` | `0x780` | **`+0x48`** |
| `__TEXT.__auth_stubs` | `0x2e20` | `0x2e60` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x12e8` | `0x1328` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1ef8` | `0x1f28` | **`+0x30`** |
| `__DATA.__data` | `0x1cc0` | `0x1ce0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x1718` | `0x1738` | **`+0x20`** |
| `__TEXT.__cstring` | `0x221d` | `0x223d` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x1a20` | `0x1a40` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1084` | `0x10a4` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xc18` | `0xc30` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x10b4` | `0x10cc` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x758` | `0x768` | **`+0x10`** |
| `__TEXT.__const` | `0x46bc` | `0x46cc` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x1807` | `0x1815` | **`+0xe`** |
| `__DATA.__objc_selrefs` | `0x718` | `0x720` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x40c` | `0x414` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x224` | `0x228` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-5111.0.2.0.0
+5113.0.1.1.1

-  Functions: 2971
-  Symbols:   1276
-  CStrings:  593
+  Functions: 2984
+  Symbols:   1285
+  CStrings:  598
Symbols:
+ _$s11WorkflowKit26AppIntentsInitialIndexGateO12waitForReady_7timeoutyAA0cD17IndexingReadiness_p_s8DurationVtYaKFZ
+ _$s11WorkflowKit26AppIntentsInitialIndexGateO12waitForReady_7timeoutyAA0cD17IndexingReadiness_p_s8DurationVtYaKFZTu
+ _$s11WorkflowKit27AppIntentsIndexingReadinessMp
+ _$sS2cEycfC
+ _$sScEMa
+ _$sScEs5ErrorsMc
+ _$ss8DurationV7secondsyABSdFZ
+ _$ss8DurationVMn
+ _OBJC_CLASS_$_NSUserDefaults
CStrings:
+ "AppIntents initial-index gate failed/timed out; deferring index (retriable): %@"
+ "AppIntentsInitialIndexGate"
+ "appIntentsReadiness"
+ "gateTimeout"
+ "toolKitDaemonInitialIndexGateTimeout"
```
