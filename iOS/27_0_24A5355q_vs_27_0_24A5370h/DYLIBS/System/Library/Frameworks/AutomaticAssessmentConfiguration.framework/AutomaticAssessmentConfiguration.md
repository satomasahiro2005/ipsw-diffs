## AutomaticAssessmentConfiguration

> `/System/Library/Frameworks/AutomaticAssessmentConfiguration.framework/AutomaticAssessmentConfiguration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7850` | `0x78b4` | **`+0x64`** |
| `__AUTH_CONST.__objc_const` | `0xfb0` | `0xfe0` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x690` | `0x6b0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x326` | `0x346` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x83c` | `0x854` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0xfc` | `0x100` | **`+0x4`** |

### Other Changes

```diff

-50.0.0.0.0
+53.0.0.0.0

-  Functions: 250
-  Symbols:   440
+  Functions: 252
+  Symbols:   443
Symbols:
+ -[AEAssessmentParticipantConfiguration _allowGracefulTermination]
+ -[AEAssessmentParticipantConfiguration _setAllowGracefulTermination:]
+ _OBJC_IVAR_$_AEAssessmentParticipantConfiguration.__allowGracefulTermination
CStrings:
+ "<%@: %p { allowsNetworkAccess = %@, required = %@, _allowGracefulTermination = %@, allowedMenuItems = %@, configurationInfo = %@ }>"
- "<%@: %p { allowsNetworkAccess = %@, required = %@, allowedMenuItems = %@, configurationInfo = %@ }>"
```
