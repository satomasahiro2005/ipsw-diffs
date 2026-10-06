## AppSupport

> `/System/Library/PrivateFrameworks/AppSupport.framework/AppSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x5c8` | `0x690` | **`+0xc8`** |
| `__DATA_DIRTY.__objc_data` | `0x348` | `0x280` | **`-0xc8`** |
| `__TEXT.__text` | `0x2df24` | `0x2de64` | **`-0xc0`** |

### Other Changes

```diff

-2666.0.0.0.0
+2668.0.0.0.0
Functions:
~ _ExplainQueryPlanCallback : 376 -> 380
~ -[CPSearchMatcher matchesASCIIString:matchType:] : 1028 -> 1004
~ _matche : 5744 -> 5540
~ _utf8_encodestr : 784 -> 816
```
