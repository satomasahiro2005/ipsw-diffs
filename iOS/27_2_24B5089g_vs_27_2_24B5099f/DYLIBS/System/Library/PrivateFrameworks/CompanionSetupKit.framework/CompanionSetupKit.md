## CompanionSetupKit

> `/System/Library/PrivateFrameworks/CompanionSetupKit.framework/CompanionSetupKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x42e8d8` | `0x434224` | **`+0x594c`** |
| `__TEXT.__eh_frame` | `0x36c60` | `0x36e30` | **`+0x1d0`** |
| `__AUTH_CONST.__const` | `0x19838` | `0x19938` | **`+0x100`** |
| `__TEXT.__const` | `0x2e8a0` | `0x2e990` | **`+0xf0`** |
| `__AUTH_CONST.__objc_const` | `0x71d8` | `0x7278` | **`+0xa0`** |
| `__TEXT.__swift5_reflstr` | `0x805e` | `0x80fe` | **`+0xa0`** |
| `__DATA.__bss` | `0x46610` | `0x46690` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x12da0` | `0x12e18` | **`+0x78`** |
| `__TEXT.__swift5_fieldmd` | `0x9454` | `0x94c4` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x97b5` | `0x9815` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x9bec` | `0x9c48` | **`+0x5c`** |
| `__DATA.__data` | `0x8d58` | `0x8d98` | **`+0x40`** |
| `__TEXT.__cstring` | `0xbf0d` | `0xbf3d` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x1380` | `0x13a8` | **`+0x28`** |
| `__AUTH.__data` | `0x5618` | `0x5638` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x37c4` | `0x37e4` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x6b4c` | `0x6b68` | **`+0x1c`** |
| `__AUTH_CONST.__auth_got` | `0x25f8` | `0x2610` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1948` | `0x1958` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x3e80` | `0x3e90` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x16c4` | `0x16d0` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x1204` | `0x120c` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x2328` | `0x232c` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0xac4` | `0xac8` | **`+0x4`** |

### Other Changes

```diff

-524.10.94.0.0
+524.10.109.0.1

-  Functions: 18523
-  Symbols:   5027
-  CStrings:  2442
+  Functions: 18559
+  Symbols:   5033
+  CStrings:  2445
Symbols:
+ _OBJC_CLASS_$_CWFColocatedConsentResult
+ ___swift_closure_destructor.397Tm
+ ___swift_closure_destructor.424Tm
+ ___swift_closure_destructor.531Tm
+ ___swift_closure_destructor.594Tm
+ _symbolic ScCySo25CWFColocatedConsentResultC______pG s5ErrorP
+ _symbolic _____ 17CompanionSetupKit22CSKStepLanguageSupportC0eF0V
+ _symbolic _____Sg 5Nexus22NXProximityServiceDataO014CompanionSetupD0V6ActionO
+ _symbolic ______Si7attemptt 17CompanionSetupKit019CSKStepAppleAccountB13ConfigurationV
+ _type_layout_string 17CompanionSetupKit22CSKStepLanguageSupportC0eF0V
- ___swift_closure_destructor.394Tm
- ___swift_closure_destructor.420Tm
- ___swift_closure_destructor.527Tm
- ___swift_closure_destructor.590Tm
CStrings:
+ " attempt "
+ "### Add colocated 5GHz network without SSID: ssid=%s"
+ "### Colocated 5GHz scan failed: error=%@"
+ "### Unhandled colocated 5GHz same-SSID consent: ssid=%s"
+ "CFBundleShortVersionString"
+ "Colocated 5GHz scan: status=%ld, count=%ld, ssid=%s"
+ "MusicHandoffScan"
+ "_handleResult: failure, re-presenting: %@"
+ "no supported siri languages"
+ "step returned after cancel: id=%s"
+ "system and siri language are supported and match."
+ "system language is unsupported or differs from the siri language."
- "Colocated WiFi check: isStandalone6G=false"
- "Colocated WiFi check: no current network"
- "Colocated WiFi check: no network name"
- "Colocated WiFi check: no other same LAN"
- "Colocated WiFi check: same LAN, name=%s, isStandalone6G=%{bool}d"
- "_diagnostics._tcp"
- "_handleResult: failure: %@"
- "system and siri language are supported."
- "system language is unsupported."
```
