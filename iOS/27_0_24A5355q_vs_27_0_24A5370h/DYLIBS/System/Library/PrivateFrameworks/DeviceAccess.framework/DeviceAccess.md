## DeviceAccess

> `/System/Library/PrivateFrameworks/DeviceAccess.framework/DeviceAccess`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x53f88` | `0x54714` | **`+0x78c`** |
| `__TEXT.__cstring` | `0x9f23` | `0xa0e3` | **`+0x1c0`** |
| `__AUTH_CONST.__objc_const` | `0x7e78` | `0x7fa0` | **`+0x128`** |
| `__TEXT.__objc_methlist` | `0x45fc` | `0x467c` | **`+0x80`** |
| `__AUTH_CONST.__cfstring` | `0x3520` | `0x3580` | **`+0x60`** |
| `__AUTH.__objc_data` | `0xb10` | `0xb60` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x12f0` | `0x1330` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x13e0` | `0x1408` | **`+0x28`** |
| `__DATA_CONST.__objc_arraydata` | `0x30` | `0x40` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f60` | `0x1f70` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x704` | `0x70c` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x540` | `0x548` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1e8` | `0x1f0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x180` | `0x188` | **`+0x8`** |

### Other Changes

```diff

-2700.22.0.0.0
+2700.26.0.0.0

-  Functions: 2280
-  Symbols:   3318
-  CStrings:  1494
+  Functions: 2294
+  Symbols:   3340
+  CStrings:  1508
Symbols:
+ +[DAExtensionCapabilityXPCStartConfiguration supportsSecureCoding]
+ -[DAExtensionCapabilityXPCStartConfiguration .cxx_destruct]
+ -[DAExtensionCapabilityXPCStartConfiguration encodeWithCoder:]
+ -[DAExtensionCapabilityXPCStartConfiguration encodeWithXPCObject:]
+ -[DAExtensionCapabilityXPCStartConfiguration initWithCoder:]
+ -[DAExtensionCapabilityXPCStartConfiguration initWithXPCObject:error:]
+ -[DAExtensionCapabilityXPCStartConfiguration sessionID]
+ -[DAExtensionCapabilityXPCStartConfiguration setSessionID:]
+ -[DASession _queue_XPCReceivedCurrentDeviceCapabilitiesChanged:]
+ GCC_except_table10
+ GCC_except_table117
+ GCC_except_table121
+ GCC_except_table32
+ GCC_except_table45
+ GCC_except_table51
+ GCC_except_table54
+ GCC_except_table62
+ GCC_except_table74
+ GCC_except_table76
+ GCC_except_table81
+ GCC_except_table87
+ GCC_except_table90
+ _DAExtensionCapabilityAllowedTransports
+ _DAExtensionTypeFromPointIdentifier
+ _OBJC_CLASS_$_DAExtensionCapabilityXPCStartConfiguration
+ _OBJC_IVAR_$_DAExtensionCapability._processSuspended
+ _OBJC_IVAR_$_DAExtensionCapabilityXPCStartConfiguration._sessionID
+ _OBJC_METACLASS_$_DAExtensionCapabilityXPCStartConfiguration
+ __OBJC_$_CLASS_METHODS_DAExtensionCapabilityXPCStartConfiguration
+ __OBJC_$_CLASS_PROP_LIST_DAExtensionCapabilityXPCStartConfiguration
+ __OBJC_$_INSTANCE_METHODS_DAExtensionCapabilityXPCStartConfiguration
+ __OBJC_$_INSTANCE_VARIABLES_DAExtensionCapabilityXPCStartConfiguration
+ __OBJC_$_PROP_LIST_DAExtensionCapabilityXPCStartConfiguration
+ __OBJC_CLASS_PROTOCOLS_$_DAExtensionCapabilityXPCStartConfiguration
+ __OBJC_CLASS_RO_$_DAExtensionCapabilityXPCStartConfiguration
+ __OBJC_METACLASS_RO_$_DAExtensionCapabilityXPCStartConfiguration
- GCC_except_table110
- GCC_except_table116
- GCC_except_table120
- GCC_except_table31
- GCC_except_table44
- GCC_except_table61
- GCC_except_table65
- GCC_except_table71
- GCC_except_table73
- GCC_except_table75
- GCC_except_table80
- GCC_except_table82
- GCC_except_table85
- GCC_except_table9
CStrings:
+ "### Failed to suspend capability process: %@, %@"
+ "%@ should start: %s"
+ "-[DADiscovery _activateDirect]_block_invoke_2"
+ "-[DASession _queue_XPCReceivedCurrentDeviceCapabilitiesChanged:]"
+ "CdCC"
+ "Current device capabilities changed: %@"
+ "Discovery Extension count : %lu"
+ "HasAliasScanning"
+ "Host session config instance identifier: '%@'"
+ "Resumed capability process: %@"
+ "Suspended capability process: %@"
+ "failed to configure extension process: %@"
+ "failed to resume capability process: %@"
+ "isProxPairing"
+ "sesID"
- "failed to configure extension process"
```
