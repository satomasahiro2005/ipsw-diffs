## MatterSupport

> `/System/Library/Frameworks/MatterSupport.framework/MatterSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x338b0` | `0x33960` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0x432f` | `0x4323` | **`-0xc`** |
| `__TEXT.__unwind_info` | `0x1018` | `0x1020` | **`+0x8`** |

### Other Changes

```diff

-1468.5.0.0.6
+1479.0.0.1.0
Functions:
~ -[MTSKeychainStore allDataByKey] : 1128 -> 1124
~ ___74-[MTSDeviceSetupManager performDeviceSetupUsingRequest:completionHandler:]_block_invoke : 788 -> 792
~ +[MTSNetworkCredentialManager threadCredentialManagementEndpoint:] : 556 -> 552
~ sub_2437d0460 -> sub_2448e145c : 220 -> 232
~ sub_2437d053c -> sub_2448e1544 : 240 -> 252
~ sub_2437d2118 -> sub_2448e312c : 88 -> 100
~ sub_2437d24c4 -> sub_2448e34e4 : 1264 -> 1268
~ sub_2437d3a20 -> sub_2448e4a44 : 248 -> 252
~ sub_2437d58e0 -> sub_2448e6908 : 84 -> 80
~ sub_2437d5e48 -> sub_2448e6e6c : 352 -> 364
~ sub_2437d6090 -> sub_2448e70c0 : 184 -> 192
~ sub_2437d6148 -> sub_2448e7180 : 136 -> 144
~ sub_2437d61d0 -> sub_2448e7210 : 200 -> 216
~ sub_2437d6634 -> sub_2448e7684 : 100 -> 112
~ sub_2437d6698 -> sub_2448e76f4 : 136 -> 148
~ sub_2437d6ee0 -> sub_2448e7f48 : 2740 -> 2760
~ sub_2437d93bc -> sub_2448ea438 : 800 -> 852
~ sub_2437defd4 -> sub_2448f0084 : 84 -> 80
~ sub_2437e0b60 -> sub_2448f1c0c : 1152 -> 1148
~ sub_2437e16ec -> sub_2448f2794 : 1032 -> 1028
~ sub_2437e3abc -> sub_2448f4b60 : 320 -> 332
~ sub_2437e5214 -> sub_2448f62c4 : 280 -> 276
~ sub_2437e5b5c -> sub_2448f6c08 : 472 -> 476
CStrings:
+ "[%{public}@] Failed to perform Matter device setup: %@"
+ "[%{public}@] [%{public}@] Failed to perform Matter device setup: %@"
- "[%{public}@] Failed to perform Matter device setup setup: %@"
- "[%{public}@] [%{public}@] Failed to perform Matter device setup setup: %@"
```
