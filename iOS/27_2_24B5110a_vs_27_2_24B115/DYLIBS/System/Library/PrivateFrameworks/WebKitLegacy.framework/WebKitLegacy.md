## WebKitLegacy

> `/System/Library/PrivateFrameworks/WebKitLegacy.framework/WebKitLegacy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x164f30` | `0x164ffc` | **`+0xcc`** |
| `__AUTH_CONST.__auth_got` | `0x46c0` | `0x46c8` | **`+0x8`** |

### Other Changes

```diff

-625.2.8.10.4
+625.2.8.10.6

-  Symbols:   13060
+  Symbols:   13061
Symbols:
+ __ZNK7WebCore21SerializedScriptValue5cloneEv
Functions:
~ __ZN27WebBroadcastChannelRegistry11postMessageERKN7WebCore25PartitionedSecurityOriginERKN3WTF6StringENS4_23ObjectIdentifierGenericINS0_30BroadcastChannelIdentifierTypeENS4_38ObjectIdentifierThreadSafeAccessTraitsIyEEyEEONS4_3RefINS0_21SerializedScriptValueENS4_12RawPtrTraitsISE_EENS4_21DefaultRefDerefTraitsISE_EEEEONS4_17CompletionHandlerIFvvEEE : 748 -> 952
```
