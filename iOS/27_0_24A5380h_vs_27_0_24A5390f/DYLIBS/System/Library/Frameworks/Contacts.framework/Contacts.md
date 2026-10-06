## Contacts

> `/System/Library/Frameworks/Contacts.framework/Contacts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22096c` | `0x221678` | **`+0xd0c`** |
| `__DATA_DIRTY.__bss` | `0xbf8` | `0x1128` | **`+0x530`** |
| `__DATA.__bss` | `0x65b0` | `0x6090` | **`-0x520`** |
| `__AUTH.__objc_data` | `0x6df8` | `0x6b50` | **`-0x2a8`** |
| `__DATA_DIRTY.__objc_data` | `0x5370` | `0x5618` | **`+0x2a8`** |
| `__TEXT.__oslogstring` | `0xf67a` | `0xf75a` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0x1be18` | `0x1be70` | **`+0x58`** |
| `__AUTH_CONST.__objc_const` | `0x2db70` | `0x2dbc0` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x9d28` | `0x9d70` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x9208` | `0x9240` | **`+0x38`** |
| `__AUTH_CONST.__cfstring` | `0xdfa0` | `0xdfc0` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x91f1` | `0x9211` | **`+0x20`** |
| `__TEXT.__cstring` | `0xcbf9` | `0xcc19` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x600` | `0x5e8` | **`-0x18`** |
| `__AUTH.__data` | `0x8a8` | `0x8b0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1db0` | `0x1db8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1328` | `0x132c` | **`+0x4`** |

### Other Changes

```diff

-3837.100.1.0.0
+3839.100.3.2.1

-  Functions: 14213
-  Symbols:   20154
-  CStrings:  3446
+  Functions: 14232
+  Symbols:   20164
+  CStrings:  3452
Symbols:
+ +[CNContact(Predicates_Private) predicateForContactsMatchingEmailAddressPrefix:]
+ +[CNContactProviderSupportManager log]
+ -[CNContactProviderSupportManager clientBundleIdentifier]
+ -[CNContactProviderSupportManager hasSPIEntitlement]
+ -[CNContactProviderSupportManager isProviderExtensionEnabled]
+ -[CNEmailAddressContactPredicate initWithEmailAddress:groupIdentifiers:prefixSearch:returnMultipleResults:]
+ -[CNEmailAddressContactPredicate initWithEmailAddress:prefixSearch:returnMultipleResults:]
+ -[CNEmailAddressContactPredicate prefixSearch]
+ _CNEntitlementNameContactsFrameworkSPI
+ _OBJC_IVAR_$_CNContactProviderSupportManager._clientBundleIdentifier
+ _OBJC_IVAR_$_CNContactProviderSupportManager._hasSPIEntitlement
+ _OBJC_IVAR_$_CNEmailAddressContactPredicate._prefixSearch
+ ___38+[CNContactProviderSupportManager log]_block_invoke
+ ___38-[CNEmailAddressContactPredicate hash]_block_invoke_4
+ ___42-[CNEmailAddressContactPredicate isEqual:]_block_invoke_4
- -[CNContactProviderSupportManager clientLoggingIdentifier]
- -[CNContactProviderSupportiOSDataMapper defaultContainerIdentifierImpl]
- _OBJC_IVAR_$_CNContactProviderSupportManager._clientLoggingIdentifier
- _OBJC_IVAR_$_CNContactProviderSupportiOSDataMapper._cachedContainerIdentifier
- ___67-[CNContactProviderSupportiOSDataMapper defaultContainerIdentifier]_block_invoke
CStrings:
+ "%@ has no SPI access to CNContactProviderSupportDomainCommand %@"
+ "%@ has no SPI access to set CNContactProviderSupportDomainCommand.bundleIdentifier (%@)"
+ "Failed to check SPI entitlement, error: %@"
+ "No provider access allowed"
+ "_prefixSearch"
+ "support-manager"
```
