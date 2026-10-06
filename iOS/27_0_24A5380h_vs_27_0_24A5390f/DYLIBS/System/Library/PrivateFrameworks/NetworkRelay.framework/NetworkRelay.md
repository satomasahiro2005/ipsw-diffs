## NetworkRelay

> `/System/Library/PrivateFrameworks/NetworkRelay.framework/NetworkRelay`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x78c1c` | `0x79568` | **`+0x94c`** |
| `__TEXT.__cstring` | `0xffbd` | `0x10178` | **`+0x1bb`** |
| `__AUTH_CONST.__cfstring` | `0x5120` | `0x5140` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x5150` | `0x5170` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xb48` | `0xb60` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x1f4c` | `0x1f64` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x10a8` | `0x10b8` | **`+0x10`** |
| `__DATA_CONST.__const` | `0xd10` | `0xd18` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x9f0` | `0x9f8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x550` | `0x554` | **`+0x4`** |

### Other Changes

```diff

-914.0.14.502.2
+914.0.22.0.1

-  Functions: 1046
-  Symbols:   2261
-  CStrings:  1964
+  Functions: 1048
+  Symbols:   2265
+  CStrings:  1974
Symbols:
+ -[NRMeshPreferences startNANLinkForPeers:]
+ -[NRMeshPreferences stopNANLinkForPeers:]
+ _OBJC_IVAR_$_NRMeshPreferences._nanPeerSet
+ _nrXPCKeyMeshPreferencesNANPeerList
CStrings:
+ "%02x%02x%02x%02x.%s"
+ "%s%.30s:%-4d %@ startNANLinkForPeers: Terminus_ExplicitNANControl is OFF, ignoring"
+ "%s%.30s:%-4d %@ started NAN for %lu peers, total %lu"
+ "%s%.30s:%-4d %@ stopNANLinkForPeers: Terminus_ExplicitNANControl is OFF, ignoring"
+ "%s%.30s:%-4d %@ stopped NAN for %lu peers, %lu remaining"
+ "-[NRMeshPreferences startNANLinkForPeers:]"
+ "-[NRMeshPreferences stopNANLinkForPeers:]"
+ "AirPlay"
+ "MeshPreferencesNANPeerList"
+ "Terminus_ExplicitNANControl"
```
