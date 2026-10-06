## Business

> `/Applications/BusinessExtensionsWrapper.app/PlugIns/Business.appex/Business`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9e47c` | `0x9ec18` | **`+0x79c`** |
| `__TEXT.__cstring` | `0x5c2b` | `0x5eab` | **`+0x280`** |
| `__TEXT.__objc_methname` | `0x7c48` | `0x7cb8` | **`+0x70`** |
| `__DATA.__objc_data` | `0x6d78` | `0x6d98` | **`+0x20`** |
| `__TEXT.__const` | `0x6434` | `0x6414` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0x4ea4` | `0x4ec4` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x27a0` | `0x27c0` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x1f60` | `0x1f50` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0xfb8` | `0xfb0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x998` | `0x990` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x28c6` | `0x28be` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1db8` | `0x1db0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-30122.30.5.19.1
+30123.30.6.2.1

-  Functions: 2662
-  Symbols:   446
-  CStrings:  1905
+  Functions: 2665
+  Symbols:   445
+  CStrings:  1910
Symbols:
- _OBJC_CLASS_$_UIViewPrintFormatter
CStrings:
+ "$__lazy_storage_$_shareButtonItem"
+ "%{public}@: internal auth bubble tapped — state: %{public}@"
+ "%{public}@: internal auth response NOT sent — authentication manager is nil (request payload failed to parse?). Tap does nothing."
+ "%{public}@: internal auth response NOT sent — hasOneRecipient: %{public}@, recipientIsApple: %{public}@. Recipient must be a single allowed Apple business URN; a test/demo business on a non-internal build fails the Apple-URN check. Recipients: %@. Tap does nothing."
+ "%{public}@: tap ignored — bubble state is %{public}@ (not authenticate/signIn), nothing to do"
+ "authenticationSucceeded"
- "shareButtonItem"
```
