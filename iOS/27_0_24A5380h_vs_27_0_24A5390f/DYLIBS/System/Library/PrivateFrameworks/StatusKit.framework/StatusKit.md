## StatusKit

> `/System/Library/PrivateFrameworks/StatusKit.framework/StatusKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0x1810` | `0x1100` | **`-0x710`** |
| `__DATA_DIRTY.__bss` | `0x170` | `0x880` | **`+0x710`** |
| `__AUTH.__objc_data` | `0x460` | `0x48` | **`-0x418`** |
| `__DATA_DIRTY.__objc_data` | `0x8e8` | `0xd00` | **`+0x418`** |
| `__TEXT.__text` | `0x45974` | `0x456a0` | **`-0x2d4`** |
| `__DATA_DIRTY.__data` | `0x7a0` | `0x8a0` | **`+0x100`** |
| `__TEXT.__cstring` | `0x1d6e` | `0x1c7e` | **`-0xf0`** |
| `__DATA.__data` | `0x948` | `0x860` | **`-0xe8`** |
| `__AUTH_CONST.__cfstring` | `0x1200` | `0x1180` | **`-0x80`** |
| `__TEXT.__oslogstring` | `0x5419` | `0x5469` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0x3890` | `0x3850` | **`-0x40`** |
| `__TEXT.__gcc_except_tab` | `0x8b8` | `0x884` | **`-0x34`** |

### Other Changes

```diff

-149.100.1.0.0
+151.100.1.0.0

-  Functions: 1705
-  Symbols:   3458
-  CStrings:  541
+  Functions: 1704
+  Symbols:   3454
+  CStrings:  538
Symbols:
+ +[NSString(StatusKit) sk_descriptionFromSKUpdatePriority:]
+ -[NSString(StatusKit) sk_clientIdentifierPrefixFromPresenceIdentifier]
+ -[NSString(StatusKit) sk_sha256Hash]
+ -[SKPresence _releaseDaemonConnectionAlreadyLocked]
+ GCC_except_table100
+ GCC_except_table106
+ GCC_except_table110
+ GCC_except_table131
+ GCC_except_table144
+ GCC_except_table149
+ GCC_except_table150
+ GCC_except_table155
+ GCC_except_table158
+ GCC_except_table46
+ GCC_except_table51
+ GCC_except_table75
+ GCC_except_table81
+ GCC_except_table87
+ GCC_except_table92
+ GCC_except_table97
+ __OBJC_$_CATEGORY_CLASS_METHODS_NSString_$_StatusKit
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_NSString_$_StatusKit
+ __OBJC_$_CATEGORY_NSString_$_StatusKit
+ __OBJC_$_PROP_LIST_NSString_$_StatusKit
- +[NSString(StatusKitAgent) descriptionFromSKUpdatePriority:]
- -[NSString(StatusKitAgent) clientIdentifierPrefixFromPresenceIdentifier]
- -[NSString(StatusKitAgent) ska_appearsToBeEmail]
- -[NSString(StatusKitAgent) ska_sha256Hash]
- GCC_except_table102
- GCC_except_table108
- GCC_except_table112
- GCC_except_table133
- GCC_except_table146
- GCC_except_table151
- GCC_except_table152
- GCC_except_table157
- GCC_except_table160
- GCC_except_table31
- GCC_except_table42
- GCC_except_table48
- GCC_except_table53
- GCC_except_table58
- GCC_except_table63
- GCC_except_table77
- GCC_except_table83
- GCC_except_table89
- GCC_except_table94
- GCC_except_table99
- __OBJC_$_CATEGORY_CLASS_METHODS_NSString_$_StatusKitAgent
- __OBJC_$_CATEGORY_INSTANCE_METHODS_NSString_$_StatusKitAgent
- __OBJC_$_CATEGORY_NSString_$_StatusKitAgent
- __OBJC_$_PROP_LIST_NSString_$_StatusKitAgent
CStrings:
+ "Stale daemon disconnection handler, ignoring and not invalidating newer connection."
- "@"
- "Attempted to assert on channel that is not equivalent to active channel"
- "Attempted to retain subscription on channel that is not equivalent to active channel"
- "Attempted to set persistent payload on channel that is not equivalent to active channel"
```
