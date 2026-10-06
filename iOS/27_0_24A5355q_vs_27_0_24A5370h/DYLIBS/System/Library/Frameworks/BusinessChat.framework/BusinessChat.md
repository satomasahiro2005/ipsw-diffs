## BusinessChat

> `/System/Library/Frameworks/BusinessChat.framework/BusinessChat`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x124a4` | `0x12458` | **`-0x4c`** |

### Other Changes

```diff

-30122.30.5.19.1
+30123.30.6.2.1
Functions:
~ -[BCInternalAuthenticationResponse initWithDictionary:] : 1108 -> 1104
~ -[BCInternalAuthenticationResponse dictionaryValue] : 464 -> 460
~ -[BCNativeOAuth2Response dictionaryValue] : 516 -> 512
~ -[BCServerSideOAuth2Response initWithRedirectURI:] : 1048 -> 1040
~ +[BCOAuth2ResponseFactory makeResponseObjectWithDictionary:version:] : 880 -> 876
~ -[BCMessageData initWithUrl:data:] : 672 -> 668
~ -[BCInternalAuthenticationRequest initWithDictionary:] : 1352 -> 1348
~ -[BCInternalAuthenticationRequest dictionaryValue] : 480 -> 476
~ -[BCImageStore generateImageDictionaryFromArray:] : 808 -> 804
~ -[BCImageStore initWithImages:] : 476 -> 472
~ -[BCMessage isAnyUnknownRootKey] : 360 -> 356
~ -[NSURL fragments] : 448 -> 444
~ +[BCServerSideOAuth2URLProvider URLProviderWithDictionary:] : 1908 -> 1904
~ +[BCChatAction openTranscript:intentParameters:] : 628 -> 624
~ ___52-[BCInternalAuthenticationManager fetchCredentials:]_block_invoke : 1528 -> 1524
~ -[BCAuthenticationManager fetchTokenWithRequest:completion:] : 1620 -> 1616
~ -[BCAuthenticationManager processQueryItems:completion:] : 556 -> 552
~ +[BCNativeOAuth2URLProvider URLProviderWithDictionary:] : 1840 -> 1836
```
