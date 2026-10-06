## nanoregistryd

> `/usr/libexec/nanoregistryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__got` | `0xc90` | `0xdc8` | **`+0x138`** |
| `__TEXT.__oslogstring` | `0x16191` | `0x16281` | **`+0xf0`** |
| `__TEXT.__text` | `0x100628` | `0x1006b4` | **`+0x8c`** |
| `__TEXT.__cstring` | `0xe0aa` | `0xe0ac` | **`+0x2`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1075.1.0.0.0
+1075.1.1.0.0

-  Functions: 5827
+  Functions: 5828

-  CStrings:  8651
+  CStrings:  8652
Functions:
~ sub_100061644 : 660 -> 732
+ sub_1000fd968
CStrings:
+ "72"
+ "BLOCKSYNCTESTMODE ENABLED: EPSagaTransactionPairedSync paired sync disabled because internal default blockSyncTestMode (com.apple.NanoRegistry) is set; skipping initial sync and not posting NRInitialPairedSyncDidCompleteDarwinNotification."
+ "NanoRegistry-1075.1.1"
- "55"
- "NanoRegistry-1075.1"
```
