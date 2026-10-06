## LightSourceSupport

> `/System/Library/PrivateFrameworks/LightSourceSupport.framework/LightSourceSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf1d0` | `0xfd60` | **`+0xb90`** |
| `__TEXT.__oslogstring` | `0x863` | `0xa29` | **`+0x1c6`** |
| `__AUTH_CONST.__objc_const` | `0x30b0` | `0x3120` | **`+0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0x598` | `0x5c8` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x680` | `0x6a0` | **`+0x20`** |
| `__TEXT.__cstring` | `0xb7b` | `0xb98` | **`+0x1d`** |
| `__TEXT.__gcc_except_tab` | `0x42c` | `0x444` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xbac` | `0xbc4` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x608` | `0x620` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x3e0` | `0x3f0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x274` | `0x280` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x178` | `0x180` | **`+0x8`** |

### Other Changes

```diff

-8.0.74.0.0
+8.1.5.0.0

-  Functions: 462
-  Symbols:   987
-  CStrings:  228
+  Functions: 475
+  Symbols:   1005
+  CStrings:  242
Symbols:
+ -[LSSCAService _enabledIntegratedDisplayIds]
+ -[LSSCAService _integratedDisplayWithId:]
+ -[LSSController _handleDisplayLinkStall]
+ -[LSSDisplayLinkResampler displayLinkStalledHandler]
+ -[LSSDisplayLinkResampler setDisplayLinkStalledHandler:]
+ GCC_except_table17
+ _OBJC_CLASS_$_NSMutableString
+ _OBJC_IVAR_$_LSSDisplayLinkResampler._displayLinkStalledHandler
+ _OBJC_IVAR_$_LSSDisplayLinkResampler._lastFireTime
+ _OBJC_IVAR_$_LSSDisplayLinkResampler._stallReported
+ _OUTLINED_FUNCTION_10
+ _OUTLINED_FUNCTION_11
+ _OUTLINED_FUNCTION_12
+ _OUTLINED_FUNCTION_13
+ ___32-[LSSController _setProviderTo:]_block_invoke
+ ___32-[LSSController _setProviderTo:]_block_invoke_2
+ ___NSArray0__struct
+ _objc_release_x28
+ _objc_retain
- -[LSSCAService _integratedDisplayUsingGlobalLight]
CStrings:
+ " "
+ "%s%u:%s%s"
+ "+light"
+ "Q"
+ "changing provider: %{public}@"
+ "changing provider: %{public}@. display: %u"
+ "display link display: %u. active display"
+ "display link display: %u. using global light"
+ "display link has not fired in %f s. its display is not refreshing"
+ "display link recovered"
+ "display link stalled on display %u but it is still the display we would pick"
+ "display link stalled. active display moved to %u"
+ "integrated displays: [%{public}@]"
+ "no enabled integrated display. falling back to main display: %u"
+ "off"
+ "on"
- "1"
- "changing provider"
```
