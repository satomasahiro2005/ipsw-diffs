## InternationalTextSearch

> `/System/Library/PrivateFrameworks/InternationalTextSearch.framework/InternationalTextSearch`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__unwind_info` | `0xd8` | `0xd0` | **`-0x8`** |

### Other Changes

```text
Functions:
~ _ITSGetCollationContextForDatabaseConnectionHandle -> _ITSRegisterSQLiteICUTokenizer : 116 -> 328
~ _ITSCollationContextFreeContextForDatabaseHandle -> _ITSSetCollationContextForDatabaseConnectionHandle : 120 -> 140
~ _ITSSetCollationContextForDatabaseConnectionHandle -> _ITSCollationContextFreeContextForDatabaseHandle : 140 -> 120
~ _ITSRegisterSQLiteICUTokenizer -> _ITSGetCollationContextForDatabaseConnectionHandle : 328 -> 116
```
