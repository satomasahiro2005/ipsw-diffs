## SiriPlaybackControlSupport

> `/System/Library/PrivateFrameworks/SiriPlaybackControlSupport.framework/SiriPlaybackControlSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x81fa0` | `0x839c4` | **`+0x1a24`** |
| `__AUTH_CONST.__const` | `0x7e90` | `0x80d0` | **`+0x240`** |
| `__TEXT.__oslogstring` | `0x5eec` | `0x603c` | **`+0x150`** |
| `__TEXT.__swift5_capture` | `0x14ec` | `0x159c` | **`+0xb0`** |
| `__AUTH.__data` | `0x1330` | `0x12a8` | **`-0x88`** |
| `__TEXT.__eh_frame` | `0x1208` | `0x1190` | **`-0x78`** |
| `__TEXT.__swift5_typeref` | `0x19dc` | `0x1a1a` | **`+0x3e`** |
| `__TEXT.__const` | `0x4bb2` | `0x4be2` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1e80` | `0x1ea0` | **`+0x20`** |
| `__DATA.__data` | `0x1110` | `0x10f8` | **`-0x18`** |
| `__TEXT.__constg_swiftt` | `0x1dd4` | `0x1dc8` | **`-0xc`** |
| `__AUTH_CONST.__auth_got` | `0xf78` | `0xf80` | **`+0x8`** |

### Other Changes

```diff

-3600.20.2.0.0
+3600.26.3.0.0

+  - /System/Library/PrivateFrameworks/FlowToolTypes.framework/FlowToolTypes

-  Functions: 4243
-  Symbols:   1106
-  CStrings:  690
+  Functions: 4286
+  Symbols:   1118
+  CStrings:  695
Symbols:
+ _OUTLINED_FUNCTION_174
+ _OUTLINED_FUNCTION_175
+ _OUTLINED_FUNCTION_176
+ _OUTLINED_FUNCTION_177
+ ___swift_closure_destructor.14Tm
+ _symbolic _____Iegr_ 10Foundation6LocaleV
+ _symbolic _____SgIegr_ 26SiriPlaybackControlSupport11DeviceIdiomO
+ _symbolic _____Sgyc 26SiriPlaybackControlSupport11DeviceIdiomO
+ _symbolic _____Sgyc 26SiriPlaybackControlSupport12EndpointInfoV
+ _symbolic ______p 11SiriKitFlow11DeviceStateP
+ _symbolic _____yc 10Foundation6LocaleV
+ _type_layout_string 26SiriPlaybackControlSupport19DeviceStateProviderV
CStrings:
+ "DeviceStateProvider initialized with eager deviceState (deprecated)"
+ "DeviceStateProvider initialized with explicit idiom: %s"
+ "DeviceStateProvider initialized with lazy evaluation"
+ "DeviceStateProvider lazily evaluated device idiom: %s"
+ "DeviceStateProvider lazily evaluated siriLocale: %s"
```
