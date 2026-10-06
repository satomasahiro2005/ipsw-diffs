## HomeKitDaemonShared

> `/System/Library/PrivateFrameworks/HomeKitDaemonShared.framework/HomeKitDaemonShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xae34` | `0xb450` | **`+0x61c`** |
| `__AUTH_CONST.__objc_const` | `0x1770` | `0x1a08` | **`+0x298`** |
| `__TEXT.__objc_methlist` | `0xbac` | `0xcb4` | **`+0x108`** |
| `__AUTH_CONST.__cfstring` | `0x720` | `0x820` | **`+0x100`** |
| `__DATA.__data` | `0x578` | `0x638` | **`+0xc0`** |
| `__DATA_CONST.__objc_selrefs` | `0x750` | `0x7c8` | **`+0x78`** |
| `__TEXT.__cstring` | `0x574` | `0x5e4` | **`+0x70`** |
| `__AUTH.__objc_data` | `0x240` | `0x290` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x298` | `0x2c0` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0xc0` | `0xe0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x338` | `0x350` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x78` | `0x88` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x348` | `0x350` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x170` | `0x178` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x40` | `0x48` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x30` | `0x38` | **`+0x8`** |

### Other Changes

```diff

-1468.5.0.0.6
+1479.0.0.1.0

-  Functions: 249
-  Symbols:   554
-  CStrings:  172
+  Functions: 264
+  Symbols:   602
+  CStrings:  180
Symbols:
+ +[HMDNFCTagInfo supportsSecureCoding]
+ -[HMDNFCTagInfo .cxx_destruct]
+ -[HMDNFCTagInfo encodeWithCoder:]
+ -[HMDNFCTagInfo initWithCoder:]
+ -[HMDNFCTagInfo initWithSetupURLString:tagIdentifier:technology:ndefData:]
+ -[HMDNFCTagInfo initWithSetupURLString:tagIdentifier:technology:ndefData:mfiToken:mfiTokenUUID:]
+ -[HMDNFCTagInfo mfiTokenUUID]
+ -[HMDNFCTagInfo mfiToken]
+ -[HMDNFCTagInfo ndefData]
+ -[HMDNFCTagInfo setupURLString]
+ -[HMDNFCTagInfo tagIdentifier]
+ -[HMDNFCTagInfo technology]
+ -[HMDStatusChannelObserveLogEvent initWithChannelPrefix:payloadType:]
+ -[HMDStatusChannelObserveLogEvent initWithChannelPrefix:payloadType:count:]
+ -[HMDStatusChannelObserveLogEvent payloadType]
+ -[HMDStatusChannelPublishLogEvent initWithChannelPrefix:isRetry:payloadType:]
+ -[HMDStatusChannelPublishLogEvent initWithChannelPrefix:isRetry:payloadType:count:]
+ -[HMDStatusChannelPublishLogEvent payloadType]
+ _HMDNFCTagXPCMachServiceName
+ _HMDStatusChannelPayloadTypePersistent
+ _HMDStatusChannelPayloadTypePresence
+ _OBJC_CLASS_$_HMDNFCTagInfo
+ _OBJC_CLASS_$_NSData
+ _OBJC_IVAR_$_HMDNFCTagInfo._mfiToken
+ _OBJC_IVAR_$_HMDNFCTagInfo._mfiTokenUUID
+ _OBJC_IVAR_$_HMDNFCTagInfo._ndefData
+ _OBJC_IVAR_$_HMDNFCTagInfo._setupURLString
+ _OBJC_IVAR_$_HMDNFCTagInfo._tagIdentifier
+ _OBJC_IVAR_$_HMDNFCTagInfo._technology
+ _OBJC_IVAR_$_HMDStatusChannelObserveLogEvent._payloadType
+ _OBJC_IVAR_$_HMDStatusChannelPublishLogEvent._payloadType
+ _OBJC_METACLASS_$_HMDNFCTagInfo
+ __OBJC_$_CLASS_METHODS_HMDNFCTagInfo
+ __OBJC_$_CLASS_PROP_LIST_HMDNFCTagInfo
+ __OBJC_$_CLASS_PROP_LIST_NSSecureCoding
+ __OBJC_$_INSTANCE_METHODS_HMDNFCTagInfo
+ __OBJC_$_INSTANCE_VARIABLES_HMDNFCTagInfo
+ __OBJC_$_PROP_LIST_HMDNFCTagInfo
+ __OBJC_$_PROTOCOL_CLASS_METHODS_NSSecureCoding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSCoding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSCoding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSSecureCoding
+ __OBJC_$_PROTOCOL_REFS_NSSecureCoding
+ __OBJC_CLASS_PROTOCOLS_$_HMDNFCTagInfo
+ __OBJC_CLASS_RO_$_HMDNFCTagInfo
+ __OBJC_LABEL_PROTOCOL_$_NSCoding
+ __OBJC_LABEL_PROTOCOL_$_NSSecureCoding
+ __OBJC_METACLASS_RO_$_HMDNFCTagInfo
+ __OBJC_PROTOCOL_$_NSCoding
+ __OBJC_PROTOCOL_$_NSSecureCoding
+ _objc_retain_x25
- -[HMDStatusChannelObserveLogEvent initWithChannelPrefix:count:]
- -[HMDStatusChannelPublishLogEvent initWithChannelPrefix:isRetry:]
- -[HMDStatusChannelPublishLogEvent initWithChannelPrefix:isRetry:count:]
CStrings:
+ "Presence"
+ "com.apple.homed.xpc.nfc.tag"
+ "mfiToken"
+ "mfiTokenUUID"
+ "ndefData"
+ "setupURLString"
+ "tagIdentifier"
+ "technology"
```
