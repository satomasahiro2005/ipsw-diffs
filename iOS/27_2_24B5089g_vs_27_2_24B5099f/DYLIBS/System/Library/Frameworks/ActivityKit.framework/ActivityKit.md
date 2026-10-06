## ActivityKit

> `/System/Library/Frameworks/ActivityKit.framework/ActivityKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc3658` | `0xc4ca8` | **`+0x1650`** |
| `__DATA_DIRTY.__objc_data` | `0x810` | `0xb38` | **`+0x328`** |
| `__AUTH.__objc_data` | `0x1238` | `0xf30` | **`-0x308`** |
| `__DATA_DIRTY.__data` | `0x2810` | `0x2a18` | **`+0x208`** |
| `__AUTH.__data` | `0xbb0` | `0x9d0` | **`-0x1e0`** |
| `__AUTH_CONST.__objc_const` | `0x57b0` | `0x5810` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x8c70` | `0x8cc0` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x45e0` | `0x4618` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x3920` | `0x3948` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x698` | `0x6b8` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xf2c` | `0xf4c` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x1e9f` | `0x1ebf` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0xa60` | `0xa80` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x2413` | `0x2433` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xe00` | `0xe18` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x3878` | `0x3890` | **`+0x18`** |
| `__TEXT.__const` | `0xef8a` | `0xef9a` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x3058` | `0x3064` | **`+0xc`** |
| `__TEXT.__swift5_typeref` | `0x3e18` | `0x3e22` | **`+0xa`** |
| `__DATA.__objc_ivar` | `0xa0` | `0xa4` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-313.2.4.0.0
+313.2.7.0.0

-  Functions: 5226
-  Symbols:   2149
-  CStrings:  363
+  Functions: 5241
+  Symbols:   2154
+  CStrings:  364
Symbols:
+ -[ACActivityDescriptor initWithIdentifier:sceneTargets:alertSceneTargets:presentationOptions:isEphemeral:isMomentary:isImportant:createdDate:descriptorData:contentTypesByDestination:alertContentTypesByDestination:remoteDeviceIdentifier:localizedAppName:localizedActivityName:protectionClass:]
+ -[ACActivityDescriptor localizedActivityName]
+ -[ACActivityDescriptor localizedName]
+ -[ACActivityDescriptor setLocalizedActivityName:]
+ _OBJC_IVAR_$_ACActivityDescriptor._localizedActivityName
+ _symbolic _____ySOG 8Dispatch0A11SpecificKeyC
- -[ACActivityDescriptor initWithIdentifier:sceneTargets:alertSceneTargets:presentationOptions:isEphemeral:isMomentary:isImportant:createdDate:descriptorData:contentTypesByDestination:alertContentTypesByDestination:remoteDeviceIdentifier:localizedAppName:protectionClass:]
CStrings:
+ "AlertClient invalidated"
```
