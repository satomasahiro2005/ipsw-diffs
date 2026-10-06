## Matter

> `/System/Library/Frameworks/Matter.framework/Matter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x857ac8` | `0x85e05c` | **`+0x6594`** |
| `__TEXT.__gcc_except_tab` | `0xc4460` | `0xc6fe0` | **`+0x2b80`** |
| `__TEXT.__const` | `0x64189` | `0x651b9` | **`+0x1030`** |
| `__TEXT.__objc_methlist` | `0x5e054` | `0x5eedc` | **`+0xe88`** |
| `__AUTH_CONST.__objc_const` | `0x76178` | `0x76f20` | **`+0xda8`** |
| `__TEXT.__unwind_info` | `0x515b0` | `0x52070` | **`+0xac0`** |
| `__TEXT.__cstring` | `0x301aa` | `0x30b45` | **`+0x99b`** |
| `__AUTH_CONST.__const` | `0x1c820` | `0x1cdc0` | **`+0x5a0`** |
| `__AUTH_CONST.__cfstring` | `0x183c0` | `0x18900` | **`+0x540`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c7e8` | `0x1cd28` | **`+0x540`** |
| `__AUTH_CONST.__objc_intobj` | `0x6a68` | `0x6de0` | **`+0x378`** |
| `__AUTH.__objc_data` | `0x1e640` | `0x1e9b0` | **`+0x370`** |
| `__DATA_CONST.__const` | `0x12c40` | `0x12d08` | **`+0xc8`** |
| `__DATA.__objc_ivar` | `0x4038` | `0x40c0` | **`+0x88`** |
| `__TEXT.__oslogstring` | `0x1b37e` | `0x1b314` | **`-0x6a`** |
| `__DATA_CONST.__objc_classlist` | `0x30a0` | `0x30f8` | **`+0x58`** |
| `__DATA_CONST.__got` | `0x23b0` | `0x23f8` | **`+0x48`** |
| `__AUTH_CONST.__auth_got` | `0x998` | `0x9d8` | **`+0x40`** |
| `__DATA_CONST.__objc_superrefs` | `0x2248` | `0x2280` | **`+0x38`** |
| `__DATA.__bss` | `0x8f68` | `0x8f80` | **`+0x18`** |
| `__DATA.__data` | `0x6110` | `0x6118` | **`+0x8`** |

### Other Changes

```diff

-324.0.0.0.0
+331.0.0.0.0

+  - /System/Library/Frameworks/SystemConfiguration.framework/SystemConfiguration

-  Functions: 52652
-  Symbols:   3455
-  CStrings:  8934
+  Functions: 52975
+  Symbols:   3482
+  CStrings:  9001
Symbols:
+ _CFEqual
+ _CFStringCreateWithCStringNoCopy
+ _CFStringFind
+ _OBJC_CLASS_$_MTRAccountLoginClusterGetDeviceAuthURIParams
+ _OBJC_CLASS_$_MTRAccountLoginClusterGetDeviceAuthURIResponseParams
+ _OBJC_CLASS_$_MTRAmbientSensingUnionClusterContributorStatusChangeStruct
+ _OBJC_CLASS_$_MTRClusterAppleAccessoryConfiguration
+ _OBJC_CLASS_$_MTRClusterAppleProximityBLEAdvertising
+ _OBJC_CLASS_$_MTRMessagesClusterMessageNotPresentedEvent
+ _OBJC_CLASS_$_MTRProximityRangingClusterRangingConstraintStruct
+ _OBJC_CLASS_$_MTRPushAVStreamTransportClusterUpdateMotionZoneOptionsParams
+ _OBJC_METACLASS_$_MTRAccountLoginClusterGetDeviceAuthURIParams
+ _OBJC_METACLASS_$_MTRAccountLoginClusterGetDeviceAuthURIResponseParams
+ _OBJC_METACLASS_$_MTRAmbientSensingUnionClusterContributorStatusChangeStruct
+ _OBJC_METACLASS_$_MTRClusterAppleAccessoryConfiguration
+ _OBJC_METACLASS_$_MTRClusterAppleProximityBLEAdvertising
+ _OBJC_METACLASS_$_MTRMessagesClusterMessageNotPresentedEvent
+ _OBJC_METACLASS_$_MTRProximityRangingClusterRangingConstraintStruct
+ _OBJC_METACLASS_$_MTRPushAVStreamTransportClusterUpdateMotionZoneOptionsParams
+ _SCNetworkInterfaceGetInterfaceType
+ __SCNetworkInterfaceCreateWithBSDName
+ __SCNetworkInterfaceGetIOPath
+ __SCNetworkInterfaceIsHiddenConfiguration
+ __SCNetworkInterfaceIsHiddenInterface
+ _kCFAllocatorNull
+ _kSCNetworkInterfaceTypeEthernet
+ _kSCNetworkInterfaceTypeIEEE80211
CStrings:
+ "%s:%d false: %s"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CHIPFramework/connectedhomeip/src/protocols/bdx/AsyncTransferFacilitator.h"
+ "<%@: connectionID:%@; motionZones:%@; motionSensitivity:%@; >"
+ "<%@: contributorIndex:%@; previousContributorStatus:%@; currentContributorStatus:%@; >"
+ "<%@: contributorNodeID:%@; contributorEndpointID:%@; contributorName:%@; contributorStatus:%@; >"
+ "<%@: contributorStatusChange:%@; >"
+ "<%@: messageID:%@; priority:%@; messageControl:%@; startTime:%@; duration:%@; messageText:%@; responses:%@; languageCode:%@; messageURI:%@; >"
+ "<%@: messageID:%@; removedFromQueue:%@; fabricIndex:%@; >"
+ "<%@: role:%@; peerBLEDeviceID:%@; blerbcSecurityMode:%@; sessionKey:%@; >"
+ "<%@: technology:%@; frequencyBand:%@; bandwidth:%@; supportedRangingRoles:%@; rdrCapability:%@; periodicRangingSupport:%@; maxConcurrentSessions:%@; >"
+ "<%@: technology:%@; role:%@; enabled:%@; minRangingInterval:%@; maxSessionDuration:%@; maxRangingInstances:%@; >"
+ "<%@: technology:%@; wiFiRangingDeviceRoleConfig:%@; bleRangingDeviceRoleConfig:%@; bltChannelSoundingDeviceRoleConfig:%@; frequencyBand:%@; bandwidth:%@; trigger:%@; reportingCondition:%@; >"
+ "<%@: tripMechanism:%@; protectionClass:%@; protectionType:%@; maxContinuousOperatingVoltage:%@; maxVoltageProtection:%@; maxTemporaryVoltage:%@; nominalDischargeCurrent:%@; maximumDischargeCurrent:%@; ratedShortCircuitCurrent:%@; ratedShortTimeWithstandCurrent:%@; energyAbsorptionCapability:%@; responseTime:%@; >"
+ "<%@: userCode:%@; verificationURI:%@; verificationURIComplete:%@; expiresIn:%@; interval:%@; >"
+ "AV Analysis Node"
+ "AdditionalAccessoryConfigurationAvailable"
+ "Advertiser not initialized"
+ "AdvertisingEnabled"
+ "AppleAccessoryConfiguration"
+ "AppleDelayedEndTime"
+ "AppleDelayedStartTime"
+ "AppleProximityBLEAdvertising"
+ "AppleReadyState"
+ "AppleUSB"
+ "Arc Fault Circuit Interrupter"
+ "Attestation nonce length is invalid"
+ "BDXTransferTimeoutInSeconds"
+ "BlockingAccessoryFunctionality"
+ "CSR nonce length is invalid"
+ "CondPumpEnabled"
+ "CondRunCount"
+ "Country code is too large"
+ "Darwin IP address scorer installed"
+ "DeviceRebootCompleted"
+ "DeviceRebootDurationToRecovery"
+ "DeviceSessionLossCount"
+ "Electrical Surge Protector"
+ "Error %s"
+ "Failed to advertise commissionable node"
+ "Failed to advertise operational node"
+ "Failed to establish CASE session with peer <%08X%08X, %d>. Error: %s"
+ "Failed to finalize service update"
+ "Failed to initialize advertiser"
+ "Failed to remove advertised services"
+ "Failed to start commissioning"
+ "Failure accepting incoming connection"
+ "Food Thermometer"
+ "GetDeviceAuthURI"
+ "GetDeviceAuthURIResponse"
+ "Got a user default value for BDX transfer timeout - %d seconds"
+ "Irrigation System"
+ "MessageNotPresented"
+ "No Wi-Fi credentials configured at commissioner!"
+ "OAuthLoggedIn"
+ "PROXY:%u"
+ "Posting DNS-SD platform initialized event failed with"
+ "ProxyTransport: activating session %u"
+ "ProxyTransport: deactivating session %u"
+ "ProxyTransport: empty message for session %u"
+ "ProxyTransport: forwarding %u bytes for session %u"
+ "ProxyTransport: injecting %u bytes for session %u into Matter stack"
+ "ProxyTransport: out of memory for received message"
+ "ProxyTransport: received message for unknown session %u (active=%d, expected=%u)"
+ "RangingConstraints"
+ "ResetCountBootRelativeTime"
+ "Residual Current Circuit Breaker"
+ "SetUpCodePairer: dropping duplicate discovered rendezvous parameters"
+ "Subscription 0x%08x to peer <%08X%08X, %d>: CASE session hung, initiating recovery"
+ "SuccessOrDie failure %s at %s:%d"
+ "SupportedLanguageCodes"
+ "ThreadFirstRestartCompleted"
+ "ThreadFirstRestartConnectivityState"
+ "ThreadFirstRestartRecoveryTime"
+ "ThreadRecoveryAttemptCount"
+ "ThreadRestartCount"
+ "ThreadTransportLossCount"
+ "Too many targeted endpoints in invoke, capping at %u"
+ "Treating NetworkIDNotFound as success for network removal"
+ "UpdateMotionZoneOptions"
+ "VerifyOrDie failure at %s:%d"
+ "WiFiCredentials.credentials is too large"
+ "WiFiCredentials.ssid is too large"
+ "WiFiFirstRestartCompleted"
+ "WiFiFirstRestartConnectivityState"
+ "WiFiFirstRestartRecoveryTime"
+ "WiFiRecoveryAttemptCount"
+ "WiFiRestartCount"
+ "WiFiTransportLossCount"
+ "ir0"
+ "src/app/CommandHandler.h"
+ "src/app/MessageDef/InvokeRequestMessage.cpp"
+ "src/protocols/bdx/StatusCode.cpp"
+ "src/transport/raw/ProxyTransport.cpp"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CHIPFramework/connectedhomeip/src/app/CommandHandler.h"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CHIPFramework/connectedhomeip/src/lib/support/Variant.h"
- "<%@: contributorNodeID:%@; contributorEndpointID:%@; contributorName:%@; contributorHealth:%@; >"
- "<%@: messageID:%@; priority:%@; messageControl:%@; startTime:%@; duration:%@; messageText:%@; responses:%@; >"
- "<%@: resultCode:%@; sessionID:%@; >"
- "<%@: role:%@; peerBLEDeviceID:%@; >"
- "<%@: statusChangedContributor:%@; >"
- "<%@: technology:%@; frequencyBand:%@; periodicRangingSupport:%@; >"
- "<%@: technology:%@; wiFiRangingDeviceRoleConfig:%@; bleRangingDeviceRoleConfig:%@; bltChannelSoundingDeviceRoleConfig:%@; frequencyBand:%@; bandwidth:%@; securityMode:%@; trigger:%@; reportingCondition:%@; >"
- "<%@: tripMechanism:%@; protectionClass:%@; protectionType:%@; maxContinuousOperatingVoltage:%@; maxVoltageProtection:%@; maxTemporaryVoltage:%@; nominalDischargeCurrent:%@; maximumDishargeCurrent:%@; ratedShortCircuitCurrent:%@; ratedShortTimeWithstandCurrent:%@; energyAbsorptionCapability:%@; responseTime:%@; >"
- "AppleFoodThermometerConnected"
- "AppleFoodThermometerCurrentTemperature"
- "AppleFoodThermometerTargetTemperature"
- "Country code is too large: %u"
- "Failed to advertise commissionable node: %s"
- "Failed to advertise operational node: %s"
- "Failed to finalize service update: %s"
- "Failed to initialize advertiser: %s"
- "Failed to start commissioning: %s"
- "Failure accepting incoming connection: %s"
- "NFCBase::OnNfcTagResponse"
- "Posting DNS-SD platform initialized event failed with: %s"
- "Wifi credentials are too large"
- "discriminator == (discriminator & kShortMask)"
- "mValue.type == Value::Type::kChipErrorCode"
- "mValue.type == Value::Type::kInt32"
```
