## ShareSheet

> `/System/Library/PrivateFrameworks/ShareSheet.framework/ShareSheet`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x2800` | `0x32f0` | **`+0xaf0`** |
| `__DATA_DIRTY.__objc_data` | `0x1630` | `0xb40` | **`-0xaf0`** |
| `__TEXT.__text` | `0xc6c6c` | `0xc6e3c` | **`+0x1d0`** |
| `__TEXT.__oslogstring` | `0x70c4` | `0x7110` | **`+0x4c`** |
| `__AUTH.__data` | `0x150` | `0x198` | **`+0x48`** |
| `__DATA_DIRTY.__data` | `0x48` | `—` | **`-0x48`** |
| `__AUTH_CONST.__cfstring` | `0x59a0` | `0x59e0` | **`+0x40`** |
| `__TEXT.__ustring` | `0xf0` | `0x104` | **`+0x14`** |
| `__DATA.__bss` | `0xaa8` | `0xab8` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x10` | `—` | **`-0x10`** |
| `__TEXT.__cstring` | `0x711a` | `0x7128` | **`+0xe`** |

### Other Changes

```diff

-2122.10.2.2.1
+2124.10.2.2.2

-  CStrings:  1608
+  CStrings:  1611
Functions:
~ -[UIActivityContentViewController _updateContentWithPeopleProxies:shareProxies:actionProxies:activitiesByUUID:nearbyCountSlotID:animated:reloadData:] : 1144 -> 1160
~ -[SHSheetContentDataSourceManager _updateCurrentStateWithChangeRequest:] : 2492 -> 2640
~ -[SHSheetPresenter updateHostPortraitWindowSize:] : 316 -> 420
~ -[SHSheetPresenter interactor:creatingCollaborationForActivity:] : 304 -> 444
~ -[SHSheetContentLayoutSpec _calculateIconWidths] : 156 -> 212
CStrings:
+ "CREATING_TEXT"
+ "Creating…"
+ "SHSheetContentDataSourceManager: Dropping duplicate people proxy %{public}@"
```
