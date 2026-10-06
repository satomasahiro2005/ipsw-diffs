## com.apple.driver.AppleTypeCPhy

> `com.apple.driver.AppleTypeCPhy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x11db8` | `0x12e44` | **`+0x108c`** |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x2d0` | **`+0x2d0`** |
| `__TEXT.__cstring` | `0x1792` | `0x1970` | **`+0x1de`** |
| `__TEXT.__os_log` | `0x1267` | `0x1440` | **`+0x1d9`** |

### Other Changes

```diff

-311.0.0.0.0
+316.0.0.0.0

-  CStrings:  169
+  CStrings:  178
Functions:
~ __ZN13AppleTypeCPhy5startEP9IOService : 4268 -> 4288
~ __ZN13AppleTypeCPhy4stopEP9IOService : 1548 -> 1540
~ __ZN13AppleTypeCPhy4openEP22AppleTypeCPhyInterface23AppleTypeCPhyPowerLeveljj : 1372 -> 1728
~ ____ZN13AppleTypeCPhy4openEP22AppleTypeCPhyInterface23AppleTypeCPhyPowerLeveljj_block_invoke : 7452 -> 11204
~ ____ZN13AppleTypeCPhy5closeEP22AppleTypeCPhyInterface_block_invoke : 3548 -> 3552
~ ____ZN13AppleTypeCPhy18serializeLaneStateEPvP11OSSerialize_block_invoke : 1036 -> 1032
~ ____ZN13AppleTypeCPhy20serializeTunnelStateEPvP11OSSerialize_block_invoke : 952 -> 948
~ ____ZN13AppleTypeCPhy18serializePclkStateEPvP11OSSerialize_block_invoke : 1400 -> 1396
~ sub_fffffff009960bc8 -> sub_fffffff0099bf3f8 : 504 -> 500
~ sub_fffffff009960dc0 -> sub_fffffff0099bf5ec : 80 -> 76
~ sub_fffffff009960e10 -> sub_fffffff0099bf638 : 256 -> 252
~ ____ZN13AppleTypeCPhy16assignLaneClientEv_block_invoke : 1728 -> 1720
~ sub_fffffff009963c34 -> sub_fffffff0099c2450 : 164 -> 176
~ sub_fffffff009964668 -> sub_fffffff0099c2e90 : 164 -> 172
~ sub_fffffff00996504c -> sub_fffffff0099c387c : 1252 -> 1276
~ sub_fffffff0099664a0 -> sub_fffffff0099c4ce8 : 272 -> 296
~ ____ZN13AppleTypeCPhy24addDisplayPortPclkClientEP33AppleTypeCPhyDisplayPortInterfacehjj_block_invoke : 1504 -> 1552
~ ____ZN13AppleTypeCPhy27removeDisplayPortPclkClientEP33AppleTypeCPhyDisplayPortInterface_block_invoke : 776 -> 808
~ sub_fffffff0099673d8 -> sub_fffffff0099c5c88 : 1372 -> 1368
~ sub_fffffff009967b58 -> sub_fffffff0099c6404 : 260 -> 256
~ sub_fffffff009967d20 -> sub_fffffff0099c65c8 : 208 -> 204
~ sub_fffffff009969f74 -> sub_fffffff0099c8818 : 496 -> 504
CStrings:
+ "%s@%s: %s::%s: USB2 timeout: blocked by %s (type %d, power %d)\n"
+ "%s@%s: %s::%s: USB2 wait aborted: current owner %s\n"
+ "%s@%s: %s::%s: configureLanes failed: 0x%08x\n"
+ "%s@%s: %s::%s: configureUSB2 failed: 0x%08x\n"
+ "%s@%s: %s::%s: hibernate resume timeout: USB2=%s, Lane0=%s, Lane1=%s\n"
+ "%s@%s: %s::%s: lane timeout: need %d lanes, have %d. Owners: L0=%s, L1=%s\n"
+ "%s@%s: %s::%s: lane wait aborted: have %d/%d lanes. Owners: L0=%s, L1=%s\n"
+ "%s@%s: %s::%s: open failed: NULL client\n"
+ "%s@%s: %s::%s: owner %s type %d powerLevel %d options 0x%08x result 0x%08x\n"
+ "none"
- "%s@%s: %s::%s: owner %s type %d options 0x%08x completed with 0x%08x\n"
```
