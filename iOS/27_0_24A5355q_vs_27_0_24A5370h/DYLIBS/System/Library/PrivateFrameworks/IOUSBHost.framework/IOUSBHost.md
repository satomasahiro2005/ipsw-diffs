## IOUSBHost

> `/System/Library/PrivateFrameworks/IOUSBHost.framework/IOUSBHost`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x160cc` | `0x16158` | **`+0x8c`** |
| `__TEXT.__unwind_info` | `0x328` | `0x330` | **`+0x8`** |

### Other Changes

```diff

-1616.0.0.0.0
+1617.0.1.0.0
Functions:
~ _IOUSBGetNextDescriptor : 92 -> 96
~ _IOUSBGetNextAssociatedDescriptor : 196 -> 208
~ _IOUSBGetNextAssociatedDescriptorWithType : 236 -> 244
~ _IOUSBGetNextCapabilityDescriptor : 92 -> 96
~ ___39-[IOUSBHostControllerInterface destroy]_block_invoke : 388 -> 396
~ -[IOUSBHostControllerInterface doorbellAsyncCallbackWithResult:length:error:] : 1164 -> 1160
~ -[IOUSBHostControllerInterface descriptionForMessage:] : 1528 -> 1544
~ _IOFindNameForValue : 68 -> 76
~ _IOUSBHostCIMessageTypeToString : 84 -> 96
~ _IOUSBHostCIMessageStatusToString : 84 -> 96
~ _IOUSBHostCILinkStateToString : 84 -> 96
~ _IOUSBHostCIDeviceSpeedToString : 84 -> 96
~ _IOUSBHostCIExceptionTypeToString : 88 -> 100
~ _IOUSBHostCIPortStateToString : 88 -> 100
~ _IOUSBHostCIEndpointStateToString : 88 -> 100
```
