## com.apple.iokit.IOThunderboltFamily

> `com.apple.iokit.IOThunderboltFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0xaa0` | **`+0xaa0`** |
| `__TEXT_EXEC.__text` | `0x1cb7f0` | `0x1cc084` | **`+0x894`** |
| `__TEXT.__os_log` | `0x3be20` | `0x3bd4b` | **`-0xd5`** |
| `__TEXT.__cstring` | `0x4adb4` | `0x4ad99` | **`-0x1b`** |
| `__DATA_CONST.__const` | `0x24a38` | `0x24a28` | **`-0x10`** |

### Other Changes

```diff

-6832.0.0.0.0
-  Functions: 5698
+6834.0.0.0.0
+  Functions: 5701
CStrings:
+ "%lldus IOThunderboltController(%d)::updateCLxModeInternal - sw_clx_objection=0x%x\n"
+ "%lldus IOThunderboltController(%d)::updateCLxModeInternal - switch_sw_clx_Objection = 0x%x route_string = 0x%llx (sw_clx_objection=0x%x)\n"
+ "%lldus IOThunderboltSwitch(%x@%llx)::doOverrideSupportedCLxStates - new_clx_states=0x%x controllerObjection=0x%x (explicit=%d)\n"
+ "%lldus IOThunderboltSwitchOS2(%d)::updateCLxModeInternal enable=0x%x\n"
+ "%lldus IOThunderboltSwitchOS2<%p>::configureUpstreamAsymmetricMode - dispatchAsync( IOThunderboltSwitchOS2<%p>::configureUpstreamAsymmetricModeInternal )\n"
+ "%lldus IOThunderboltSwitchOS2<%p>::configureUpstreamAsymmetricMode - dispatchAsync( IOThunderboltSwitchOS2<%p>::configureUpstreamAsymmetricModeInternal ) failed with status=0x%x\n"
+ "1211111212221212111111111222211111112212222212222221"
+ "121111121222121211111111122221111111221222221222222121212122"
+ "19:34:13"
+ "Jun 18 2026"
+ "mode"
- "%lldus IOThunderboltController(%d)::updateCLxModeInternal - fSWObjectionCLxStates=0x%x\n"
- "%lldus IOThunderboltController(%d)::updateCLxModeInternal - switch_sw_clx_Objection = 0x%x route_string = 0x%llx (fSWObjectionCLxStates=0x%x)\n"
- "%lldus IOThunderboltPort(%x@%llx:0x%x)::configureLinkMode - done waiting for in-progress asymmetric transition\n"
- "%lldus IOThunderboltPort(%x@%llx:0x%x)::configureLinkMode - start waiting for in-progress asymmetric transition (if any)\n"
- "%lldus IOThunderboltSwitch(%x@%llx)::doOverrideSupportedCLxStates - new_clx_states=0x%x controllerObjection=0x%x\n"
- "%lldus IOThunderboltSwitchOS2(%x@%llx)::blockUntilAsymmetricFlowDone - Asymmetric flow is in progress, sleep the thread\n"
- "%lldus IOThunderboltSwitchOS2(%x@%llx)::blockUntilAsymmetricFlowDone - thread woke up\n"
- "121111121222121211111111122221111112212222212222221"
- "12111112122212121111111112222111111221222221222222121212122"
- "22:46:39"
- "May 27 2026"
```
