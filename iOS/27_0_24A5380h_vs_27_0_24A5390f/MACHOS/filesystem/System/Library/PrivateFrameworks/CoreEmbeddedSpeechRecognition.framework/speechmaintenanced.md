## speechmaintenanced

> `/System/Library/PrivateFrameworks/CoreEmbeddedSpeechRecognition.framework/speechmaintenanced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ee2c` | `0x3f34c` | **`+0x520`** |
| `__TEXT.__oslogstring` | `0x247e` | `0x253e` | **`+0xc0`** |
| `__TEXT.__eh_frame` | `0x2140` | `0x20c0` | **`-0x80`** |
| `__TEXT.__objc_stubs` | `0x9c0` | `0x9e0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xa20` | `0xa08` | **`-0x18`** |
| `__DATA.__data` | `0xd80` | `0xd90` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x1780` | `0x1790` | **`+0x10`** |
| `__TEXT.__const` | `0xc00` | `0xbf0` | **`-0x10`** |
| `__TEXT.__objc_methname` | `0xdf1` | `0xe01` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x368` | `0x370` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0xbc8` | `0xbd0` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x4d8` | `0x4d0` | **`-0x8`** |
| `__TEXT.__swift5_capture` | `0x470` | `0x474` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x154` | `0x150` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0x9c` | `0x98` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0xb8` | `0xb4` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-3600.70.20.1.1
+3600.70.32.0.0

-  Functions: 644
-  Symbols:   545
-  CStrings:  375
+  Functions: 641
+  Symbols:   546
+  CStrings:  378
Symbols:
+ _$s6Speech12NCBVQProfileC5resetyyFTj
CStrings:
+ "Failed to check asset compatibility, aborting user vocab profile update before Cascade enumeration and SELF logging: %@"
+ "Speech maintenance task %s expired before completion."
+ "User vocab profile entity limit (%ld) reached, set enumeration halted."
+ "clearAllBookmarks"
- "Failed to check asset compatibility, defaulting to full rebuild: %@"
```
