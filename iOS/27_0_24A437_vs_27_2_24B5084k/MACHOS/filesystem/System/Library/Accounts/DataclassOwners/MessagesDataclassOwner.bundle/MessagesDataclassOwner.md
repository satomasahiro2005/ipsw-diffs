## MessagesDataclassOwner

> `/System/Library/Accounts/DataclassOwners/MessagesDataclassOwner.bundle/MessagesDataclassOwner`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2108` | `0x217c` | **`+0x74`** |
| `__TEXT.__oslogstring` | `0x79f` | `0x7f0` | **`+0x51`** |
| `__TEXT.__auth_stubs` | `0x290` | `0x2a0` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x84a` | `0x855` | **`+0xb`** |
| `__DATA_CONST.__auth_got` | `0x158` | `0x160` | **`+0x8`** |
| `__TEXT.__const` | `0x90` | `0x98` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x2e8` | `0x2e4` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1491.100.1.2.25
+1491.200.63.2.1

-  Symbols:   74
+  Symbols:   75
Symbols:
+ _IMCloudKitCanToggleMiCSwitchWithBroadcastState
Functions:
~ sub_1c24 : 864 -> 828
~ sub_1fec -> sub_1fc8 : 580 -> 664
~ sub_2434 -> sub_2464 : 600 -> 652
~ sub_268c -> sub_26f0 : 264 -> 280
CStrings:
+ "Asking imagent to set Messages in iCloud enabled: %d (our local view of enablement is %d)"
+ "Not eligible as account does not support DeviceToDeviceEncryption"
+ "Signal eligible_semaphore, canToggleMiCSwitch: %@"
+ "Timeout eligible_semaphore; letting the request through for imagent to judge"
+ "Timeout enable_semaphore; accepting the request and leaving the switch for imagent to reconcile"
+ "removeObserver:name:object:"
- "Not eligible as account does not support DeviceToDeviceEncryption, or iCloud & iMsg accounts do not match up"
- "Signal eligible_semaphore, isEligible: %@"
- "Timeout eligible_semaphore, isEligible: %@"
- "Timeout enable_semaphore, didSucceed: %d"
- "mocAccountsMatch"
- "setCloudEnable: Did nothing as it was already enabled/disabled"
```
