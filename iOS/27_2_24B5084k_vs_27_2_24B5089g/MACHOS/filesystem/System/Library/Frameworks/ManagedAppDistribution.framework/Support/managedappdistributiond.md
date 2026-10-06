## managedappdistributiond

> `/System/Library/Frameworks/ManagedAppDistribution.framework/Support/managedappdistributiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6dd1e0` | `0x6e014c` | **`+0x2f6c`** |
| `__TEXT.__eh_frame` | `0x3a448` | `0x3a758` | **`+0x310`** |
| `__TEXT.__unwind_info` | `0x125d0` | `0x126b0` | **`+0xe0`** |
| `__TEXT.__swift_as_cont` | `0x3584` | `0x35fc` | **`+0x78`** |
| `__DATA.__data` | `0x10f68` | `0x10f90` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x2f588` | `0x2f560` | **`-0x28`** |
| `__TEXT.__swift_as_ret` | `0x19f8` | `0x1a10` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x7070` | `0x7080` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x15ef2` | `0x15f02` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x3848` | `0x3850` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1f70` | `0x1f78` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xc40` | `0xc48` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-4.1.9.0.0
+4.1.11.0.0

-  Functions: 16667
-  Symbols:   3269
+  Functions: 16702
+  Symbols:   3271
Symbols:
+ _$s22ManagedAppDistribution19MessageRegistrationO15isLibraryScopedSbvg
+ _$s22ManagedAppDistribution19MessageRegistrationOs23CustomStringConvertibleAAMc
CStrings:
+ "[%@] Client %{public}s is entitled to no library; refusing registration for %{public}s"
- "[%@] Client %{public}s is entitled to no library; refusing registration"
```
