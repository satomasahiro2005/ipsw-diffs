## libEmbeddedSystemAUs.dylib

> `/System/Library/Frameworks/AudioToolbox.framework/libEmbeddedSystemAUs.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd3cac` | `0xd3dd4` | **`+0x128`** |
| `__TEXT.__oslogstring` | `0xc28c` | `0xc2cc` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x794c` | `0x7958` | **`+0xc`** |

### Other Changes

```diff

-1638.208.0.0.0
+1638.209.1.0.0

-  CStrings:  1992
+  CStrings:  1993
Functions:
~ ____ZN20AudioCapturerManager10InitializeEv_block_invoke : 1820 -> 1804
~ __ZZN10AURemoteIO5StartEvENK3$_0clE8TapPointRK27AudioStreamBasicDescriptionPKcb : 1908 -> 2220
CStrings:
+ "%25s:%-5d AURemoteIO::Start: cannot capture %s; bus is disabled"
```
