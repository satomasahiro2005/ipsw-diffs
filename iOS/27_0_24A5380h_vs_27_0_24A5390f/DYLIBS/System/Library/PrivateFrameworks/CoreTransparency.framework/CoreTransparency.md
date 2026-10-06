## CoreTransparency

> `/System/Library/PrivateFrameworks/CoreTransparency.framework/CoreTransparency`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4655c` | `0x48e20` | **`+0x28c4`** |
| `__DATA.__bss` | `0x7080` | `0x7400` | **`+0x380`** |
| `__TEXT.__swift5_reflstr` | `0x2064` | `0x22c4` | **`+0x260`** |
| `__TEXT.__const` | `0x7164` | `0x73b4` | **`+0x250`** |
| `__TEXT.__eh_frame` | `0x20d4` | `0x22a4` | **`+0x1d0`** |
| `__AUTH_CONST.__const` | `0x3a30` | `0x3b60` | **`+0x130`** |
| `__TEXT.__swift5_fieldmd` | `0x1bd8` | `0x1cdc` | **`+0x104`** |
| `__TEXT.__cstring` | `0xc8e` | `0xd6e` | **`+0xe0`** |
| `__TEXT.__unwind_info` | `0x17c0` | `0x1858` | **`+0x98`** |
| `__TEXT.__constg_swiftt` | `0x1b34` | `0x1b6c` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0x1862` | `0x1888` | **`+0x26`** |
| `__AUTH_CONST.__auth_got` | `0x958` | `0x938` | **`-0x20`** |
| `__DATA.__data` | `0x9a0` | `0x9c0` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x414` | `0x430` | **`+0x1c`** |
| `__TEXT.__swift5_builtin` | `0xc8` | `0xdc` | **`+0x14`** |
| `__TEXT.__swift5_mpenum` | `0x60` | `0x68` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x164` | `0x16c` | **`+0x8`** |

### Other Changes

```diff

-1766.0.27.0.0
+1766.0.39.0.2

-  Functions: 2837
-  Symbols:   726
-  CStrings:  93
+  Functions: 2915
+  Symbols:   731
+  CStrings:  97
Symbols:
+ ___swift_destroy_boxed_opaque_existential_0Tm
+ _associated conformance 16CoreTransparency17MapInclusionErrorO10Foundation13CustomNSErrorAAs0E0
+ _associated conformance 16CoreTransparency19CTServerStatusErrorV10Foundation13CustomNSErrorAAs0E0
+ _symbolic Si8expected_Si6actualt
+ _symbolic _____ 16CoreTransparency17MapInclusionErrorO
+ _symbolic _____ 16CoreTransparency19CTServerStatusErrorV
+ _type_layout_string 16CoreTransparency19CTServerStatusErrorV
- ___swift_destroy_boxed_opaque_existential_1Tm
- _symbolic _____y_____G s8RepeatedV s5UInt8V
CStrings:
+ "AET server returned non-OK status "
+ "com.apple.CoreTransparency.ServerError"
+ "parseEventsWithoutVerifying: response carried no map proofs"
+ "verifyMapProofs: response carried no map proofs ["
```
