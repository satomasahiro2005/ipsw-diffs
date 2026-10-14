## SiriNetwork

> `/System/Library/PrivateFrameworks/SiriNetwork.framework/SiriNetwork`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13f1a8` | `0x13f760` | **`+0x5b8`** |
| `__TEXT.__oslogstring` | `0xb0f7` | `0xb157` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0x1a28` | `0x1a58` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x9a0` | `0x9a8` | **`+0x8`** |

### Other Changes

```diff

-3605.7.1.0.0
+3605.10.1.0.0

-  Functions: 9479
-  Symbols:   15296
-  CStrings:  862
+  Functions: 9480
+  Symbols:   15306
+  CStrings:  863
Symbols:
+ _$s11SiriNetwork41MessageCenterConnectionParametersBuildersO12quicProtocol33_BE8D5C15C75B5A2D7D41CDF64E7C9714LL11serviceName6listen0B04QUICVSS_SbtFZ
+ _$s7Network12NWParametersC04SiriA0E17boundPathRecovery33_BE8D5C15C75B5A2D7D41CDF64E7C9714LLyyF
+ _$s7Network12NWParametersC13ProtocolStackC20applicationProtocolsSayAA17NWProtocolOptionsCGvgTj
+ _$s7Network12NWParametersC20defaultProtocolStackAC0dE0Cvg
+ _$s7Network14NWProtocolQUICC19PathRecoveryTimeoutO12millisecondsyAESicAEmFWC
+ _$s7Network14NWProtocolQUICC19PathRecoveryTimeoutOMa
+ _$s7Network14NWProtocolQUICC7OptionsC19pathRecoveryTimeoutAC04PathfG0OvsTj
+ _$s7Network14NWProtocolQUICC7OptionsCMa
+ _$s7Network4QUICV19pathRecoveryTimeoutyAcA010NWProtocolB0C04PathdE0OF
+ _$sSa9_getCountSiyF7Network17NWProtocolOptionsC_Tg5
CStrings:
+ "boundPathRecovery: no QUIC options in the protocol stack, path recovery stays unbounded"
```
