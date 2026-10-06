## ActionKit

> `/System/Library/PrivateFrameworks/ActionKit.framework/ActionKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4027ac` | `0x409268` | **`+0x6abc`** |
| `__TEXT.__ustring` | `0x3840` | `0x41d8` | **`+0x998`** |
| `__DATA_CONST.__const` | `0x1d858` | `0x1dfd0` | **`+0x778`** |
| `__TEXT.__eh_frame` | `0x9b90` | `0x9ed8` | **`+0x348`** |
| `__TEXT.__oslogstring` | `0x6390` | `0x66ba` | **`+0x32a`** |
| `__AUTH_CONST.__const` | `0x10f20` | `0x11200` | **`+0x2e0`** |
| `__TEXT.__cstring` | `0x5399e` | `0x53bc1` | **`+0x223`** |
| `__TEXT.__gcc_except_tab` | `0x3be4` | `0x3d48` | **`+0x164`** |
| `__TEXT.__unwind_info` | `0xe458` | `0xe5b8` | **`+0x160`** |
| `__AUTH_CONST.__cfstring` | `0x2b860` | `0x2b980` | **`+0x120`** |
| `__TEXT.__const` | `0x2a820` | `0x2a938` | **`+0x118`** |
| `__TEXT.__swift5_capture` | `0xb34` | `0xc14` | **`+0xe0`** |
| `__AUTH_CONST.__auth_got` | `0x34c8` | `0x3580` | **`+0xb8`** |
| `__DATA.__bss` | `0xa158` | `0xa1d8` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x21994` | `0x21a14` | **`+0x80`** |
| `__DATA.__data` | `0xb4e8` | `0xb558` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0x3e558` | `0x3e5c0` | **`+0x68`** |
| `__DATA_CONST.__got` | `0x46e0` | `0x4738` | **`+0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0xf6f8` | `0xf750` | **`+0x58`** |
| `__TEXT.__swift_as_cont` | `0x7f0` | `0x848` | **`+0x58`** |
| `__DATA_DIRTY.__data` | `0x1668` | `0x1698` | **`+0x30`** |
| `__AUTH.__objc_data` | `0x7fd8` | `0x8000` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x1ea0` | `0x1ec8` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `0x524` | `0x540` | **`+0x1c`** |
| `__TEXT.__swift5_typeref` | `0x3e0f` | `0x3e29` | **`+0x1a`** |
| `__TEXT.__swift_as_entry` | `0x43c` | `0x454` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x74c` | `0x750` | **`+0x4`** |

### Other Changes

```diff

-5028.0.21.0.0
+5032.5.0.0.0

-  Functions: 23810
-  Symbols:   32246
-  CStrings:  13051
+  Functions: 23951
+  Symbols:   32288
+  CStrings:  13192
Symbols:
+ +[WFNetworkInterface ethernetNetworkInterfaces]
+ +[WFNetworkInterface interfaceHasRoutableAddress:fromList:]
+ -[WFNetworkInterface IPv4DefaultGateway]
+ -[WFNetworkInterface IPv4SubnetMask]
+ -[WFNetworkInterface ethernetSubtype]
+ -[WFNetworkInterface hardwareMACAddress]
+ -[WFNetworkInterface linkSpeedMbps]
+ -[WFNetworkInterface stringForMatchingAddrInfoOfFamily:selector:]
+ -[WFRequestRideIntentAction intentResponseRequiresAppLaunchForError:]
+ -[WFSetVPNAction saveToPreferencesWithVPNManager:completionHandler:]
+ GCC_except_table10005
+ GCC_except_table10354
+ GCC_except_table10358
+ GCC_except_table10385
+ GCC_except_table10394
+ GCC_except_table10397
+ GCC_except_table10407
+ GCC_except_table10531
+ GCC_except_table10550
+ GCC_except_table10558
+ GCC_except_table10571
+ GCC_except_table10644
+ GCC_except_table10649
+ GCC_except_table10653
+ GCC_except_table10664
+ GCC_except_table10750
+ GCC_except_table10754
+ GCC_except_table10758
+ GCC_except_table10768
+ GCC_except_table10772
+ GCC_except_table10785
+ GCC_except_table10793
+ GCC_except_table10872
+ GCC_except_table10910
+ GCC_except_table11047
+ GCC_except_table11101
+ GCC_except_table11116
+ GCC_except_table11168
+ GCC_except_table11171
+ GCC_except_table11174
+ GCC_except_table11178
+ GCC_except_table11199
+ GCC_except_table11201
+ GCC_except_table11213
+ GCC_except_table11229
+ GCC_except_table11231
+ GCC_except_table11248
+ GCC_except_table11253
+ GCC_except_table11261
+ GCC_except_table11327
+ GCC_except_table11330
+ GCC_except_table11333
+ GCC_except_table11336
+ GCC_except_table11358
+ GCC_except_table11458
+ GCC_except_table11462
+ GCC_except_table11464
+ GCC_except_table11466
+ GCC_except_table11480
+ GCC_except_table11551
+ GCC_except_table11573
+ GCC_except_table11580
+ GCC_except_table11611
+ GCC_except_table11613
+ GCC_except_table11633
+ GCC_except_table11651
+ GCC_except_table11676
+ GCC_except_table11681
+ GCC_except_table11786
+ GCC_except_table11830
+ GCC_except_table11859
+ GCC_except_table11917
+ GCC_except_table11920
+ GCC_except_table11931
+ GCC_except_table11934
+ GCC_except_table9973
+ _OBJC_CLASS_$_LNEntityValueType
+ _OUTLINED_FUNCTION_328
+ _OUTLINED_FUNCTION_457
+ _OUTLINED_FUNCTION_458
+ _OUTLINED_FUNCTION_459
+ _OUTLINED_FUNCTION_460
+ _OUTLINED_FUNCTION_461
+ _OUTLINED_FUNCTION_462
+ _WFDeviceCapabilityEthernet
+ _WFLinkMailMessageEntityTypeName
+ _WFNetworkPickerNetworkCellular
+ _WFNetworkPickerNetworkEthernet
+ __PROPERTIES_WFOnScreenContextAction
+ ___33-[WFNetworkInterface IPv4Address]_block_invoke
+ ___33-[WFNetworkInterface IPv6Address]_block_invoke
+ ___35-[WFNetworkInterface linkSpeedMbps]_block_invoke
+ ___36-[WFNetworkInterface IPv4SubnetMask]_block_invoke
+ ___37-[WFNetworkInterface ethernetSubtype]_block_invoke
+ ___40-[WFNetworkInterface IPv4DefaultGateway]_block_invoke
+ ___40-[WFNetworkInterface hardwareMACAddress]_block_invoke
+ ___47+[WFNetworkInterface ethernetNetworkInterfaces]_block_invoke
+ ___47+[WFNetworkInterface ethernetNetworkInterfaces]_block_invoke_2
+ ___65-[WFNetworkInterface stringForMatchingAddrInfoOfFamily:selector:]_block_invoke
+ ___68-[WFSetVPNAction saveToPreferencesWithVPNManager:completionHandler:]_block_invoke
+ ___block_descriptor_32_e83_^{sockaddr=CC[14c]}16?0^{ifaddrs=^{ifaddrs}*I^{sockaddr}^{sockaddr}^{sockaddr}^v}8l
+ ___block_descriptor_36_e5_v8?0l
+ ___block_descriptor_64_e8_32s40s48s_e53_v32?0"NSAttributedString"8"NSString"16"NSError"24ls32l8s40l8s48l8
+ _ethernetSubtype.descriptions
+ _if_nametoindex
+ _ioctl
+ _swift_asyncLet_begin
+ _swift_asyncLet_finish
+ _swift_asyncLet_get
+ _swift_asyncLet_get_throwing
+ _symbolic ScCySaySSG_____G s5NeverO
+ _symbolic _____Sg 16FoundationModels32PrivateCloudComputeLanguageModelC10QuotaUsageV
- -[WFNetworkInterface ipAddressForFamily:]
- -[WFSetVPNAction saveToPreferencesWithVPNManager:]
- GCC_except_table10004
- GCC_except_table10353
- GCC_except_table10356
- GCC_except_table10384
- GCC_except_table10392
- GCC_except_table10396
- GCC_except_table10399
- GCC_except_table10527
- GCC_except_table10549
- GCC_except_table10557
- GCC_except_table10570
- GCC_except_table10643
- GCC_except_table10648
- GCC_except_table10652
- GCC_except_table10663
- GCC_except_table10749
- GCC_except_table10753
- GCC_except_table10757
- GCC_except_table10767
- GCC_except_table10771
- GCC_except_table10784
- GCC_except_table10792
- GCC_except_table10871
- GCC_except_table10909
- GCC_except_table11046
- GCC_except_table11100
- GCC_except_table11115
- GCC_except_table11167
- GCC_except_table11170
- GCC_except_table11173
- GCC_except_table11177
- GCC_except_table11198
- GCC_except_table11200
- GCC_except_table11212
- GCC_except_table11224
- GCC_except_table11230
- GCC_except_table11247
- GCC_except_table11252
- GCC_except_table11259
- GCC_except_table11326
- GCC_except_table11329
- GCC_except_table11332
- GCC_except_table11335
- GCC_except_table11357
- GCC_except_table11457
- GCC_except_table11534
- GCC_except_table11556
- GCC_except_table11563
- GCC_except_table11594
- GCC_except_table11596
- GCC_except_table11616
- GCC_except_table11634
- GCC_except_table11659
- GCC_except_table11664
- GCC_except_table11769
- GCC_except_table11813
- GCC_except_table11839
- GCC_except_table11891
- GCC_except_table11894
- GCC_except_table11897
- GCC_except_table11900
- GCC_except_table9972
- _OUTLINED_FUNCTION_332
- _WFNetworkPickerNetworkCelluar
- _WFOpenWorkflowURLHandlerScrolledToActionErrorMessageKey
- ___41-[WFNetworkInterface ipAddressForFamily:]_block_invoke
- ___50-[WFSetVPNAction saveToPreferencesWithVPNManager:]_block_invoke
- ___block_descriptor_56_e8_32s40s_e53_v32?0"NSAttributedString"8"NSString"16"NSError"24ls32l8s40l8
CStrings:
+ "%s Received empty or nil string from object representation conversion"
+ "%s Unable to coerce WFRichTextContentItem %@ to attributed string"
+ "%s Unable to retrieve string from WFStringContentItem"
+ "%s Unexpected WFEthernetDetailKey %@ in WFGetNetworkDetailsAction"
+ "%s Unexpected ethernetSubject: %@"
+ "-[WFGetNetworkDetailsAction runAsynchronouslyWithInput:]"
+ "-[WFSetVPNAction saveToPreferencesWithVPNManager:completionHandler:]_block_invoke"
+ "1000Base-CX-SGMII"
+ "1000Base-KX"
+ "1000Base-SGMII"
+ "1000baseCX"
+ "1000baseLX"
+ "1000baseSX"
+ "1000baseT"
+ "100BaseT"
+ "100G-AUI2"
+ "100G-AUI2-AC"
+ "100G-AUI4"
+ "100G-AUI4-AC"
+ "100G-CAUI2"
+ "100G-CAUI2-AC"
+ "100G-CAUI4"
+ "100G-CAUI4-AC"
+ "100GBase-CP2"
+ "100GBase-CR-PAM4"
+ "100GBase-CR4"
+ "100GBase-DR"
+ "100GBase-KR-PAM4"
+ "100GBase-KR2-PAM4"
+ "100GBase-KR4"
+ "100GBase-LR4"
+ "100GBase-SR2"
+ "100GBase-SR4"
+ "100M-SGMII"
+ "100baseFX"
+ "100baseT2"
+ "100baseT4"
+ "100baseTX"
+ "100baseVG"
+ "10GBase-AOC"
+ "10GBase-CR1"
+ "10GBase-ER"
+ "10GBase-KR"
+ "10GBase-KX4"
+ "10GBase-SFI"
+ "10Gbase-CX4"
+ "10Gbase-LR"
+ "10Gbase-LRM"
+ "10Gbase-SR"
+ "10Gbase-T"
+ "10Gbase-Twinax"
+ "10Gbase-Twinax-Long"
+ "10base2/BNC"
+ "10base5/AUI"
+ "10baseFL"
+ "10baseSTP"
+ "10baseT/UTP"
+ "200G-AUI4"
+ "200G-AUI4-AC"
+ "200G-AUI8"
+ "200G-AUI8-AC"
+ "200GBase-CR4-PAM4"
+ "200GBase-DR4"
+ "200GBase-FR4"
+ "200GBase-KR4-PAM4"
+ "200GBase-LR4"
+ "200GBase-SR4"
+ "20GBase-KR2"
+ "2500Base-KX"
+ "2500Base-T"
+ "2500Base-X"
+ "2500BaseSX"
+ "25G-AUI"
+ "25GBase-ACC"
+ "25GBase-AOC"
+ "25GBase-CR"
+ "25GBase-CR-S"
+ "25GBase-CR1"
+ "25GBase-KR"
+ "25GBase-KR-S"
+ "25GBase-KR1"
+ "25GBase-LR"
+ "25GBase-SR"
+ "25GBase-T"
+ "400G-AUI8"
+ "400G-AUI8-AC"
+ "400GBase-DR4"
+ "400GBase-FR8"
+ "400GBase-LR8"
+ "40G-XLAUI"
+ "40G-XLAUI-AC"
+ "40GBase-ER4"
+ "40GBase-KR4"
+ "40GBase-XLPPI"
+ "40Gbase-CR4"
+ "40Gbase-LR4"
+ "40Gbase-SR4"
+ "5000Base-KR"
+ "5000Base-KR-S"
+ "5000Base-KR1"
+ "5000Base-T"
+ "50G-AUI1"
+ "50G-AUI1-AC"
+ "50G-AUI2"
+ "50G-AUI2-AC"
+ "50G-LAUI2"
+ "50G-LAUI2-AC"
+ "50GBase-CP"
+ "50GBase-CR2"
+ "50GBase-FR"
+ "50GBase-KR-PAM4"
+ "50GBase-KR2"
+ "50GBase-LR"
+ "50GBase-LR2"
+ "50GBase-SR"
+ "50GBase-SR2"
+ "56GBase-R4"
+ "Add New Reminders couldn’t find any Reminders lists. Make sure you have at least one set up in the Reminders app."
+ "Couldn’t hand off music between specified devices."
+ "Current PCC usage: %s"
+ "Ethernet"
+ "Ethernet Standard"
+ "Failed to get current PCC usage: refreshQuota() returned nil"
+ "Failed to get current PCC usage: refreshQuota() threw %@"
+ "IPv4 Address"
+ "IPv6 Address"
+ "IT IS POSSIBLE THAT SOMEONE IS DOING SOMETHING NASTY!\n\nThis could indicate a man-in-the-middle attack, or it is possible that the host has changed.\n\nThe host key’s fingerprint is %@.\n\nAre you sure you want to continue connecting?"
+ "Image from the device’s screen."
+ "Interface Name"
+ "Link Speed"
+ "Lock App couldn’t authenticate the user."
+ "Make sure the SSH server has this device’s public key in its list of authorized keys."
+ "No alert location was provided. Please provide a location for this reminder’s alert."
+ "PCC usage limit reached"
+ "PCC usage: isApproachingLimit=%{bool}d"
+ "PCIExpress-25G"
+ "PCIExpress-50G"
+ "Presents a menu of the items passed as input to the action and outputs the user’s selection."
+ "Router IP"
+ "Shazam didn’t recognize any media."
+ "Subnet Mask"
+ "Take a screenshot of the device’s screen."
+ "The Quick Look action wasn’t passed any items to preview."
+ "The authenticity of host ‘%@’ can’t be established because it has not been seen before by this device.\n\nThe host’s key fingerprint is %@.\n\nAre you sure you want to continue connecting?"
+ "The expanded URL is cleaned, removing unnecessary parameters such as “utm_source”."
+ "The extension for ‘%@’ is not enabled. To run this action, enable the extension in Settings > Apple Intelligence & Siri > Extensions."
+ "The person you are trying to request money from doesn’t have an account set up with %@."
+ "The person you are trying to send money to doesn’t have an account set up with %@."
+ "The timer’s duration must be less than 24 hours."
+ "The ‘%@’ app is not installed on this device. To run this action, install the app or choose another model."
+ "This action requires a model from an extension, but this device doesn’t support Personal Siri. Choose a different model to run this action."
+ "This action uses a model provided by the ‘%@’ extension. To run this action, enable Personal Siri in Settings > Apple Intelligence & Siri, then enable the extension for the app."
+ "This is just like the Count in Sesame Street, but instead of a vampire, it’s a Shortcuts action."
+ "Unhandled PCC model QuotaUsage case: %s"
+ "WFEthernetDetail"
+ "WFSpotlightSearchAction: GLP mail hydrated %ld/%ld"
+ "WFSpotlightSearchAction: GLP mail hydration failed: %@"
+ "WFSpotlightSearchAction: GLP mail search failed: %@"
+ "WFSpotlightSearchAction: Mail routed to %{public}s (rdar://179176856)"
+ "What’s the message?"
+ "You can reference values deep inside of a dictionary by providing multiple keys separated by dots. For example, to get the value “soup” from the dictionary {\"beverages\": [{\"favorite\": \"soup\"}]}, you can specify the key path “beverages.1.favorite”."
+ "You don’t have a bank account configured on this device."
+ "Your administrator doesn’t allow taking screenshots."
+ "You’re approaching your daily Apple Intelligence limit for Shortcuts."
+ "You’re approaching your daily Apple Intelligence limit for Shortcuts. Sign in to iCloud for higher limits."
+ "You’re approaching your daily Apple Intelligence limit for Shortcuts. Upgrade to iCloud+ for higher limits."
+ "^{sockaddr=CC[14c]}16@?0^{ifaddrs=^{ifaddrs}*I^{sockaddr}^{sockaddr}^{sockaddr}^v}8"
+ "files.FileEntity"
+ "homePNA"
+ "queryMailGLP(searchInput:mailUseGLP:)"
+ "reader.ReaderDocumentEntity"
+ "‘%@’ was not found in Apple Music"
- "%s After enabling VPN, its status is %@"
- "'%@' was not found in Apple Music"
- "-[WFSetVPNAction saveToPreferencesWithVPNManager:]_block_invoke"
- "Add New Reminders couldn't find any Reminders lists. Make sure you have at least one set up in the Reminders app."
- "Couldn't hand off music between specified devices."
- "IT IS POSSIBLE THAT SOMEONE IS DOING SOMETHING NASTY!\n\nThis could indicate a man-in-the-middle attack, or it is possible that the host has changed.\n\nThe host key's fingerprint is %@.\n\nAre you sure you want to continue connecting?"
- "Image from the device's screen."
- "Lock App couldn't authenticate the user."
- "Make sure the SSH server has this device's public key in its list of authorized keys."
- "No alert location was provided. Please provide a location for this reminder's alert."
- "Presents a menu of the items passed as input to the action and outputs the user's selection."
- "Shazam didn't recognize any media."
- "Take a screenshot of the device's screen."
- "The '%@' app is not installed on this device. To run this action, install the app or choose another model."
- "The Quick Look action wasn't passed any items to preview."
- "The authenticity of host '%@' can't be established because it has not been seen before by this device.\n\nThe host's key fingerprint is %@.\n\nAre you sure you want to continue connecting?"
- "The expanded URL is cleaned, removing unnecessary parameters such as \"utm_source\"."
- "The extension for '%@' is not enabled. To run this action, enable the extension in Settings > Apple Intelligence & Siri > Extensions."
- "The person you are trying to request money from doesn't have an account set up with %@."
- "The person you are trying to send money to doesn't have an account set up with %@."
- "The timer's duration must be less than 24 hours."
- "This action requires a model from an extension, but this device doesn't support Personal Siri. Choose a different model to run this action."
- "This action uses a model provided by the '%@' extension. To run this action, enable Personal Siri in Settings > Apple Intelligence & Siri, then enable the extension for the app."
- "This is just like the Count in Sesame Street, but instead of a vampire, it's a Shortcuts action."
- "What's the message?"
- "You can reference values deep inside of a dictionary by providing multiple keys separated by dots. For example, to get the value \"soup\" from the dictionary {\"beverages\": [{\"favorite\": \"soup\"}]}, you can specify the key path \"beverages.1.favorite\"."
- "You don't have a bank account configured on this device."
- "You're approaching your daily Apple Intelligence limit for Shortcuts."
- "You're approaching your daily Apple Intelligence limit for Shortcuts. Sign in to iCloud for higher limits."
- "You're approaching your daily Apple Intelligence limit for Shortcuts. Upgrade to iCloud+ for higher limits."
- "Your administrator doesn't allow taking screenshots."
```
