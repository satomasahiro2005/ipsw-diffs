## StatusKit

> `/System/Library/PrivateFrameworks/StatusKit.framework/StatusKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x453f0` | `0x4583c` | **`+0x44c`** |
| `__TEXT.__eh_frame` | `0x1b98` | `0x1c08` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x52b9` | `0x5329` | **`+0x70`** |
| `__AUTH_CONST.__const` | `0xe18` | `0xe68` | **`+0x50`** |
| `__DATA_CONST.__const` | `0xa58` | `0xa08` | **`-0x50`** |
| `__TEXT.__swift5_capture` | `0x1fc` | `0x234` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0xac8` | `0xae8` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x864` | `0x884` | **`+0x20`** |
| `__DATA.__data` | `0x938` | `0x948` | **`+0x10`** |
| `__TEXT.__cstring` | `0x1d2e` | `0x1d3e` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x2138` | `0x2128` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x7e6` | `0x7f6` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xf20` | `0xf28` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0x7a8` | `0x7a0` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0x524` | `0x51c` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1548` | `0x1550` | **`+0x8`** |

### Other Changes

```diff

-143.100.3.0.0
+147.100.1.0.0

-  Functions: 1701
-  Symbols:   3457
-  CStrings:  538
+  Functions: 1704
+  Symbols:   3462
+  CStrings:  539
Symbols:
+ -[SKStatusPublishingService releaseProvisionedPayload:completion:]
+ GCC_except_table11
+ GCC_except_table133
+ GCC_except_table146
+ GCC_except_table152
+ GCC_except_table160
+ GCC_except_table47
+ GCC_except_table55
+ _$s14XPCDistributed9XPCSystemC7SessionC14LocalInterfaceV7sessionAEvg
+ _$s14XPCDistributed9XPCSystemC7SessionC16remoteAuditTokenSo13audit_token_taSgvg
+ _$s9StatusKit19SKPrimaryQueueActorC14assumeIsolated_4file4linexxyYbKACYcXE_s12StaticStringVSutKlFZ
+ _$s9StatusKit19SKPrimaryQueueActorCACs06GlobalE0AAWL
+ _$s9StatusKit22SKBackgroundQueueActorC14assumeIsolated_4file4linexxyYbKACYcXE_s12StaticStringVSutKlFZ
+ _$s9StatusKit22SKBackgroundQueueActorCACs06GlobalE0AAWL
+ _$ss11GlobalActorPsE20preconditionIsolated_4file4lineySSyXK_s12StaticStringVSutFZ
+ _$ss11GlobalActorPsE20preconditionIsolated_4file4lineySSyXK_s12StaticStringVSutFZfA_SSycfu_
+ ___66-[SKStatusPublishingService releaseProvisionedPayload:completion:]_block_invoke
+ _swift_isEscapingClosureAtFileLocation
+ _symbolic x______pIghrzo_ s5ErrorP
- -[SKPresence fetchPresenceCapability:]
- GCC_except_table138
- GCC_except_table15
- GCC_except_table156
- GCC_except_table162
- GCC_except_table165
- GCC_except_table37
- GCC_except_table52
- _$s9StatusKit18SKPresenceXPCActorC15peerRequirement3XPC07XPCPeerF0VvgTj
- _$s9StatusKit18SKPresenceXPCActorC15peerRequirement3XPC07XPCPeerF0VvgTq
- ___38-[SKPresence fetchPresenceCapability:]_block_invoke
- ___38-[SKPresence fetchPresenceCapability:]_block_invoke_2
- ___block_descriptor_41_e8_32bs_e5_v8?0ls32l8
- ___block_descriptor_48_e8_32s40bs_e8_v12?0B8ls32l8s40l8
CStrings:
+ "AllowUnlimitedPayloadSizeForPrototyping"
+ "Releasing provisioned payload %@ succeeded"
+ "Releasing provisioned payload %@. StatusType: %{public}@"
+ "Releasing provisioned payload failed with error: %@"
+ "XPC Error releasing provisioned payload. StatusType: %{public}@ Error: %{public}@"
- "-[SKPresence fetchPresenceCapability:]"
- "Checked if account is presence capable: %d"
- "Fetching presence capability."
- "XPC Error checking presence capability.  Error: %{public}@"
```
