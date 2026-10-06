## ClarityBoard

> `/System/Library/CoreServices/ClarityBoard.app/ClarityBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x12e95` | `0x13065` | **`+0x1d0`** |
| `__DATA.__objc_const` | `0xa828` | `0xa8c8` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x59c4` | `0x5a3c` | **`+0x78`** |
| `__TEXT.__text` | `0x29ad70` | `0x29acf8` | **`-0x78`** |
| `__DATA.__objc_selrefs` | `0x4268` | `0x42b8` | **`+0x50`** |
| `__TEXT.__const` | `0x28368` | `0x28388` | **`+0x20`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-170.3.1.0.0
+170.3.3.0.0

-  CStrings:  4398
+  CStrings:  4408
Functions:
~ sub_1000294ac : 424 -> 300
~ sub_100070094 -> sub_100070018 : 124 -> 128
CStrings:
+ "activityResponseContentBounds"
+ "activitySearchContentBounds"
+ "activityThinkingContentBounds"
+ "activityVoiceContentBounds"
+ "setActivityResponseContentBounds:"
+ "setActivitySearchContentBounds:"
+ "setActivityThinkingContentBounds:"
+ "setActivityVoiceContentBounds:"
+ "setTransientCanvasContentBounds:"
+ "transientCanvasContentBounds"
```
