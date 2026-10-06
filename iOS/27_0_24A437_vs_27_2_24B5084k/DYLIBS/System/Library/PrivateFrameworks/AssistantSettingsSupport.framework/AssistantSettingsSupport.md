## AssistantSettingsSupport

> `/System/Library/PrivateFrameworks/AssistantSettingsSupport.framework/AssistantSettingsSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x84764` | `0x84a20` | **`+0x2bc`** |
| `__TEXT.__cstring` | `0x6e78` | `0x6e98` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0xabf` | `0xadf` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x938` | `0x944` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x14e8` | `0x14f0` | **`+0x8`** |
| `__DATA.__data` | `0x1638` | `0x1640` | **`+0x8`** |
| `__DATA_CONST.__const` | `0xd70` | `0xd68` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2480` | `0x2488` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x2e38` | `0x2e40` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x31d6` | `0x31de` | **`+0x8`** |

### Other Changes

```diff

-3600.55.37.11.4
+3605.22.2.0.0

-  - /usr/lib/swift/libswiftSpriteKit.dylib

-  Functions: 2629
+  Functions: 2632

-  CStrings:  986
+  CStrings:  987
Symbols:
+ +[SRUIFSiriFeatureFlag(SWEFeatureFlags) isContinuousConversationHomepodEnabled]
+ _symbolic _____Sg 12FindMyLocate12ClientTargetV
- __swift_FORCE_LOAD_$_swiftSpriteKit
- __swift_FORCE_LOAD_$_swiftSpriteKit_$_AssistantSettingsSupport
CStrings:
+ "continuous_conversation_homepod"
```
