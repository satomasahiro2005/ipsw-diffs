## SEService

> `/System/Library/PrivateFrameworks/SEService.framework/SEService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11433c` | `0x114224` | **`-0x118`** |
| `__AUTH_CONST.__cfstring` | `0x46a0` | `0x46e0` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x83f8` | `0x8428` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x3cb4` | `0x3ccc` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x1ac8` | `0x1ab4` | **`-0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b68` | `0x1b78` | **`+0x10`** |
| `__TEXT.__cstring` | `0x8e75` | `0x8e85` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x5388` | `0x5380` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x390` | `0x394` | **`+0x4`** |

### Other Changes

```diff

-70.37.0.0.0
+70.39.1.0.0

-  Functions: 7228
-  Symbols:   4701
-  CStrings:  1353
+  Functions: 7231
+  Symbols:   4703
+  CStrings:  1355
Symbols:
+ -[SEEndPoint revocationReason]
+ -[SEEndPoint setRevocationReason:]
+ GCC_except_table100
+ GCC_except_table102
+ GCC_except_table104
+ GCC_except_table106
+ GCC_except_table108
+ GCC_except_table110
+ GCC_except_table112
+ GCC_except_table114
+ GCC_except_table116
+ GCC_except_table118
+ GCC_except_table120
+ GCC_except_table122
+ GCC_except_table124
+ GCC_except_table131
+ GCC_except_table133
+ GCC_except_table34
+ GCC_except_table37
+ GCC_except_table64
+ GCC_except_table70
+ GCC_except_table74
+ GCC_except_table77
+ GCC_except_table79
+ GCC_except_table81
+ GCC_except_table84
+ GCC_except_table87
+ GCC_except_table91
+ GCC_except_table93
+ GCC_except_table96
+ GCC_except_table98
+ _OBJC_IVAR_$_SEEndPoint._revocationReason
+ _SESEndPointDeleteWithReason
+ _SESEndPointRevokeWithReason
+ __SESEndPointDeleteWithReason
+ ___SESEndPointRevokeWithReason_block_invoke
+ ___SESEndPointRevokeWithReason_block_invoke_2
+ ____SESEndPointDeleteWithReason_block_invoke
+ ___block_descriptor_88_e8_32s40s48s56s64s72r80r_e5_v8?0ls32l8s40l8s48l8s56l8s64l8r72l8r80l8
- GCC_except_table101
- GCC_except_table103
- GCC_except_table105
- GCC_except_table107
- GCC_except_table109
- GCC_except_table111
- GCC_except_table113
- GCC_except_table115
- GCC_except_table117
- GCC_except_table119
- GCC_except_table121
- GCC_except_table123
- GCC_except_table130
- GCC_except_table132
- GCC_except_table31
- GCC_except_table33
- GCC_except_table36
- GCC_except_table48
- GCC_except_table66
- GCC_except_table69
- GCC_except_table72
- GCC_except_table76
- GCC_except_table78
- GCC_except_table80
- GCC_except_table83
- GCC_except_table86
- GCC_except_table90
- GCC_except_table92
- GCC_except_table95
- GCC_except_table97
- GCC_except_table99
- __SESEndPointDeleteWithSession
- ___SESEndPointDelete_block_invoke
- ___SESEndPointRevoke_block_invoke
- ___SESEndPointRevoke_block_invoke_2
- ____SESEndPointDeleteWithSession_block_invoke
- ___block_descriptor_80_e8_32s40s48s56s64r72r_e5_v8?0ls32l8s40l8s48l8s56l8r64l8r72l8
CStrings:
+ "\trevocationReason : %@\n"
+ "SESEndPointRevokeWithReason -> revokeEndPointWithIdentifier"
+ "Unspecified"
+ "_SESEndPointDeleteWithReason -> deleteEndPointWithProxy"
+ "revocationReason"
- "SESEndPointDelete -> deleteEndPointWithProxy"
- "SESEndPointRevoke -> revokeEndPointWithIdentifier"
- "_SESEndPointDeleteWithSession -> deleteEndPointWithProxy"
```
