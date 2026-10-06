## PodcastsBridgeSettings

> `/System/Library/NanoPreferenceBundles/Applications/PodcastsBridgeSettings.bundle/PodcastsBridgeSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__ustring` | `0x980` | `0xb30` | **`+0x1b0`** |
| `__TEXT.__text` | `0xfff8` | `0x1019c` | **`+0x1a4`** |
| `__TEXT.__cstring` | `0xb4a` | `0xce9` | **`+0x19f`** |
| `__DATA_CONST.__cfstring` | `0x1000` | `0x1180` | **`+0x180`** |
| `__TEXT.__auth_stubs` | `0x630` | `0x640` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x328` | `0x330` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-4027.110.2.0.0
+4027.210.23.1.0

-  Symbols:   302
-  CStrings:  853
+  Symbols:   303
+  CStrings:  865
Symbols:
+ _os_feature_enabled_up_next_split
Functions:
~ sub_23a0 : 104 -> 140
~ sub_aeb0 -> sub_aed4 : 536 -> 572
~ sub_b0cc -> sub_b114 : 768 -> 804
~ sub_c67c -> sub_c6e8 : 728 -> 764
~ sub_10160 -> sub_101f0 : 260 -> 536
CStrings:
+ "RECENT_EPISODES_CELL_STRING"
+ "RECENT_EPISODES_FOOTER_STRING"
+ "RECENT_EPISODES_NUMBER_OF_EPISODES_FOOTER_TEXT"
+ "RECENT_EPISODES_NUMBER_OF_EPISODES_OFF_FOOTER_TEXT"
+ "Recent Episodes"
+ "Recent episodes won’t be downloaded."
+ "SAVED_NUMBER_OF_EPISODES_FOOTER_TEXT"
+ "SAVED_NUMBER_OF_EPISODES_OFF_FOOTER_TEXT"
+ "SYNC_SETTINGS_CONTENT_SUMMARY_HEADER_NOTHING_ADDED_MESSAGE_RECENT_EPISODES"
+ "Saved episodes won’t be downloaded."
+ "You can choose to automatically keep your Recent Episodes up-to-date on your Apple\u00a0Watch, or manually add shows and stations from your iPhone."
+ "Your iPhone will try to add one episode from each of the top 10 shows in Recent Episodes."
```
