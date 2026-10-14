## InstalledContentLibrary

> `/System/Library/PrivateFrameworks/InstalledContentLibrary.framework/InstalledContentLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0xd700` | `0xd760` | **`+0x60`** |
| `__TEXT.__text` | `0xd3e20` | `0xd3e68` | **`+0x48`** |
| `__TEXT.__cstring` | `0x18c7e` | `0x18cbe` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x1078` | `0x1080` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 2513
-  Symbols:   3892
-  CStrings:  2309
+  Functions: 2514
+  Symbols:   3893
+  CStrings:  2312
Symbols:
+ _MIHasHomeExtensionEntitlement
Functions:
~ _MIClassifyAppManagementDomainValue : 168 -> 196
+ _MIHasHomeKitEntitlement
~ -[MIAppExtensionBundle extensionPoint] : 304 -> 332
CStrings:
+ "com.apple.AppClips"
+ "com.apple.Home.HomeExtension"
+ "com.apple.developer.home"
```
