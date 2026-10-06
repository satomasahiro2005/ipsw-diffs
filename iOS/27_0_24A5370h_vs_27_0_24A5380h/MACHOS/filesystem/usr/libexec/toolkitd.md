## toolkitd

> `/usr/libexec/toolkitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x99710` | `0x99920` | **`+0x210`** |
| `__TEXT.__oslogstring` | `0x16cc` | `0x175c` | **`+0x90`** |
| `__TEXT.__eh_frame` | `0x4c50` | `0x4c18` | **`-0x38`** |
| `__TEXT.__const` | `0x463c` | `0x461c` | **`-0x20`** |
| `__DATA_CONST.__got` | `0xc00` | `0xbe8` | **`-0x18`** |
| `__TEXT.__auth_stubs` | `0x2d00` | `0x2d10` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1688` | `0x1690` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x184b` | `0x1845` | **`-0x6`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-5028.0.21.0.0
+5032.5.0.0.0

-  Functions: 2755
-  Symbols:   1260
-  CStrings:  571
+  Functions: 2752
+  Symbols:   1258
+  CStrings:  573
Symbols:
+ _$s11WorkflowKit04ToolB17CascadeSyncEngineC26clearAllBookmarkRegistries13cascadeClientyAA0ceL0_p_tKFZ
+ _$s11WorkflowKit04ToolB17CascadeSyncEngineC26clearAllBookmarkRegistries13cascadeClientyAA0ceL0_p_tKFZfA_
- _$ss5NeverON
- _$ss5NeverOs5ErrorsWP
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
CStrings:
+ "Cleared Cascade pull bookmarks after full reindex"
+ "Failed to clear Cascade bookmark registries after full reindex: %@"
```
