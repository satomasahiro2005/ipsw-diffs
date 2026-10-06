## CoreServicesStore

> `/System/Library/PrivateFrameworks/CoreServicesStore.framework/CoreServicesStore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2bf48` | `0x2c06c` | **`+0x124`** |
| `__TEXT.__oslogstring` | `0x1835` | `0x1872` | **`+0x3d`** |
| `__TEXT.__gcc_except_tab` | `0x3b80` | `0x3ba8` | **`+0x28`** |

### Other Changes

```diff

-1504.0.0.0.0
+1507.0.0.0.0

-  CStrings:  419
+  CStrings:  420
Functions:
~ __ZN8CSStore26String3GetERNS_5StoreEj : 388 -> 376
~ __ZNK8CSStore25Array15enumerateValuesEU13block_pointerFvjRKjPbE : 360 -> 316
~ __ZNK8CSStore25Array12getAllValuesEv : 444 -> 408
~ __CSDictionaryCreateWithKeysAndValues : 1756 -> 1772
~ __ZN8CSStore27HashMapIjjNS_20_IdentifierFunctionsELy1EE6CreateERNS_5StoreERKNSt3__113unordered_mapIjjNS5_4hashIjEENS5_8equal_toIjEENS5_9allocatorINS5_4pairIKjjEEEEEEj : 320 -> 348
~ __ZN8CSStore25Store12allocateUnitEPNS_5TableEjj : 528 -> 696
~ __ZN8CSStore27HashMapIjjNS_20_IdentifierFunctionsELy1EE6CreateERKNS_5StoreERKNSt3__113unordered_mapIjjNS6_4hashIjEENS6_8equal_toIjEENS6_9allocatorINS6_4pairIKjjEEEEEEjjPj : 940 -> 1020
~ __ZN8CSStore27HashMapIjNS_17_StringCacheEntryENS_16_StringFunctionsELy0EE6CreateERKNS_5StoreERKNSt3__113unordered_mapIjS1_NS7_4hashIjEENS7_8equal_toIjEENS7_9allocatorINS7_4pairIKjS1_EEEEEEjjPj : 960 -> 1024
~ __ZN8CSStore27HashMapIjjNS_10Dictionary10_FunctionsELy0EE6CreateERKNS_5StoreERKNSt3__113unordered_mapIjjNS7_4hashIjEENS7_8equal_toIjEENS7_9allocatorINS7_4pairIKjjEEEEEEjjPj : 940 -> 1020
~ +[_CSVisualizer breakDownTable:inStore:buffer:] : 1888 -> 1872
~ ___47+[_CSVisualizer breakDownTable:inStore:buffer:]_block_invoke : 1024 -> 1008
~ __ZN8CSStore25Array7_unpackEv : 308 -> 288
CStrings:
+ "Refusing to allocate unit of length %llu in table %{public}s"
```
