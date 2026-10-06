## audioaccessoryd

> `/usr/libexec/audioaccessoryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x257afc` | `0x258aa8` | **`+0xfac`** |
| `__TEXT.__oslogstring` | `0x9d5a` | `0x9e5a` | **`+0x100`** |
| `__TEXT.__objc_stubs` | `0x1f220` | `0x1f2c0` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0x2d345` | `0x2d3c5` | **`+0x80`** |
| `__DATA_CONST.__cfstring` | `0xb9e0` | `0xb980` | **`-0x60`** |
| `__DATA_CONST.__const` | `0xcce0` | `0xcd30` | **`+0x50`** |
| `__DATA_CONST.__objc_intobj` | `0x330` | `0x360` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x92e0` | `0x9308` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x1f94` | `0x1fb8` | **`+0x24`** |
| `__DATA_CONST.__got` | `0x1120` | `0x1130` | **`+0x10`** |
| `__TEXT.__const` | `0x4d00` | `0x4d10` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xe8ac` | `0xe8bc` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x7240` | `0x7250` | **`+0x10`** |
| `__DATA.__objc_data` | `0x3668` | `0x3670` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x210c` | `0x2114` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-40.33.1.0.0
+40.36.1.0.0

-  Functions: 12022
-  Symbols:   1688
-  CStrings:  16342
+  Functions: 12034
+  Symbols:   1690
+  CStrings:  16348
Symbols:
+ _OBJC_CLASS_$_DAExtensionRuntimeAssertion
+ _RPOptionStatusFlags
CStrings:
+ "-[AASourceDeviceManager _startScanningWithControlFlags:]_block_invoke_5"
+ "Failed to create DAExtensionRuntimeAssertion for UUID %s"
+ "Failed to execute runtime assertion for UUID %s: %@"
+ "No DADevice found for UUID %s, skipping runtime assertion"
+ "Runtime assertion requested for UUID %s (duration: %fs)"
+ "Using exsting extensionSession connection"
+ "daDeviceForBTIdentifier:"
+ "executeCommand:error:"
+ "initWithDevice:capabilityFlags:"
+ "setDuration:"
- "-[AASourceDeviceManager _startScanningWithControlFlags:]_block_invoke_6"
- "AudioAccessory1,"
- "AudioAccessory5,"
- "AudioAccessory6,"
```
