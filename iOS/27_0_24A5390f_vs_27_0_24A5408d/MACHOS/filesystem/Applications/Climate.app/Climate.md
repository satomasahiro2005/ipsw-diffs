## Climate

> `/Applications/Climate.app/Climate`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15c3f0` | `0x15dd80` | **`+0x1990`** |
| `__TEXT.__oslogstring` | `0x380a` | `0x393a` | **`+0x130`** |
| `__TEXT.__const` | `0x7b14` | `0x7ad4` | **`-0x40`** |
| `__TEXT.__swift5_reflstr` | `0x3526` | `0x3546` | **`+0x20`** |
| `__DATA.__bss` | `0x4ce0` | `0x4cd0` | **`-0x10`** |
| `__TEXT.__objc_methname` | `0x9163` | `0x9173` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x7bc4` | `0x7bd0` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0x35c0` | `0x35b8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
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

### Other Changes

```diff

-340.0.0.0.0
+342.1.0.0.0

-  CStrings:  2401
+  CStrings:  2405
CStrings:
+ "No climate zone for side %{public}lu — ignoring quick controls tap"
+ "No source view for side %{public}lu — quick controls popover not created"
+ "No status bar view for side %{public}lu — ignoring quick controls tap"
+ "hasDualStatusBar: %{bool,public}d -> %{bool,public}d"
+ "regulatedDefrostButton"
+ "regulatedFanACButton"
- "defrostIndicator"
- "fanAcIndicator"
```
