## CryptoKitCBridging

> `/System/Library/PrivateFrameworks/CryptoKitCBridging.framework/CryptoKitCBridging`

### Other Changes

```diff

-381.0.0.0.0
+383.0.3.0.0
Functions:
~ +[SEPUtils dataFromACL:] -> _keyIsCompactRepresentable : 44 -> 340
~ _SPAKE2CtxSize -> +[SEPUtils dataFromACL:] : 40 -> 44
~ _SPAKE2GetSessionKey -> _SPAKE2Alishaz0Size : 4 -> 40
~ _AESLubyRackoffContextSize -> _SPAKE2GetSessionKey : 8 -> 4
~ _keyIsCompactRepresentable -> _AESLubyRackoffContextSize : 340 -> 8
```
