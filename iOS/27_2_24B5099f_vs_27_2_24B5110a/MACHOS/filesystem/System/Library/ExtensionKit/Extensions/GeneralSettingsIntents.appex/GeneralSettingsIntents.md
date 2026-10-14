## GeneralSettingsIntents

> `/System/Library/ExtensionKit/Extensions/GeneralSettingsIntents.appex/GeneralSettingsIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb460` | `0xb73c` | **`+0x2dc`** |
| `__TEXT.__cstring` | `0x2cd1` | `0x2db1` | **`+0xe0`** |
| `__TEXT.__auth_stubs` | `0x7d0` | `0x830` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0x3f0` | `0x420` | **`+0x30`** |
| `__TEXT.__const` | `0x1348` | `0x1358` | **`+0x10`** |
| `__DATA.__data` | `0x408` | `0x410` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x168` | `0x170` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2027.1.1.0.0
+2027.1.1.101.0

-  Functions: 320
+  Functions: 321

-  CStrings:  169
+  CStrings:  173
CStrings:
+ "Handoff to Home Devices"
+ "HomeDevices-J490"
+ "Settings search result description. 'Handoff' is an Apple feature name."
+ "Settings search result title. 'Handoff' is an Apple feature name."
+ "The “Handoff to Home Devices” setting is in the iOS Settings app on the “AirPlay & Continuity” pane. This setting allows users to transfer playing media from an iPhone to a HomePod"
- "The “Transfer to HomePod” setting is in the iOS Settings app on the “AirPlay & Continuity” pane. This setting allows users to transfer playing media from an iPhone to a HomePod"
```
