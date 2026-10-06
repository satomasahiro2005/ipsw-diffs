## GenerativePartnerService

> `/System/Library/PrivateFrameworks/GenerativePartnerService.framework/GenerativePartnerService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x872b8` | `0x8c294` | **`+0x4fdc`** |
| `__DATA_DIRTY.__data` | `0xc60` | `0x15f8` | **`+0x998`** |
| `__DATA_DIRTY.__bss` | `0xb80` | `0x1500` | **`+0x980`** |
| `__DATA.__bss` | `0x46a0` | `0x40a0` | **`-0x600`** |
| `__AUTH.__data` | `0xce0` | `0x740` | **`-0x5a0`** |
| `__AUTH_CONST.__const` | `0x5e48` | `0x62a0` | **`+0x458`** |
| `__TEXT.__const` | `0x48a8` | `0x4c98` | **`+0x3f0`** |
| `__TEXT.__eh_frame` | `0x47e0` | `0x4bd0` | **`+0x3f0`** |
| `__TEXT.__swift5_typeref` | `0x13ed` | `0x1721` | **`+0x334`** |
| `__TEXT.__unwind_info` | `0x23c8` | `0x2680` | **`+0x2b8`** |
| `__AUTH_CONST.__objc_const` | `0xfe8` | `0x11b8` | **`+0x1d0`** |
| `__TEXT.__swift5_capture` | `0x11b4` | `0x137c` | **`+0x1c8`** |
| `__DATA.__data` | `0x9e8` | `0x8c8` | **`-0x120`** |
| `__DATA_DIRTY.__objc_data` | `0x1d0` | `0x2e8` | **`+0x118`** |
| `__TEXT.__constg_swiftt` | `0x14c0` | `0x15b4` | **`+0xf4`** |
| `__DATA_CONST.__const` | `0x210` | `0x300` | **`+0xf0`** |
| `__TEXT.__swift5_reflstr` | `0x12c1` | `0x13a1` | **`+0xe0`** |
| `__DATA_DIRTY.__common` | `0xb0` | `0x168` | **`+0xb8`** |
| `__TEXT.__swift5_fieldmd` | `0x152c` | `0x15e4` | **`+0xb8`** |
| `__AUTH_CONST.__auth_got` | `0x1410` | `0x14b8` | **`+0xa8`** |
| `__TEXT.__swift5_assocty` | `0x2b0` | `0x358` | **`+0xa8`** |
| `__DATA.__common` | `0x128` | `0x88` | **`-0xa0`** |
| `__AUTH.__objc_data` | `0x1f0` | `0x190` | **`-0x60`** |
| `__TEXT.__cstring` | `0x1cfb` | `0x1cab` | **`-0x50`** |
| `__TEXT.__oslogstring` | `0x3f4d` | `0x3efd` | **`-0x50`** |
| `__TEXT.__objc_methlist` | `0x1d4` | `0x21c` | **`+0x48`** |
| `__TEXT.__swift_as_cont` | `0x34c` | `0x390` | **`+0x44`** |
| `__DATA_CONST.__objc_selrefs` | `0x370` | `0x330` | **`-0x40`** |
| `__TEXT.__swift5_proto` | `0x2a0` | `0x2bc` | **`+0x1c`** |
| `__TEXT.__swift_as_entry` | `0x194` | `0x1b0` | **`+0x1c`** |
| `__TEXT.__swift_as_ret` | `0x1a0` | `0x1bc` | **`+0x1c`** |
| `__TEXT.__swift5_types` | `0x1b0` | `0x1c8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x7a0` | `0x7b0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x88` | `0x98` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x20` | `0x28` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x18` | `0x20` | **`+0x8`** |

### Other Changes

```diff

-284.0.7.0.0
+287.0.6.0.0

+  - /System/Library/PrivateFrameworks/ProactiveDaemonSupport.framework/ProactiveDaemonSupport

-  Functions: 4111
-  Symbols:   235
-  CStrings:  434
+  Functions: 4413
+  Symbols:   233
+  CStrings:  430
Symbols:
+ _objc_retain_x26
+ _swift_weakAssign
- _OBJC_CLASS_$_NSXPCConnection
- _OBJC_CLASS_$_NSXPCInterface
- _swift_deallocPartialClassInstance
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "EPS XPC connection interrupted."
+ "EPS XPC connection invalidated."
+ "EPS failed to resubscribe to provider changes: %{public}@"
+ "EPS failed to subscribe to provider changes: %{public}@"
+ "EPS failed to unsubscribe from provider changes: %{public}@"
+ "ExternalProviderServiceXPCClient: connection init failed: "
+ "Fatal error"
+ "GenerativePartnerService/ExternalProviderServiceXPCClient.swift"
+ "TCC XPC: tccAuthorizedBundleIdentifiers failed: %{public}@"
+ "TCC XPC: tccForceAuthorize failed: %{public}@"
+ "TCC XPC: tccForceReset failed: %{public}@"
- "ExternalProviderServiceXPCClient init()"
- "ExternalProviderTCCManagingXPCClient init()"
- "Failed to create XPC proxy"
- "XPC Client: Received change notification: %s"
- "XPC Client: Unregistered observer: %{bool}d"
- "XPC connection interrupted - attempting to reconnect"
- "XPC connection invalidated - service may not be running"
- "[%{public}s] XPC Client: Connection error: %@"
- "[%{public}s] XPC Client: Failed to create XPC proxy"
- "[%{public}s] XPC Client: Successfully created XPC proxy"
- "externalProviders()"
- "observeExternalProviderChanges()"
- "tccAuthorizedBundleIdentifiers(service:)"
- "tccForceAuthorize(service:for:)"
- "tccForceReset(service:for:)"
```
