## AgentCanvasPersistence

> `/System/Library/PrivateFrameworks/AgentCanvasPersistence.framework/AgentCanvasPersistence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x71214` | `0x74afc` | **`+0x38e8`** |
| `__TEXT.__eh_frame` | `0x37e0` | `0x3c68` | **`+0x488`** |
| `__TEXT.__const` | `0x6840` | `0x69c0` | **`+0x180`** |
| `__TEXT.__oslogstring` | `0xa3b` | `0xb7b` | **`+0x140`** |
| `__TEXT.__unwind_info` | `0x2200` | `0x2308` | **`+0x108`** |
| `__TEXT.__constg_swiftt` | `0x112c` | `0x11f4` | **`+0xc8`** |
| `__AUTH_CONST.__objc_const` | `0x5f8` | `0x6b0` | **`+0xb8`** |
| `__TEXT.__swift5_typeref` | `0x1818` | `0x18d0` | **`+0xb8`** |
| `__AUTH.__data` | `0x578` | `0x620` | **`+0xa8`** |
| `__TEXT.__swift5_fieldmd` | `0x11fc` | `0x126c` | **`+0x70`** |
| `__TEXT.__swift5_capture` | `0xb84` | `0xb2c` | **`-0x58`** |
| `__DATA.__data` | `0xdd0` | `0xe00` | **`+0x30`** |
| `__TEXT.__swift_as_ret` | `0x118` | `0x144` | **`+0x2c`** |
| `__TEXT.__swift5_reflstr` | `0xae9` | `0xb09` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0xe4` | `0x104` | **`+0x20`** |
| `__DATA.__common` | `—` | `0x18` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xf78` | `0xf88` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x250` | `0x260` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x1590` | `0x15a0` | **`+0x10`** |
| `__TEXT.__cstring` | `0xe44` | `0xe54` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x180` | `0x18c` | **`+0xc`** |
| `__AUTH_CONST.__const` | `0x44c0` | `0x44b8` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x20` | `0x24` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x110` | `0x114` | **`+0x4`** |

### Other Changes

```diff

-3605.3.4.0.0
+3605.9.5.0.0
+  - /System/Library/Frameworks/CoreServices.framework/CoreServices

-  Functions: 3434
-  Symbols:   1106
-  CStrings:  150
+  Functions: 3520
+  Symbols:   1125
+  CStrings:  156
Symbols:
+ _OBJC_CLASS_$_LSApplicationRecord
+ __DATA__TtC22AgentCanvasPersistence25ObservationDemandRegistry
+ __IVARS__TtC22AgentCanvasPersistence25ObservationDemandRegistry
+ __METACLASS_DATA__TtC22AgentCanvasPersistence25ObservationDemandRegistry
+ _swift_unknownObjectWeakInit
+ _swift_unknownObjectWeakLoadStrong
+ _symbolic $s22AgentCanvasPersistence27ObservationDemandRespondingP
+ _symbolic Say_____G 22AgentCanvasPersistence25ObservationDemandRegistryC14WeakRegistrant33_EAA68C8D1D8CA922ADF75347BE1BF51FLLV
+ _symbolic _____ 22AgentCanvasPersistence25ObservationDemandRegistryC
+ _symbolic _____ 22AgentCanvasPersistence25ObservationDemandRegistryC14WeakRegistrant33_EAA68C8D1D8CA922ADF75347BE1BF51FLLV
+ _symbolic _____ 22AgentCanvasPersistence25ObservationDemandRegistryC5State33_EAA68C8D1D8CA922ADF75347BE1BF51FLLV
+ _symbolic _____SgXw 22AgentCanvasPersistence25ObservationDemandRegistryC
+ _symbolic _____SgXwz_Xx 22AgentCanvasPersistence25ObservationDemandRegistryC
+ _symbolic ______p 22AgentCanvasPersistence27ObservationDemandRespondingP
+ _symbolic ______pSgXw 22AgentCanvasPersistence27ObservationDemandRespondingP
+ _symbolic ______pXp 22AgentCanvasPersistence27ObservationDemandRespondingP
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 22AgentCanvasPersistence25ObservationDemandRegistryC5State33_EAA68C8D1D8CA922ADF75347BE1BF51FLLV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 22AgentCanvasPersistence25ObservationDemandRegistryC14WeakRegistrant33_EAA68C8D1D8CA922ADF75347BE1BF51FLLV
+ _symbolic _____y______pG s23_ContiguousArrayStorageC 22AgentCanvasPersistence27ObservationDemandRespondingP
+ _type_layout_string 22AgentCanvasPersistence25ObservationDemandRegistryC14WeakRegistrant33_EAA68C8D1D8CA922ADF75347BE1BF51FLLV
+ _type_layout_string 22AgentCanvasPersistence25ObservationDemandRegistryC5State33_EAA68C8D1D8CA922ADF75347BE1BF51FLLV
- _OUTLINED_FUNCTION_192
- _swift_retain_x8
CStrings:
+ "%{public}s idle → applying deferred release"
+ "Acquire failed for %{public}s: %@"
+ "AcquireAll %{public}ld registrant(s)"
+ "AcquireAll: acquiring %{public}s"
+ "Late registrant → releasing %{public}s"
+ "ObservationDemandRegistry"
+ "Release failed for %{public}s: %@"
+ "ReleaseAll %{public}ld registrant(s)"
+ "ReleaseAll: %{public}s busy → deferring"
+ "ReleaseAll: releasing %{public}s"
- "Failed to encode selected text snippet: %s"
- "Not rendering SelectedText: %s"
- "SelectedText"
- "Will build for SelectedText: %s"
```
