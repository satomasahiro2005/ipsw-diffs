## Sharing

> `/System/Library/PrivateFrameworks/Sharing.framework/Sharing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x4530` | `0x7818` | **`+0x32e8`** |
| `__DATA_DIRTY.__objc_data` | `0x4368` | `0x1080` | **`-0x32e8`** |
| `__DATA_DIRTY.__data` | `0x13b0` | `0x300` | **`-0x10b0`** |
| `__AUTH.__data` | `0x3eb0` | `0x4e00` | **`+0xf50`** |
| `__DATA_DIRTY.__bss` | `0x2e8` | `0xc8` | **`-0x220`** |
| `__DATA.__bss` | `0x3e510` | `0x3e710` | **`+0x200`** |
| `__DATA.__data` | `0xcf20` | `0xd050` | **`+0x130`** |
| `__TEXT.__text` | `0x38ae6c` | `0x38af08` | **`+0x9c`** |
| `__TEXT.__eh_frame` | `0x100e4` | `0x10054` | **`-0x90`** |
| `__TEXT.__cstring` | `0x3ad85` | `0x3adb5` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x13c8` | `0x13e0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xed68` | `0xed78` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0xca4` | `0xca8` | **`+0x4`** |

### Other Changes

```diff

-2122.10.2.2.1
+2124.10.2.2.2

-  Functions: 24538
+  Functions: 24543

-  CStrings:  8858
+  CStrings:  8859
Symbols:
+ -[_SFCollaborationItemsRequest _processRemainingActivityItemsFromIndex:]
- -[_SFCollaborationItemsRequest _processRemainingActivityItems]
CStrings:
+ "FindNearbyLocalFindableAccessoryExtendedRange"
```
