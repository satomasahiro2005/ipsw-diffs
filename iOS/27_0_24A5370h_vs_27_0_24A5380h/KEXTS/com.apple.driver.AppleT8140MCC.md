## com.apple.driver.AppleT8140MCC

> `com.apple.driver.AppleT8140MCC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x168a0` | `0x16894` | **`-0xc`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-125.0.0.0.0
-  Functions: 574
+127.0.0.0.0
+  Functions: 573
Functions:
~ __ZN25AppleMemCacheControllerV29getPTDIdxEPKcPjS2_ : 620 -> 624
~ __ZN11MemCacheCIP5startEP9IOService : 4768 -> 4804
- sub_fffffff00982c3b4
CStrings:
+ "\"%s: \" \"Total AMCC Count %d exceeds the max value that the _amccEnableMask can represent\" @%s:%d"
- "\"%s: \" \"Total AMCC Count %d exceeds the max value that the _amccEnbaleMask can represent\" @%s:%d"
```
