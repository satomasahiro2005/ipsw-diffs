## SoftwareUpdateSubscriber

> `/System/Library/PrivateFrameworks/RemoteManagement.framework/XPCServices/SoftwareUpdateSubscriber.xpc/SoftwareUpdateSubscriber`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x52d4` | `0x52c0` | **`-0x14`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2717.0.0.0.0
+2718.0.2.0.0
Functions:
~ -[SoftwareUpdateAdapter allDeclarationKeysForScope:error:] : 2208 -> 2204
~ -[SoftwareUpdateCombinedAdapter allDeclarationKeysForScope:completionHandler:] : 1128 -> 1124
~ -[SoftwareUpdateCombinedAdapter applyCombinedConfiguration:declarationKeys:scope:returningReasons:error:] : 3392 -> 3388
~ -[SoftwareUpdateCombinedAdapter configurationUIForConfiguration:scope:completionHandler:] : 3372 -> 3368
~ -[SoftwareUpdateStatus queryForStatusWithKeyPaths:store:completionHandler:] : 1204 -> 1200
```
