## libAppleTconUARPUpdater.dylib

> `/usr/lib/updaters/libAppleTconUARPUpdater.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6d514` | `0x702e4` | **`+0x2dd0`** |
| `__AUTH_CONST.__objc_const` | `0xc810` | `0xd1f8` | **`+0x9e8`** |
| `__TEXT.__objc_methlist` | `0x63ec` | `0x67fc` | **`+0x410`** |
| `__AUTH.__objc_data` | `0x32f0` | `0x36b0` | **`+0x3c0`** |
| `__TEXT.__cstring` | `0x7439` | `0x7675` | **`+0x23c`** |
| `__AUTH_CONST.__cfstring` | `0x5340` | `0x54c0` | **`+0x180`** |
| `__TEXT.__unwind_info` | `0x1938` | `0x1a50` | **`+0x118`** |
| `__DATA_CONST.__objc_selrefs` | `0x1ee0` | `0x1f70` | **`+0x90`** |
| `__DATA_CONST.__got` | `0x620` | `0x680` | **`+0x60`** |
| `__DATA_CONST.__objc_classlist` | `0x518` | `0x578` | **`+0x60`** |
| `__DATA_CONST.__objc_superrefs` | `0x508` | `0x568` | **`+0x60`** |
| `__DATA.__objc_ivar` | `0x870` | `0x8a4` | **`+0x34`** |
| `__TEXT.__oslogstring` | `0x37a1` | `0x377b` | **`-0x26`** |
| `__DATA.__bss` | `0x1188` | `0x1180` | **`-0x8`** |

### Other Changes

```diff

-1587.0.3.0.3
+1587.0.21.0.0

-  Functions: 2835
-  Symbols:   4627
-  CStrings:  1281
+  Functions: 2921
+  Symbols:   4806
+  CStrings:  1294
Symbols:
+ -[UARPEndpointLayer3 downstreamEndpointReachable:downstreamEndpointID:tlvs:]
+ -[UARPEndpointLayer3 notifyDownstreamEndpointReachable:tlvs:]
+ -[UARPEndpointLayer3 packetTracking:packetDirection:inFunction:]
+ -[UARPEndpointLayer3(Layer2EndpointCallbacks) layer2CallbackDownstreamReachable:tlvs:]
+ -[UARPMetaDataPersonalizationBoardID64 boardID]
+ -[UARPMetaDataPersonalizationBoardID64 description]
+ -[UARPMetaDataPersonalizationBoardID64 initWithLength:value:]
+ -[UARPMetaDataPersonalizationBoardID64 initWithPropertyListValue:relativeURL:]
+ -[UARPMetaDataPersonalizationBoardID64 init]
+ -[UARPMetaDataPersonalizationBoardID64 tlvValue]
+ -[UARPMetaDataPersonalizationDemotionProductionMode demotionProductionMode]
+ -[UARPMetaDataPersonalizationDemotionProductionMode description]
+ -[UARPMetaDataPersonalizationDemotionProductionMode initWithLength:value:]
+ -[UARPMetaDataPersonalizationDemotionProductionMode initWithPropertyListValue:relativeURL:]
+ -[UARPMetaDataPersonalizationDemotionProductionMode init]
+ -[UARPMetaDataPersonalizationDemotionProductionMode tlvValue]
+ -[UARPMetaDataPersonalizationDemotionSecurityMode demotionSecurityMode]
+ -[UARPMetaDataPersonalizationDemotionSecurityMode description]
+ -[UARPMetaDataPersonalizationDemotionSecurityMode initWithLength:value:]
+ -[UARPMetaDataPersonalizationDemotionSecurityMode initWithPropertyListValue:relativeURL:]
+ -[UARPMetaDataPersonalizationDemotionSecurityMode init]
+ -[UARPMetaDataPersonalizationDemotionSecurityMode tlvValue]
+ -[UARPMetaDataPersonalizationDigestListSize description]
+ -[UARPMetaDataPersonalizationDigestListSize digestListSize]
+ -[UARPMetaDataPersonalizationDigestListSize initWithLength:value:]
+ -[UARPMetaDataPersonalizationDigestListSize initWithPropertyListValue:relativeURL:]
+ -[UARPMetaDataPersonalizationDigestListSize init]
+ -[UARPMetaDataPersonalizationDigestListSize tlvValue]
+ -[UARPMetaDataPersonalizationFTABPayloadProductionModeHostOverride description]
+ -[UARPMetaDataPersonalizationFTABPayloadProductionModeHostOverride initWithLength:value:]
+ -[UARPMetaDataPersonalizationFTABPayloadProductionModeHostOverride initWithPropertyListValue:relativeURL:]
+ -[UARPMetaDataPersonalizationFTABPayloadProductionModeHostOverride init]
+ -[UARPMetaDataPersonalizationFTABPayloadProductionModeHostOverride productionModeHostOverride]
+ -[UARPMetaDataPersonalizationFTABPayloadProductionModeHostOverride tlvValue]
+ -[UARPMetaDataPersonalizationFTABPayloadSecurityModeHostOverride description]
+ -[UARPMetaDataPersonalizationFTABPayloadSecurityModeHostOverride initWithLength:value:]
+ -[UARPMetaDataPersonalizationFTABPayloadSecurityModeHostOverride initWithPropertyListValue:relativeURL:]
+ -[UARPMetaDataPersonalizationFTABPayloadSecurityModeHostOverride init]
+ -[UARPMetaDataPersonalizationFTABPayloadSecurityModeHostOverride securityModeHostOverride]
+ -[UARPMetaDataPersonalizationFTABPayloadSecurityModeHostOverride tlvValue]
+ -[UARPMetaDataPersonalizationMatchingData .cxx_destruct]
+ -[UARPMetaDataPersonalizationMatchingData description]
+ -[UARPMetaDataPersonalizationMatchingData initWithLength:value:]
+ -[UARPMetaDataPersonalizationMatchingData initWithPropertyListValue:relativeURL:]
+ -[UARPMetaDataPersonalizationMatchingData init]
+ -[UARPMetaDataPersonalizationMatchingData matchingData]
+ -[UARPMetaDataPersonalizationMatchingData tlvValue]
+ -[UARPMetaDataPersonalizationMatchingDataPayloadTags .cxx_destruct]
+ -[UARPMetaDataPersonalizationMatchingDataPayloadTags description]
+ -[UARPMetaDataPersonalizationMatchingDataPayloadTags initWithLength:value:]
+ -[UARPMetaDataPersonalizationMatchingDataPayloadTags initWithPropertyListValue:relativeURL:]
+ -[UARPMetaDataPersonalizationMatchingDataPayloadTags init]
+ -[UARPMetaDataPersonalizationMatchingDataPayloadTags payloadTags]
+ -[UARPMetaDataPersonalizationMatchingDataPayloadTags tlvValue]
+ -[UARPMetaDataPersonalizationMatchingDataProductRevisionMax description]
+ -[UARPMetaDataPersonalizationMatchingDataProductRevisionMax initWithLength:value:]
+ -[UARPMetaDataPersonalizationMatchingDataProductRevisionMax initWithPropertyListValue:relativeURL:]
+ -[UARPMetaDataPersonalizationMatchingDataProductRevisionMax init]
+ -[UARPMetaDataPersonalizationMatchingDataProductRevisionMax productRevisionMax]
+ -[UARPMetaDataPersonalizationMatchingDataProductRevisionMax tlvValue]
+ -[UARPMetaDataPersonalizationMatchingDataProductRevisionMin description]
+ -[UARPMetaDataPersonalizationMatchingDataProductRevisionMin initWithLength:value:]
+ -[UARPMetaDataPersonalizationMatchingDataProductRevisionMin initWithPropertyListValue:relativeURL:]
+ -[UARPMetaDataPersonalizationMatchingDataProductRevisionMin init]
+ -[UARPMetaDataPersonalizationMatchingDataProductRevisionMin productRevisionMin]
+ -[UARPMetaDataPersonalizationMatchingDataProductRevisionMin tlvValue]
+ -[UARPMetaDataPersonalizationMoreRequestsToFollow description]
+ -[UARPMetaDataPersonalizationMoreRequestsToFollow initWithLength:value:]
+ -[UARPMetaDataPersonalizationMoreRequestsToFollow initWithPropertyListValue:relativeURL:]
+ -[UARPMetaDataPersonalizationMoreRequestsToFollow init]
+ -[UARPMetaDataPersonalizationMoreRequestsToFollow moreRequestsToFollow]
+ -[UARPMetaDataPersonalizationMoreRequestsToFollow tlvValue]
+ -[UARPMetaDataPersonalizationSharedManifest description]
+ -[UARPMetaDataPersonalizationSharedManifest initWithLength:value:]
+ -[UARPMetaDataPersonalizationSharedManifest initWithPropertyListValue:relativeURL:]
+ -[UARPMetaDataPersonalizationSharedManifest init]
+ -[UARPMetaDataPersonalizationSharedManifest sharedManifest]
+ -[UARPMetaDataPersonalizationSharedManifest tlvValue]
+ -[UARPRTKitFTAB adjustSubfileLengthsAndOffsets]
+ -[UARPRTKitFTABSubfile updateSubfileOffset:]
+ _OBJC_CLASS_$_UARPMetaDataPersonalizationBoardID64
+ _OBJC_CLASS_$_UARPMetaDataPersonalizationDemotionProductionMode
+ _OBJC_CLASS_$_UARPMetaDataPersonalizationDemotionSecurityMode
+ _OBJC_CLASS_$_UARPMetaDataPersonalizationDigestListSize
+ _OBJC_CLASS_$_UARPMetaDataPersonalizationFTABPayloadProductionModeHostOverride
+ _OBJC_CLASS_$_UARPMetaDataPersonalizationFTABPayloadSecurityModeHostOverride
+ _OBJC_CLASS_$_UARPMetaDataPersonalizationMatchingData
+ _OBJC_CLASS_$_UARPMetaDataPersonalizationMatchingDataPayloadTags
+ _OBJC_CLASS_$_UARPMetaDataPersonalizationMatchingDataProductRevisionMax
+ _OBJC_CLASS_$_UARPMetaDataPersonalizationMatchingDataProductRevisionMin
+ _OBJC_CLASS_$_UARPMetaDataPersonalizationMoreRequestsToFollow
+ _OBJC_CLASS_$_UARPMetaDataPersonalizationSharedManifest
+ _OBJC_IVAR_$_UARPEndpointLayer3._packetQueue
+ _OBJC_IVAR_$_UARPMetaDataPersonalizationBoardID64._boardID
+ _OBJC_IVAR_$_UARPMetaDataPersonalizationDemotionProductionMode._demotionProductionMode
+ _OBJC_IVAR_$_UARPMetaDataPersonalizationDemotionSecurityMode._demotionSecurityMode
+ _OBJC_IVAR_$_UARPMetaDataPersonalizationDigestListSize._digestListSize
+ _OBJC_IVAR_$_UARPMetaDataPersonalizationFTABPayloadProductionModeHostOverride._productionModeHostOverride
+ _OBJC_IVAR_$_UARPMetaDataPersonalizationFTABPayloadSecurityModeHostOverride._securityModeHostOverride
+ _OBJC_IVAR_$_UARPMetaDataPersonalizationMatchingData._matchingData
+ _OBJC_IVAR_$_UARPMetaDataPersonalizationMatchingDataPayloadTags._payloadTags
+ _OBJC_IVAR_$_UARPMetaDataPersonalizationMatchingDataProductRevisionMax._productRevisionMax
+ _OBJC_IVAR_$_UARPMetaDataPersonalizationMatchingDataProductRevisionMin._productRevisionMin
+ _OBJC_IVAR_$_UARPMetaDataPersonalizationMoreRequestsToFollow._moreRequestsToFollow
+ _OBJC_IVAR_$_UARPMetaDataPersonalizationSharedManifest._sharedManifest
+ _OBJC_METACLASS_$_UARPMetaDataPersonalizationBoardID64
+ _OBJC_METACLASS_$_UARPMetaDataPersonalizationDemotionProductionMode
+ _OBJC_METACLASS_$_UARPMetaDataPersonalizationDemotionSecurityMode
+ _OBJC_METACLASS_$_UARPMetaDataPersonalizationDigestListSize
+ _OBJC_METACLASS_$_UARPMetaDataPersonalizationFTABPayloadProductionModeHostOverride
+ _OBJC_METACLASS_$_UARPMetaDataPersonalizationFTABPayloadSecurityModeHostOverride
+ _OBJC_METACLASS_$_UARPMetaDataPersonalizationMatchingData
+ _OBJC_METACLASS_$_UARPMetaDataPersonalizationMatchingDataPayloadTags
+ _OBJC_METACLASS_$_UARPMetaDataPersonalizationMatchingDataProductRevisionMax
+ _OBJC_METACLASS_$_UARPMetaDataPersonalizationMatchingDataProductRevisionMin
+ _OBJC_METACLASS_$_UARPMetaDataPersonalizationMoreRequestsToFollow
+ _OBJC_METACLASS_$_UARPMetaDataPersonalizationSharedManifest
+ __OBJC_$_INSTANCE_METHODS_UARPMetaDataPersonalizationBoardID64
+ __OBJC_$_INSTANCE_METHODS_UARPMetaDataPersonalizationDemotionProductionMode
+ __OBJC_$_INSTANCE_METHODS_UARPMetaDataPersonalizationDemotionSecurityMode
+ __OBJC_$_INSTANCE_METHODS_UARPMetaDataPersonalizationDigestListSize
+ __OBJC_$_INSTANCE_METHODS_UARPMetaDataPersonalizationFTABPayloadProductionModeHostOverride
+ __OBJC_$_INSTANCE_METHODS_UARPMetaDataPersonalizationFTABPayloadSecurityModeHostOverride
+ __OBJC_$_INSTANCE_METHODS_UARPMetaDataPersonalizationMatchingData
+ __OBJC_$_INSTANCE_METHODS_UARPMetaDataPersonalizationMatchingDataPayloadTags
+ __OBJC_$_INSTANCE_METHODS_UARPMetaDataPersonalizationMatchingDataProductRevisionMax
+ __OBJC_$_INSTANCE_METHODS_UARPMetaDataPersonalizationMatchingDataProductRevisionMin
+ __OBJC_$_INSTANCE_METHODS_UARPMetaDataPersonalizationMoreRequestsToFollow
+ __OBJC_$_INSTANCE_METHODS_UARPMetaDataPersonalizationSharedManifest
+ __OBJC_$_INSTANCE_VARIABLES_UARPMetaDataPersonalizationBoardID64
+ __OBJC_$_INSTANCE_VARIABLES_UARPMetaDataPersonalizationDemotionProductionMode
+ __OBJC_$_INSTANCE_VARIABLES_UARPMetaDataPersonalizationDemotionSecurityMode
+ __OBJC_$_INSTANCE_VARIABLES_UARPMetaDataPersonalizationDigestListSize
+ __OBJC_$_INSTANCE_VARIABLES_UARPMetaDataPersonalizationFTABPayloadProductionModeHostOverride
+ __OBJC_$_INSTANCE_VARIABLES_UARPMetaDataPersonalizationFTABPayloadSecurityModeHostOverride
+ __OBJC_$_INSTANCE_VARIABLES_UARPMetaDataPersonalizationMatchingData
+ __OBJC_$_INSTANCE_VARIABLES_UARPMetaDataPersonalizationMatchingDataPayloadTags
+ __OBJC_$_INSTANCE_VARIABLES_UARPMetaDataPersonalizationMatchingDataProductRevisionMax
+ __OBJC_$_INSTANCE_VARIABLES_UARPMetaDataPersonalizationMatchingDataProductRevisionMin
+ __OBJC_$_INSTANCE_VARIABLES_UARPMetaDataPersonalizationMoreRequestsToFollow
+ __OBJC_$_INSTANCE_VARIABLES_UARPMetaDataPersonalizationSharedManifest
+ __OBJC_$_PROP_LIST_UARPMetaDataPersonalizationBoardID64
+ __OBJC_$_PROP_LIST_UARPMetaDataPersonalizationDemotionProductionMode
+ __OBJC_$_PROP_LIST_UARPMetaDataPersonalizationDemotionSecurityMode
+ __OBJC_$_PROP_LIST_UARPMetaDataPersonalizationDigestListSize
+ __OBJC_$_PROP_LIST_UARPMetaDataPersonalizationFTABPayloadProductionModeHostOverride
+ __OBJC_$_PROP_LIST_UARPMetaDataPersonalizationFTABPayloadSecurityModeHostOverride
+ __OBJC_$_PROP_LIST_UARPMetaDataPersonalizationMatchingData
+ __OBJC_$_PROP_LIST_UARPMetaDataPersonalizationMatchingDataPayloadTags
+ __OBJC_$_PROP_LIST_UARPMetaDataPersonalizationMatchingDataProductRevisionMax
+ __OBJC_$_PROP_LIST_UARPMetaDataPersonalizationMatchingDataProductRevisionMin
+ __OBJC_$_PROP_LIST_UARPMetaDataPersonalizationMoreRequestsToFollow
+ __OBJC_$_PROP_LIST_UARPMetaDataPersonalizationSharedManifest
+ __OBJC_CLASS_RO_$_UARPMetaDataPersonalizationBoardID64
+ __OBJC_CLASS_RO_$_UARPMetaDataPersonalizationDemotionProductionMode
+ __OBJC_CLASS_RO_$_UARPMetaDataPersonalizationDemotionSecurityMode
+ __OBJC_CLASS_RO_$_UARPMetaDataPersonalizationDigestListSize
+ __OBJC_CLASS_RO_$_UARPMetaDataPersonalizationFTABPayloadProductionModeHostOverride
+ __OBJC_CLASS_RO_$_UARPMetaDataPersonalizationFTABPayloadSecurityModeHostOverride
+ __OBJC_CLASS_RO_$_UARPMetaDataPersonalizationMatchingData
+ __OBJC_CLASS_RO_$_UARPMetaDataPersonalizationMatchingDataPayloadTags
+ __OBJC_CLASS_RO_$_UARPMetaDataPersonalizationMatchingDataProductRevisionMax
+ __OBJC_CLASS_RO_$_UARPMetaDataPersonalizationMatchingDataProductRevisionMin
+ __OBJC_CLASS_RO_$_UARPMetaDataPersonalizationMoreRequestsToFollow
+ __OBJC_CLASS_RO_$_UARPMetaDataPersonalizationSharedManifest
+ __OBJC_METACLASS_RO_$_UARPMetaDataPersonalizationBoardID64
+ __OBJC_METACLASS_RO_$_UARPMetaDataPersonalizationDemotionProductionMode
+ __OBJC_METACLASS_RO_$_UARPMetaDataPersonalizationDemotionSecurityMode
+ __OBJC_METACLASS_RO_$_UARPMetaDataPersonalizationDigestListSize
+ __OBJC_METACLASS_RO_$_UARPMetaDataPersonalizationFTABPayloadProductionModeHostOverride
+ __OBJC_METACLASS_RO_$_UARPMetaDataPersonalizationFTABPayloadSecurityModeHostOverride
+ __OBJC_METACLASS_RO_$_UARPMetaDataPersonalizationMatchingData
+ __OBJC_METACLASS_RO_$_UARPMetaDataPersonalizationMatchingDataPayloadTags
+ __OBJC_METACLASS_RO_$_UARPMetaDataPersonalizationMatchingDataProductRevisionMax
+ __OBJC_METACLASS_RO_$_UARPMetaDataPersonalizationMatchingDataProductRevisionMin
+ __OBJC_METACLASS_RO_$_UARPMetaDataPersonalizationMoreRequestsToFollow
+ __OBJC_METACLASS_RO_$_UARPMetaDataPersonalizationSharedManifest
+ ___64-[UARPEndpointLayer3 packetTracking:packetDirection:inFunction:]_block_invoke
+ ___76-[UARPEndpointLayer3 downstreamEndpointReachable:downstreamEndpointID:tlvs:]_block_invoke
+ ___86-[UARPEndpointLayer3(Layer2EndpointCallbacks) layer2CallbackDownstreamReachable:tlvs:]_block_invoke
+ _uarpDownstreamEndpointProcessReachableMessage
+ _uarpPlatformDownstreamEndpointReachable2
+ _uarpProcessTLV2
+ _uarpProtocolSupportsDownstreamReachableTLVs
+ _uarpSendDownstreamEndpointReachable2
- -[UARPEndpointLayer3 notifyDownstreamEndpointReachable:]
- -[UARPEndpointLayer3 packetTracking:inFunction:]
- ___71-[UARPEndpointLayer3 downstreamEndpointReachable:downstreamEndpointID:]_block_invoke
- ___81-[UARPEndpointLayer3(Layer2EndpointCallbacks) layer2CallbackDownstreamReachable:]_block_invoke
- _composeFTAB.paddingBytes
- _uarpTransmitBufferUpstream
CStrings:
+ "%s: ESPRESSO: Message <type=0x%04x, id=0x%04x> Length too big ! expected <%u>, got <%u>"
+ "%s: Error creating payload at index %lu"
+ "%s: Failed to create payload at index %lu"
+ "-[UARPEndpointLayer3 downstreamEndpointReachable:downstreamEndpointID:tlvs:]_block_invoke"
+ "-[UARPEndpointLayer3 notifyDownstreamEndpointReachable:tlvs:]"
+ "-[UARPSuperBinaryLayer3 addPayloadWith4cc:payloadVersion:payloadIndex:]"
+ "Endpoint %@: Downstream Endpoint Reachable, ID = %u, TLVs = %@"
+ "Personalization Board ID (64 bits)"
+ "Personalization Digest List Size"
+ "Personalization FTAB Payload Production Mode Host Override"
+ "Personalization FTAB Payload Security Mode Host Override"
+ "Personalization Matching Data"
+ "Personalization Matching Data Payload Tags"
+ "Personalization Matching Data Product Revision Maximum"
+ "Personalization Matching Data Product Revision Minimum"
+ "Personalization More Requests to Follow"
+ "Personalization Payload Demotion Production Mode"
+ "Personalization Payload Demotion Security Mode"
+ "Shared Manifest"
+ "com.apple.uarp.endpoint.packet.parser"
+ "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\x831"
- "%s: ESPRESSO:Bonus Message <type=0x%04x, length=x0x%04x, id=0x%04x>"
- "%s: ESPRESSO:Message <type=0x%04x, id=0x%04x> Length too big ! expected <%u>, got <%u>"
- "%s: Padding before subfiles is off by %d bytes; adjust %d to %d"
- "%s: Padding subfile %c%c%c%c is off by %d bytes; pad from %d to %d"
- "-[UARPEndpointLayer3 downstreamEndpointReachable:downstreamEndpointID:]_block_invoke"
- "-[UARPEndpointLayer3 notifyDownstreamEndpointReachable:]"
- "Endpoint %@: Downstream Endpoint Reachable, ID = %u"
- "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0c1"
```
