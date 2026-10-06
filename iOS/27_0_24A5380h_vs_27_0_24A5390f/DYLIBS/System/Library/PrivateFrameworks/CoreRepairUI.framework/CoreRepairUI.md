## CoreRepairUI

> `/System/Library/PrivateFrameworks/CoreRepairUI.framework/CoreRepairUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x197a4` | `0x19a48` | **`+0x2a4`** |
| `__AUTH_CONST.__cfstring` | `0x3a20` | `0x3ae0` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x301d` | `0x30ab` | **`+0x8e`** |
| `__DATA_CONST.__objc_selrefs` | `0xd90` | `0xd98` | **`+0x8`** |
| `__TEXT.__const` | `0xb8` | `0xb0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x480` | `0x488` | **`+0x8`** |

### Other Changes

```diff

-1307.0.26.502.1
+1307.0.46.0.0

-  CStrings:  604
+  CStrings:  610
CStrings:
+ "FINISH_TOUCHID_DESC"
+ "FINISH_TOUCHID_REPAIR_DESC"
+ "FINISH_VOLUME_BUTTON_DESC_IPAD"
+ "GENUINE_TOUCHID_DESC"
+ "TOUCHID_DESC"
+ "TOUCHID_KB_URL"
+ "TOUCHID_REPAIR_KB_URL"
+ "USED_TOUCHID_DESC"
- "finishRepairId"
- "warningId"
```
