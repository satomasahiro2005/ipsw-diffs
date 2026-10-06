## TVRemoteCore

> `/System/Library/PrivateFrameworks/TVRemoteCore.framework/TVRemoteCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x48670` | `0x4880c` | **`+0x19c`** |
| `__DATA_CONST.__objc_selrefs` | `0x3090` | `0x3100` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0x9f88` | `0x9fe0` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x64d0` | `0x6528` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0x6b90` | `0x6bd5` | **`+0x45`** |
| `__AUTH_CONST.__cfstring` | `0x4a60` | `0x4a80` | **`+0x20`** |
| `__TEXT.__const` | `0x240` | `0x250` | **`+0x10`** |
| `__TEXT.__cstring` | `0x372c` | `0x3738` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x698` | `0x69c` | **`+0x4`** |

### Other Changes

```diff

-627.0.28.0.0
+627.10.45.0.0

-  Functions: 2139
-  Symbols:   3704
-  CStrings:  1299
+  Functions: 2142
+  Symbols:   3710
+  CStrings:  1300
Symbols:
+ -[TVRCRPCompanionLinkClientWrapper _updateFindMyRemoteSupport]
+ -[TVRCSiriRemoteInfo productID]
+ -[TVRCSiriRemoteInfo setProductID:]
+ GCC_except_table104
+ GCC_except_table114
+ GCC_except_table119
+ GCC_except_table124
+ GCC_except_table130
+ GCC_except_table134
+ GCC_except_table141
+ GCC_except_table146
+ GCC_except_table15
+ GCC_except_table32
+ GCC_except_table36
+ GCC_except_table41
+ GCC_except_table45
+ GCC_except_table80
+ GCC_except_table82
+ GCC_except_table84
+ GCC_except_table86
+ GCC_except_table88
+ GCC_except_table91
+ GCC_except_table94
+ GCC_except_table96
+ GCC_except_table98
+ _GestaltGetDeviceClass
+ _OBJC_IVAR_$_TVRCSiriRemoteInfo._productID
- GCC_except_table103
- GCC_except_table113
- GCC_except_table118
- GCC_except_table123
- GCC_except_table129
- GCC_except_table133
- GCC_except_table140
- GCC_except_table145
- GCC_except_table31
- GCC_except_table35
- GCC_except_table40
- GCC_except_table43
- GCC_except_table79
- GCC_except_table81
- GCC_except_table83
- GCC_except_table85
- GCC_except_table87
- GCC_except_table90
- GCC_except_table93
- GCC_except_table95
- GCC_except_table97
CStrings:
+ "Find my remote support level for %@: %@, device capability: %{bool}d, paired remote support: %{bool}d, paired remote productID: %@"
+ "Keyboard RemoteTextInput send operation - insert length:%lu deleteBackward:%lu forwardDelete:%lu"
+ "productID"
- "Find my remote support level for %@: %@, device capability: %{bool}d, paired remote support: %{bool}d"
- "Keyboard RemoteTextInput send payload string length: %lu"
```
