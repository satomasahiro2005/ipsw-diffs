## IOUSBLib

> `/System/Library/Extensions/IOUSBHostFamily.kext/PlugIns/IOUSBLib.bundle/IOUSBLib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__gcc_except_tab` | `0x80` | `0x7c` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1616.0.0.0.0
+1617.0.1.0.0
Functions:
~ __ZN13IOUSBIUnknown24_versionNumberFromStringEPK10__CFString : 544 -> 548
~ __ZN16IOUSBDeviceClassD2Ev : 236 -> 232
~ __ZN16IOUSBDeviceClass21CacheConfigDescriptorEv : 392 -> 388
~ __ZN16IOUSBDeviceClass30GetBandwidthAvailableForDeviceEPj : 84 -> 80
~ __ZN19IOUSBInterfaceClassD2Ev : 260 -> 256
~ __ZN19IOUSBInterfaceClass21GetBandwidthAvailableEPj : 84 -> 80
~ __ZN19IOUSBInterfaceClass18ReadIsochPipeAsyncEhPvyjP14IOUSBIsocFramePFvS0_iS0_ES0_ : 316 -> 324
~ __ZN19IOUSBInterfaceClass19WriteIsochPipeAsyncEhPvyjP14IOUSBIsocFramePFvS0_iS0_ES0_ : 320 -> 328
~ __ZN19IOUSBInterfaceClass28LowLatencyReadIsochPipeAsyncEhPvyjjP24IOUSBLowLatencyIsocFramePFvS0_iS0_ES0_ : 320 -> 328
~ __ZN19IOUSBInterfaceClass29LowLatencyWriteIsochPipeAsyncEhPvyjjP24IOUSBLowLatencyIsocFramePFvS0_iS0_ES0_ : 324 -> 332
~ __ZN19IOUSBInterfaceClass21CacheConfigDescriptorEv : 468 -> 460
~ __ZN19IOUSBInterfaceClass18FindNextDescriptorEPKvh : 280 -> 272
```
