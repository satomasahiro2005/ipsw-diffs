## sportsd

> `/usr/libexec/sportsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xabdb8` | `0xa8a5c` | **`-0x335c`** |
| `__DATA_CONST.__const` | `0x8360` | `0x7f18` | **`-0x448`** |
| `__DATA.__bss` | `0x7390` | `0x6f90` | **`-0x400`** |
| `__TEXT.__const` | `0x6308` | `0x5f98` | **`-0x370`** |
| `__DATA.__objc_const` | `0x27b8` | `0x2538` | **`-0x280`** |
| `__DATA.__data` | `0x3eb8` | `0x3c58` | **`-0x260`** |
| `__TEXT.__swift5_typeref` | `0x3c1c` | `0x39e4` | **`-0x238`** |
| `__TEXT.__objc_methname` | `0x200d` | `0x1e7d` | **`-0x190`** |
| `__TEXT.__constg_swiftt` | `0x1f90` | `0x1e68` | **`-0x128`** |
| `__TEXT.__swift5_capture` | `0x2278` | `0x2158` | **`-0x120`** |
| `__TEXT.__swift5_reflstr` | `0x2183` | `0x2063` | **`-0x120`** |
| `__TEXT.__unwind_info` | `0x2b48` | `0x2a50` | **`-0xf8`** |
| `__TEXT.__swift5_fieldmd` | `0x2138` | `0x2048` | **`-0xf0`** |
| `__TEXT.__objc_stubs` | `0x11e0` | `0x1100` | **`-0xe0`** |
| `__TEXT.__oslogstring` | `0x25a6` | `0x24c6` | **`-0xe0`** |
| `__TEXT.__eh_frame` | `0x4ea4` | `0x4dcc` | **`-0xd8`** |
| `__TEXT.__objc_classname` | `0x7b2` | `0x6e2` | **`-0xd0`** |
| `__TEXT.__auth_stubs` | `0x37c0` | `0x3760` | **`-0x60`** |
| `__TEXT.__cstring` | `0x19ce` | `0x196e` | **`-0x60`** |
| `__DATA.__objc_selrefs` | `0x6d8` | `0x6a0` | **`-0x38`** |
| `__DATA_CONST.__auth_got` | `0x1be8` | `0x1bb8` | **`-0x30`** |
| `__TEXT.__objc_methtype` | `0xdb2` | `0xd85` | **`-0x2d`** |
| `__DATA.__objc_data` | `0xa28` | `0xa00` | **`-0x28`** |
| `__DATA_CONST.__auth_ptr` | `0xa20` | `0x9f8` | **`-0x28`** |
| `__TEXT.__swift5_proto` | `0x440` | `0x41c` | **`-0x24`** |
| `__TEXT.__objc_methlist` | `0x6d4` | `0x6b4` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x9a8` | `0x990` | **`-0x18`** |
| `__TEXT.__swift5_assocty` | `0x288` | `0x270` | **`-0x18`** |
| `__DATA.__common` | `0x200` | `0x1f0` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x110` | `0x100` | **`-0x10`** |
| `__TEXT.__swift5_types` | `0x1f0` | `0x1e0` | **`-0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x78` | `0x70` | **`-0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x48` | `0x40` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x31c` | `0x314` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x150` | `0x148` | **`-0x8`** |
| `__TEXT.__swift5_protos` | `0x68` | `0x64` | **`-0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_catlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-234.0.0.0.0
+236.0.0.0.0

-  Functions: 4232
-  Symbols:   1410
-  CStrings:  819
+  Functions: 4134
+  Symbols:   1399
+  CStrings:  797
Symbols:
+ _$s10Foundation12CharacterSetV14urlPathAllowedACvgZ
+ _$sSy10FoundationE21addingPercentEncoding21withAllowedCharactersSSSgAA12CharacterSetV_tF
- _$s7Combine8DeferredV15createPublisherACyxGxyc_tcfC
- _$s7Combine8DeferredVMn
- _$s7Combine8DeferredVyxGAA9PublisherAAMc
- _$s9SportsKit15PersistentStoreC23persistSuppressionTallyyySDySSAA16DatedSubscribersVGKFTj
- _$s9SportsKit15PersistentStoreC24retrieveSuppressionTallySDySSAA16DatedSubscribersVGyFTj
- _$s9SportsKit15PersistentStoreCMn
- _$s9SportsKit16DatedSubscribersV15subscriberCount16lastSubscriptionACSi_10Foundation4DateVtcfC
- _$s9SportsKit16DatedSubscribersV15subscriberCountSivg
- _$s9SportsKit16DatedSubscribersV1poiyA2C_SitFZ
- _$s9SportsKit16DatedSubscribersV1soiyA2C_SitFZ
- _$s9SportsKit16DatedSubscribersVMa
- _$s9SportsKit16DatedSubscribersVMn
- _OBJC_CLASS_$_NSXPCConnection
CStrings:
+ "entityConfiguration"
- "Error connecting to watchlistd for suppression. %s"
- "Suppression Error: "
- "Unable to persist tally"
- "Unable to suppress notifications"
- "Watchlist XPC Error: %s"
- "Watchlist suppression connection interrupted. This should be recoverable."
- "Watchlist suppression connection invalidated."
- "_TtC7sportsd25WatchlistSuppressionActor"
- "_TtC7sportsd50WatchlistSuppressNotificationsXPCConnectionManager"
- "_TtP7sportsd51WatchlistSuppressNotificationsXPCConnectionProtocol_"
- "com.apple.watchlistd.xpc"
- "enableNotificationsFor:completion:"
- "initWithMachServiceName:options:"
- "persistentStore"
- "remoteObjectProxyWithErrorHandler:"
- "setInterruptionHandler:"
- "setInvalidationHandler:"
- "setRemoteObjectInterface:"
- "suppressNotificationsFor:completion:"
- "supressionManager"
- "tally"
- "v16@?0@\"NSError\"8"
- "xpcConnection"
```
