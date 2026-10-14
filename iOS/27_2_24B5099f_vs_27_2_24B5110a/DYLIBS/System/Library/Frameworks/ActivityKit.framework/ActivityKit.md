## ActivityKit

> `/System/Library/Frameworks/ActivityKit.framework/ActivityKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc4ca8` | `0xc555c` | **`+0x8b4`** |
| `__TEXT.__cstring` | `0x1e61` | `0x1ec9` | **`+0x68`** |
| `__TEXT.__swift5_reflstr` | `0x2433` | `0x2493` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x3948` | `0x3990` | **`+0x48`** |
| `__TEXT.__swift5_fieldmd` | `0x3064` | `0x30a0` | **`+0x3c`** |
| `__AUTH_CONST.__objc_const` | `0x5810` | `0x5840` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xf4c` | `0xf64` | **`+0x18`** |
| `__AUTH.__data` | `0x9d0` | `0x9e0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x6b8` | `0x6c8` | **`+0x10`** |
| `__TEXT.__const` | `0xef9a` | `0xefaa` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x2a18` | `0x2a20` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xa4` | `0xa8` | **`+0x4`** |

### Other Changes

```diff

-313.2.7.0.0
+313.2.9.0.0

-  Functions: 5241
-  Symbols:   2154
-  CStrings:  364
+  Functions: 5289
+  Symbols:   2157
+  CStrings:  367
Symbols:
+ -[ACActivityDescriptor initWithIdentifier:sceneTargets:alertSceneTargets:presentationOptions:isEphemeral:isMomentary:isImportant:createdDate:descriptorData:contentTypesByDestination:alertContentTypesByDestination:remoteDeviceIdentifier:localizedAppName:localizedAppNameBundleID:localizedActivityName:protectionClass:]
+ -[ACActivityDescriptor localizedAppNameBundleID]
+ -[ACActivityDescriptor setLocalizedAppNameBundleID:]
+ _OBJC_IVAR_$_ACActivityDescriptor._localizedAppNameBundleID
- -[ACActivityDescriptor initWithIdentifier:sceneTargets:alertSceneTargets:presentationOptions:isEphemeral:isMomentary:isImportant:createdDate:descriptorData:contentTypesByDestination:alertContentTypesByDestination:remoteDeviceIdentifier:localizedAppName:localizedActivityName:protectionClass:]
CStrings:
+ "Has Preconsent: "
+ "hasUserPreconsent"
+ "localizedAppNameBundleID"
```
