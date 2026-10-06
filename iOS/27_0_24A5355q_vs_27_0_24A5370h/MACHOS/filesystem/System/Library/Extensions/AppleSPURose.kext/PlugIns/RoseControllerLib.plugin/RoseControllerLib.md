## RoseControllerLib

> `/System/Library/Extensions/AppleSPURose.kext/PlugIns/RoseControllerLib.plugin/RoseControllerLib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7580` | `0x75a0` | **`+0x20`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1084.0.0.0.0
+1087.0.0.0.0
Functions:
~ __ZN14RoseController15ServiceCallbackEjPv : 856 -> 864
~ __ZN14RoseController34_registerEventCallbackForInterfaceEhPFvPvS0_mES0_b : 212 -> 220
~ __ZN14RoseController38_deRegisterSharedDataQueueEventHandlerEv : 84 -> 96
~ __ZN14RoseController18_callEventCallbackEP24_RTKitOSDataQueueMessagem : 444 -> 448
```
