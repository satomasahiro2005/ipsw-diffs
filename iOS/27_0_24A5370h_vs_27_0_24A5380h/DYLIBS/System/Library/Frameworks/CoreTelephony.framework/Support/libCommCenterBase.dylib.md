## libCommCenterBase.dylib

> `/System/Library/Frameworks/CoreTelephony.framework/Support/libCommCenterBase.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd2284` | `0xd2180` | **`-0x104`** |
| `__AUTH_CONST.__const` | `0x143c0` | `0x14478` | **`+0xb8`** |
| `__TEXT.__cstring` | `0x149aa` | `0x14a0a` | **`+0x60`** |
| `__TEXT.__const` | `0xd290` | `0xd2d0` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x7658` | `0x7680` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x13afc` | `0x13b08` | **`+0xc`** |

### Other Changes

```diff

-13473.1.0.0.0
+13478.3.1.3.0

-  Functions: 5751
-  Symbols:   9439
-  CStrings:  4476
+  Functions: 5759
+  Symbols:   9453
+  CStrings:  4479
Symbols:
+ __ZN24TARandomizationInterfaceD0Ev
+ __ZN24TARandomizationInterfaceD1Ev
+ __ZN24TARandomizationInterfaceD2Ev
+ __ZN30TARDriverEventHandlerInterfaceD0Ev
+ __ZN30TARDriverEventHandlerInterfaceD1Ev
+ __ZN30TARDriverEventHandlerInterfaceD2Ev
+ __ZN6Lazuli8asStringENS_20ChatBotURLSchemeTypeE
+ __ZNK14CSIPhoneNumber22getIsCallForwardingMMIERKNSt3__16vectorINS0_12basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEENS5_IS7_EEEE
+ __ZTI24TARandomizationInterface
+ __ZTI30TARDriverEventHandlerInterface
+ __ZTS24TARandomizationInterface
+ __ZTS30TARDriverEventHandlerInterface
+ __ZTV24TARandomizationInterface
+ __ZTV30TARDriverEventHandlerInterface
CStrings:
+ "pending-profile-release"
+ "primary-updating-to-fan-out-without-msg-ref"
+ "transport-activation-failed"
```
