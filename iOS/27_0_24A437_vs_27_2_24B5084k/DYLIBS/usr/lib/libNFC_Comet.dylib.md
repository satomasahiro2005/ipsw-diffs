## libNFC_Comet.dylib

> `/usr/lib/libNFC_Comet.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd6e38` | `0xd71a4` | **`+0x36c`** |
| `__TEXT.__cstring` | `0x41d46` | `0x41fa9` | **`+0x263`** |
| `__AUTH_CONST.__const` | `0x2ee0` | `0x2f50` | **`+0x70`** |

### Other Changes

```diff

-370.42.1.0.0
+371.7.0.0.0

-  CStrings:  6277
+  CStrings:  6284
Functions:
~ sub_2c07e8fa4 -> sub_2c6b1ffa4 : 796 -> 904
~ sub_2c084b074 -> sub_2c6b820e0 : 808 -> 904
~ sub_2c084b9ec -> sub_2c6b82ab8 : 832 -> 844
~ sub_2c084caac -> sub_2c6b83b84 : 1676 -> 1772
~ sub_2c084d138 -> sub_2c6b84270 : 776 -> 876
~ sub_2c084d540 -> sub_2c6b846dc : 764 -> 864
~ sub_2c084d954 -> sub_2c6b84b54 : 756 -> 856
~ sub_2c084dc48 -> sub_2c6b84eac : 652 -> 760
~ _phLibNfc_Mgt_TriggerNfccAssertion : 532 -> 480
~ sub_2c08647bc -> sub_2c6b9ba58 : 120 -> 112
~ sub_2c087aff4 -> sub_2c6bb2288 : 316 -> 340
~ sub_2c0880134 -> sub_2c6bb73e0 : 1092 -> 1172
~ sub_2c0882f5c -> sub_2c6bba258 : 252 -> 284
~ sub_2c08839ec -> sub_2c6bbad08 : 720 -> 800
CStrings:
+ "MW Version NFC5.1_R5.10"
+ "phLibNfc_SM_Main_DiscTransComplete:Invoking callback function, wStatus = "
+ "phLibNfc_SM_Main_InitTransComplete: phLibNfc_SM_eTrigNfccAssertion invoking callback function, wStatus = "
+ "phLibNfc_SM_Main_ListenActiveTransComplete:Invoking callback function, wStatus = "
+ "phLibNfc_SM_Main_ListenReceiveTransComplete:Invoking callback function, wStatus = "
+ "phLibNfc_SM_Main_ListenSendTransComplete:Invoking callback function, wStatus = "
+ "phLibNfc_SM_Main_ListenSleepTransComplete:Invoking callback function, wStatus = "
+ "phLibNfc_SM_Main_PollActiveTransComplete:Invoking callback function, wStatus = "
+ "phLibNfc_SM_Main_PollDiscoveredTransComplete:Invoking callback function, wStatus = "
- "MW Version NFC5.1_R5.B"
- "TriggerNfccAssertion:Invoking callback function, wStatus = "
```
