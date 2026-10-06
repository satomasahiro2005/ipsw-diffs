## ChronoServices

> `/System/Library/PrivateFrameworks/ChronoServices.framework/ChronoServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1015d0` | `0x101b1c` | **`+0x54c`** |
| `__TEXT.__oslogstring` | `0x55de` | `0x567e` | **`+0xa0`** |
| `__TEXT.__gcc_except_tab` | `0xac38` | `0xacc0` | **`+0x88`** |
| `__AUTH_CONST.__cfstring` | `0x5260` | `0x52c0` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x1e70` | `0x1ec0` | **`+0x50`** |
| `__TEXT.__cstring` | `0x5ac5` | `0x5b15` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x829c` | `0x82ec` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0x20250` | `0x20298` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x6be8` | `0x6c28` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x5c90` | `0x5cb0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x3198` | `0x31b8` | **`+0x20`** |
| `__DATA.__bss` | `0x9950` | `0x9960` | **`+0x10`** |
| `__TEXT.__const` | `0x7a38` | `0x7a48` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1578` | `0x1580` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x74c` | `0x750` | **`+0x4`** |

### Other Changes

```diff

-740.0.0.0.0
+749.0.1.0.0

-  Functions: 7337
-  Symbols:   6551
-  CStrings:  1329
+  Functions: 7347
+  Symbols:   6569
+  CStrings:  1334
Symbols:
+ +[NSProcessInfo(ChronoServices) chs_isStandByWidgetRendererProcess]
+ -[CHSInlineTextParameters setUsesCompactDateSpacing:]
+ -[CHSInlineTextParameters usesCompactDateSpacing]
+ -[CHSToolServiceConnection setExtensionHidden:forExtensionBundleIdentifiers:completion:]
+ -[CHSToolSupportService setExtensionHidden:forExtensionBundleIdentifiers:completion:]
+ GCC_except_table109
+ GCC_except_table133
+ GCC_except_table148
+ GCC_except_table158
+ GCC_except_table159
+ GCC_except_table163
+ GCC_except_table167
+ GCC_except_table168
+ GCC_except_table171
+ GCC_except_table183
+ GCC_except_table196
+ GCC_except_table197
+ GCC_except_table201
+ GCC_except_table204
+ GCC_except_table205
+ GCC_except_table208
+ GCC_except_table211
+ GCC_except_table212
+ GCC_except_table216
+ GCC_except_table219
+ GCC_except_table220
+ GCC_except_table223
+ GCC_except_table254
+ GCC_except_table261
+ GCC_except_table269
+ GCC_except_table270
+ GCC_except_table274
+ GCC_except_table276
+ GCC_except_table278
+ GCC_except_table282
+ GCC_except_table285
+ GCC_except_table288
+ GCC_except_table73
+ _BSSizeRoundForScale
+ _OBJC_IVAR_$_CHSInlineTextParameters._usesCompactDateSpacing
+ ___35-[CHSInlineTextParameters isEqual:]_block_invoke_13
+ ___67+[NSProcessInfo(ChronoServices) chs_isStandByWidgetRendererProcess]_block_invoke
+ ___88-[CHSToolServiceConnection setExtensionHidden:forExtensionBundleIdentifiers:completion:]_block_invoke
+ ___88-[CHSToolServiceConnection setExtensionHidden:forExtensionBundleIdentifiers:completion:]_block_invoke_2
+ ___block_descriptor_49_ea8_32s40bs_e17_v16?0"NSError"8ls32l8s40l8
+ ___block_descriptor_57_ea8_32s40s48bs_e5_v8?0ls32l8s40l8s48l8
+ _chs_isStandByWidgetRendererProcess.isStandByWidgetRendererProcess
+ _chs_isStandByWidgetRendererProcess.onceToken
- GCC_except_table108
- GCC_except_table142
- GCC_except_table153
- GCC_except_table154
- GCC_except_table161
- GCC_except_table162
- GCC_except_table169
- GCC_except_table182
- GCC_except_table194
- GCC_except_table195
- GCC_except_table199
- GCC_except_table200
- GCC_except_table203
- GCC_except_table206
- GCC_except_table209
- GCC_except_table210
- GCC_except_table213
- GCC_except_table214
- GCC_except_table218
- GCC_except_table222
- GCC_except_table248
- GCC_except_table255
- GCC_except_table259
- GCC_except_table266
- GCC_except_table267
- GCC_except_table272
- GCC_except_table273
- GCC_except_table279
- GCC_except_table283
- GCC_except_table287
CStrings:
+ "Received set extension hidden (%d) response for %lu extensions, error: %@"
+ "Unable to deliver set extension hidden request; unable to obtain the remote target"
+ "com.apple.chrono.WidgetRenderer-StandBy"
+ "ucds"
+ "usesCompactDateSpacing"
```
