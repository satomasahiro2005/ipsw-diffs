## AddressBookLegacy

> `/System/Library/PrivateFrameworks/AddressBookLegacy.framework/AddressBookLegacy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77c20` | `0x78440` | **`+0x820`** |
| `__TEXT.__cstring` | `0x26eb5` | `0x26ff0` | **`+0x13b`** |
| `__AUTH_CONST.__cfstring` | `0xdd80` | `0xde40` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x2858` | `0x2880` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1a88` | `0x1aa0` | **`+0x18`** |
| `__DATA.__bss` | `0x3c0` | `0x3b0` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2570` | `0x2580` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0xf8` | `0x108` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x3074` | `0x307c` | **`+0x8`** |

### Other Changes

```diff

-12875.100.2.0.0
+12876.100.1.0.0

-  Functions: 2620
-  Symbols:   4434
-  CStrings:  2542
+  Functions: 2627
+  Symbols:   4442
+  CStrings:  2548
Symbols:
+ +[ABSQLPredicate predicateForContactsMatchingMultivaluePropertyPrefix:values:groupIdentifiers:containerIdentifiers:limitToOneResult:map:]
+ ___137+[ABSQLPredicate predicateForContactsMatchingMultivaluePropertyPrefix:values:groupIdentifiers:containerIdentifiers:limitToOneResult:map:]_block_invoke
+ ___137+[ABSQLPredicate predicateForContactsMatchingMultivaluePropertyPrefix:values:groupIdentifiers:containerIdentifiers:limitToOneResult:map:]_block_invoke_2
+ ___137+[ABSQLPredicate predicateForContactsMatchingMultivaluePropertyPrefix:values:groupIdentifiers:containerIdentifiers:limitToOneResult:map:]_block_invoke_3
+ ___137+[ABSQLPredicate predicateForContactsMatchingMultivaluePropertyPrefix:values:groupIdentifiers:containerIdentifiers:limitToOneResult:map:]_block_invoke_4
+ ___137+[ABSQLPredicate predicateForContactsMatchingMultivaluePropertyPrefix:values:groupIdentifiers:containerIdentifiers:limitToOneResult:map:]_block_invoke_5
+ ___137+[ABSQLPredicate predicateForContactsMatchingMultivaluePropertyPrefix:values:groupIdentifiers:containerIdentifiers:limitToOneResult:map:]_block_invoke_6
+ ___block_descriptor_76_e8_32o40o48o56o64o_e19_v16?0"ABBinders"8ls32l8s40l8s48l8s56l8s64l8
CStrings:
+ "SELECT %@ FROM ABMultivalue abmv %@ %@ WHERE value LIKE ? ESCAPE '\\' AND property = ? %@ %@ %@"
+ "WITH ABQuery(term) AS ( %@ ) SELECT %@ FROM ABMultivalue abmv JOIN ABQuery ON SUBSTR(value, 1, LENGTH(term)) = term COLLATE NOCASE %@ %@ WHERE property = ? %@ %@ %@"
+ "\\%"
+ "\\_"
+ "_"
+ "ab_collect_value_row_map(?, ?, abmv.record_id)"
```
