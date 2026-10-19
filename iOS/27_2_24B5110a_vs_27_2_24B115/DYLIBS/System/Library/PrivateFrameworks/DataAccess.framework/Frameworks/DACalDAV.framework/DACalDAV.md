## DACalDAV

> `/System/Library/PrivateFrameworks/DataAccess.framework/Frameworks/DACalDAV.framework/DACalDAV`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x36c3c` | `0x36cd0` | **`+0x94`** |
| `__TEXT.__oslogstring` | `0x5061` | `0x50a6` | **`+0x45`** |
| `__DATA_CONST.__objc_selrefs` | `0x2820` | `0x2828` | **`+0x8`** |

### Other Changes

```diff

-  CStrings:  656
+  CStrings:  657
Functions:
~ -[MobileCalDAVAccountRefreshActor _uploadAttachments:forOwnerURL:syncKey:scheduleTag:] : 1892 -> 2040
CStrings:
+ "Refusing to upload attachment %i (%@) because %@ is a symbolic link."
```
