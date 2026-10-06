## dasd

> `/usr/libexec/dasd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1728e0` | `0x1736b4` | **`+0xdd4`** |
| `__TEXT.__oslogstring` | `0x16189` | `0x16599` | **`+0x410`** |
| `__DATA_CONST.__got` | `0xc70` | `0xe20` | **`+0x1b0`** |
| `__TEXT.__objc_stubs` | `0x1a9e0` | `0x1ab00` | **`+0x120`** |
| `__TEXT.__objc_methname` | `0x2db0d` | `0x2dbdd` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x10146` | `0x101f6` | **`+0xb0`** |
| `__DATA_CONST.__cfstring` | `0x114e0` | `0x11580` | **`+0xa0`** |
| `__DATA.__objc_selrefs` | `0x9ae8` | `0x9b38` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x12ee4` | `0x12f0c` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x4fa0` | `0x4fb8` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x2220` | `0x2210` | **`-0x10`** |
| `__DATA.__objc_const` | `0x33b70` | `0x33b78` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x1120` | `0x1118` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2467.0.9.0.0
+2467.0.14.502.1

-  Functions: 8260
-  Symbols:   1011
-  CStrings:  12289
+  Functions: 8273
+  Symbols:   1010
+  CStrings:  12325
Symbols:
- _swift_willThrowTypedImpl
CStrings:
+ "Compiling uncompiled model at: %@"
+ "Default asset — using pre-compiled model at: %@"
+ "Failed to compile model at %@ with error: %@"
+ "Failed to load model from %@ with error: %@"
+ "FreezerModel"
+ "Loaded freezer ML model from Trial"
+ "Loading trial freezer ML model"
+ "No trial freezer model path configured"
+ "Pre-compiled model '%@.mlmodelc' not found in daemon bundle"
+ "Reloaded freezer ML model from Trial after update"
+ "Request to load model from path: %@"
+ "Skipping %@ for freezer: memory footprint unavailable"
+ "Skipping freeze quality check for PID %d — frozenSize is 0 (process thawed)"
+ "StoredBootSessionUUID"
+ "Successfully loaded model from %@"
+ "System/Library/PrivateFrameworks/DuetActivityScheduler.framework/assets_COREOS_DRM_APRS/"
+ "Trial model update failed — keeping existing model"
+ "Trial: Boot session changed — clearing stale pre-trial sysctl defaults"
+ "Trial: Could not read kern.bootsessionuuid — skipping stale-defaults check"
+ "Trial: Could not read original sysctl %@ — skipping (err %d)"
+ "Trial: Failed to load factor %@"
+ "Trial: Failed to restore sysctl %@ to %lld (err %d)"
+ "Trial: Failed to set sysctl %@ to %lld (err %d)"
+ "Trial: Restored sysctl %@ to original value %lld"
+ "Trial: Saved original sysctl %@ = %lld"
+ "Trial: Set sysctl %@ to %lld"
+ "Unable to load from null model path"
+ "clearPreTrialDefaultsIfRebooted"
+ "com.apple.dasd.dock.trial-defaults"
+ "compileModelAtURL:error:"
+ "directoryValue"
+ "failActivityForIdentifier:"
+ "fileValue"
+ "levelOneOfCase"
+ "loadModelFromPath:isCompiled:"
+ "loadTrialFreezerModel"
+ "removePersistentDomainForName:"
+ "stringByDeletingPathExtension"
+ "swapfile_limit"
- "Trial: Failed to call sysctl %@ with %d"
- "Trial: Failed to load %@"
- "Trial: Successfully set sysctl %@ to %lld"
```
