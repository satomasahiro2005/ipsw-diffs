## gamed

> `/usr/libexec/gamed`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x235c7` | `0x23627` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x1b7a0` | `0x1b7e0` | **`+0x40`** |
| `__DATA.__objc_const` | `0x20eb0` | `0x20ee0` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x19019` | `0x19049` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0xbaf8` | `0xbb20` | **`+0x28`** |
| `__TEXT.__text` | `0x298d2c` | `0x298d54` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0xe04c` | `0xe06c` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x8158` | `0x8170` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x48d0` | `0x48e0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x8da0` | `0x8db0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x2480` | `0x2488` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1ff0` | `0x1ff8` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x628` | `0x630` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x718` | `0x71c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-821.0.13.1.2
+821.0.16.0.0

-  Functions: 12171
-  Symbols:   2527
-  CStrings:  10537
+  Functions: 12194
+  Symbols:   2529
+  CStrings:  10543
Symbols:
+ _$s16GameServicesCore26LibraryBagProviderProtocolP19cachedConfigurationAA0deiG0_pyYaFTj
+ _$s16GameServicesCore26LibraryBagProviderProtocolP19cachedConfigurationAA0deiG0_pyYaFTjTu
CStrings:
+ "-[GKGameStatService getLeaderboardSetsForGameDescriptor:handler:]_block_invoke_3"
+ "Skipping AMS %@ callback for x86 client %@"
+ "TB,V_isRosettiniClient"
+ "[BGT] Task cancelled (cooperative): %s"
+ "_isRosettiniClient"
+ "isRosettiniClient"
+ "markClientIsRosettini"
+ "setIsRosettiniClient:"
- "-[GKGameStatService getLeaderboardSetsForGameDescriptor:handler:]_block_invoke"
- "[BGT] Task cancelled: %s — retrying in %fs"
```
