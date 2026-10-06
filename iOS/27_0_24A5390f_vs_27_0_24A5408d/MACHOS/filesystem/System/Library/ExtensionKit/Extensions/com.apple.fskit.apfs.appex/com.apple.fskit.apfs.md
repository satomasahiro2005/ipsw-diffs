## com.apple.fskit.apfs

> `/System/Library/ExtensionKit/Extensions/com.apple.fskit.apfs.appex/com.apple.fskit.apfs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe4fa4` | `0xe51d0` | **`+0x22c`** |
| `__DATA.__data` | `0x1368` | `0x13c8` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x1ee7` | `0x1eb1` | **`-0x36`** |
| `__TEXT.__objc_classname` | `0x124` | `0x13d` | **`+0x19`** |
| `__DATA.__objc_selrefs` | `0x6f0` | `0x6e0` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x84c` | `0x83c` | **`-0x10`** |
| `__DATA.__objc_const` | `0xae8` | `0xae0` | **`-0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__cstring` | `0x3b8b1` | `0x3b8b3` | **`+0x2`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3283.0.13.0.0
+3288.2.1.0.0

-  Functions: 3286
-  Symbols:   1566
-  CStrings:  5387
+  Functions: 3287
+  Symbols:   1567
+  CStrings:  5386
Symbols:
+ _decrement_dstream_id_for_deletion_ex
+ _is_valid_crypto_id
- _decrement_dstream_id_for_deletion
CStrings:
+ "3288.2.1"
+ "FSVolumeCommonOperations"
+ "TB,?,R"
+ "decrement_dstream_id_for_deletion_ex"
- "3283.0.13"
- "TQ,?"
- "decrement_dstream_id_for_deletion"
- "setEnableOpenUnlinkEmulation:"
- "setRequestedMountOptions:"
```
