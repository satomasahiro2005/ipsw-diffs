## DeveloperSettingsIntents

> `/System/Library/ExtensionKit/Extensions/DeveloperSettingsIntents.appex/DeveloperSettingsIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8e44` | `0x8fac` | **`+0x168`** |
| `__TEXT.__cstring` | `0x34be` | `0x34ee` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x2b0` | `0x2d8` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x840` | `0x850` | **`+0x10`** |
| `__TEXT.__const` | `0xb02` | `0xb12` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x428` | `0x430` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x488` | `0x490` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xe8` | `0xf0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x298` | `0x2a0` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x34` | `0x38` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x20` | `0x24` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`

### Other Changes

```diff

-2027.0.1.0.0
+2027.0.2.0.0

-  Functions: 201
+  Functions: 202

-  CStrings:  192
+  CStrings:  193
Functions:
~ sub_100002e14 : 14416 -> 14600
+ sub_100006930
CStrings:
+ "Paired Computers"
+ "The “Paired Computers” setting is in the iOS Settings app under “Developer” pane. This setting allows users to see audit history and manage Mac computers that have paired with their device."
- "The “Paired Macs” setting is in the iOS Settings app under “Developer” pane. This setting allows users to see audit history and manage Macs that have paired with their device."
```
