## libsystem_eligibility.dylib

> `/usr/lib/system/libsystem_eligibility.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4178` | `0x4250` | **`+0xd8`** |
| `__TEXT.__cstring` | `0x57e1` | `0x5815` | **`+0x34`** |
| `__TEXT.__const` | `0x760` | `0x768` | **`+0x8`** |

### Other Changes

```diff

-446.2.3.0.0
+446.40.34.502.1

-  Functions: 28
-  Symbols:   78
-  CStrings:  549
+  Functions: 32
+  Symbols:   82
+  CStrings:  551
Symbols:
+ _eligibility_xpc_create_set_input_message
+ _os_eligibility_reset_all_inputs
+ _os_eligibility_reset_input
+ _os_eligibility_set_input_forced
CStrings:
+ "OS_ELIGIBILITY_INPUT_CELLULAR_CAPABLE_DEVICE"
+ "forced"
```
