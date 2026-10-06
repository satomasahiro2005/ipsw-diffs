## AdCore

> `/System/Library/PrivateFrameworks/AdCore.framework/AdCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x5c70` | `0x6c40` | **`+0xfd0`** |
| `__TEXT.__text` | `0x30a98` | `0x31670` | **`+0xbd8`** |
| `__TEXT.__objc_methlist` | `0x4074` | `0x42d4` | **`+0x260`** |
| `__AUTH.__objc_data` | `0x230` | `0x460` | **`+0x230`** |
| `__DATA.__data` | `0x1e0` | `0x300` | **`+0x120`** |
| `__DATA_CONST.__objc_selrefs` | `0x2018` | `0x20f8` | **`+0xe0`** |
| `__AUTH_CONST.__cfstring` | `0x4d00` | `0x4da0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x3fed` | `0x405d` | **`+0x70`** |
| `__TEXT.__const` | `0x180` | `0x1e0` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x348` | `0x390` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0xc48` | `0xc90` | **`+0x48`** |
| `__DATA_CONST.__objc_classlist` | `0x150` | `0x188` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x6c8` | `0x6f0` | **`+0x28`** |
| `__DATA_CONST.__objc_superrefs` | `0x150` | `0x178` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x3f8` | `0x418` | **`+0x20`** |
| `__DATA_CONST.__objc_protolist` | `0x28` | `0x40` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x4a0` | `0x4b0` | **`+0x10`** |

### Other Changes

```diff

-638.1.7.0.0
+638.2.0.0.0

+  - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics

-  Functions: 1419
-  Symbols:   2378
-  CStrings:  655
+  Functions: 1454
+  Symbols:   2495
+  CStrings:  661
Symbols:
+ +[ADAccountSyncDiagnosticSample sampleWithRemoteLoadStatus:localStoreStatus:storefrontID:]
+ +[ADAccountSyncDiagnostics(Production) production]
+ +[ADStorefront storefrontWithValue:]
+ +[ADStorefrontID storefrontIDWithValue:]
+ -[ADAccountSyncDiagnosticSample .cxx_destruct]
+ -[ADAccountSyncDiagnosticSample initWithRemoteLoadStatus:localStoreStatus:storefrontID:]
+ -[ADAccountSyncDiagnosticSample loadStatus]
+ -[ADAccountSyncDiagnosticSample storeStatus]
+ -[ADAccountSyncDiagnosticSample storefrontID]
+ -[ADAccountSyncDiagnostics .cxx_destruct]
+ -[ADAccountSyncDiagnostics depositLoadStatus:storeStatus:]
+ -[ADAccountSyncDiagnostics depot]
+ -[ADAccountSyncDiagnostics initWithDepot:storefrontIDSource:]
+ -[ADAccountSyncDiagnostics loadStatusForCocoaError:]
+ -[ADAccountSyncDiagnostics loadStatusForCoreError:]
+ -[ADAccountSyncDiagnostics loadStatusForError:]
+ -[ADAccountSyncDiagnostics localStoreCompletedWithStatus:]
+ -[ADAccountSyncDiagnostics remoteLoadFailedWithError:]
+ -[ADAccountSyncDiagnostics storeStatusForStatus:]
+ -[ADAccountSyncDiagnostics storefrontIDSource]
+ -[ADAdCoreSettingsStorefrontSource storefront]
+ -[ADCoreAnalyticsAccountSyncDiagnosticDepot depositSample:]
+ -[ADStorefront initWithValue:]
+ -[ADStorefront storefrontID]
+ -[ADStorefront value]
+ -[ADStorefrontID hash]
+ -[ADStorefrontID initWithValue:]
+ -[ADStorefrontID isEqual:]
+ -[ADStorefrontID isEqualToStorefrontID:]
+ -[ADStorefrontID value]
+ -[ADStorefrontToStorefrontIDSource .cxx_destruct]
+ -[ADStorefrontToStorefrontIDSource initWithStorefrontSource:]
+ -[ADStorefrontToStorefrontIDSource storefrontID]
+ -[ADStorefrontToStorefrontIDSource storefrontSource]
+ _AnalyticsSendEventLazy
+ _NSCocoaErrorDomain
+ _OBJC_CLASS_$_ADAccountSyncDiagnosticSample
+ _OBJC_CLASS_$_ADAccountSyncDiagnostics
+ _OBJC_CLASS_$_ADAdCoreSettingsStorefrontSource
+ _OBJC_CLASS_$_ADCoreAnalyticsAccountSyncDiagnosticDepot
+ _OBJC_CLASS_$_ADStorefront
+ _OBJC_CLASS_$_ADStorefrontID
+ _OBJC_CLASS_$_ADStorefrontToStorefrontIDSource
+ _OBJC_CLASS_$_NSCharacterSet
+ _OBJC_IVAR_$_ADAccountSyncDiagnosticSample._loadStatus
+ _OBJC_IVAR_$_ADAccountSyncDiagnosticSample._storeStatus
+ _OBJC_IVAR_$_ADAccountSyncDiagnosticSample._storefrontID
+ _OBJC_IVAR_$_ADAccountSyncDiagnostics._depot
+ _OBJC_IVAR_$_ADAccountSyncDiagnostics._storefrontIDSource
+ _OBJC_IVAR_$_ADStorefront._value
+ _OBJC_IVAR_$_ADStorefrontID._value
+ _OBJC_IVAR_$_ADStorefrontToStorefrontIDSource._storefrontSource
+ _OBJC_METACLASS_$_ADAccountSyncDiagnosticSample
+ _OBJC_METACLASS_$_ADAccountSyncDiagnostics
+ _OBJC_METACLASS_$_ADAdCoreSettingsStorefrontSource
+ _OBJC_METACLASS_$_ADCoreAnalyticsAccountSyncDiagnosticDepot
+ _OBJC_METACLASS_$_ADStorefront
+ _OBJC_METACLASS_$_ADStorefrontID
+ _OBJC_METACLASS_$_ADStorefrontToStorefrontIDSource
+ __OBJC_$_CLASS_METHODS_ADAccountSyncDiagnosticSample
+ __OBJC_$_CLASS_METHODS_ADAccountSyncDiagnostics(Production)
+ __OBJC_$_CLASS_METHODS_ADStorefront
+ __OBJC_$_CLASS_METHODS_ADStorefrontID
+ __OBJC_$_INSTANCE_METHODS_ADAccountSyncDiagnosticSample
+ __OBJC_$_INSTANCE_METHODS_ADAccountSyncDiagnostics
+ __OBJC_$_INSTANCE_METHODS_ADAdCoreSettingsStorefrontSource
+ __OBJC_$_INSTANCE_METHODS_ADCoreAnalyticsAccountSyncDiagnosticDepot
+ __OBJC_$_INSTANCE_METHODS_ADStorefront
+ __OBJC_$_INSTANCE_METHODS_ADStorefrontID
+ __OBJC_$_INSTANCE_METHODS_ADStorefrontToStorefrontIDSource
+ __OBJC_$_INSTANCE_VARIABLES_ADAccountSyncDiagnosticSample
+ __OBJC_$_INSTANCE_VARIABLES_ADAccountSyncDiagnostics
+ __OBJC_$_INSTANCE_VARIABLES_ADStorefront
+ __OBJC_$_INSTANCE_VARIABLES_ADStorefrontID
+ __OBJC_$_INSTANCE_VARIABLES_ADStorefrontToStorefrontIDSource
+ __OBJC_$_PROP_LIST_ADAccountSyncDiagnosticSample
+ __OBJC_$_PROP_LIST_ADAccountSyncDiagnostics
+ __OBJC_$_PROP_LIST_ADAdCoreSettingsStorefrontSource
+ __OBJC_$_PROP_LIST_ADCoreAnalyticsAccountSyncDiagnosticDepot
+ __OBJC_$_PROP_LIST_ADStorefront
+ __OBJC_$_PROP_LIST_ADStorefrontID
+ __OBJC_$_PROP_LIST_ADStorefrontToStorefrontIDSource
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_ADAccountSyncDiagnosticDepot
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_ADStorefrontIDSource
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_ADStorefrontSource
+ __OBJC_$_PROTOCOL_METHOD_TYPES_ADAccountSyncDiagnosticDepot
+ __OBJC_$_PROTOCOL_METHOD_TYPES_ADStorefrontIDSource
+ __OBJC_$_PROTOCOL_METHOD_TYPES_ADStorefrontSource
+ __OBJC_$_PROTOCOL_REFS_ADAccountSyncDiagnosticDepot
+ __OBJC_$_PROTOCOL_REFS_ADStorefrontIDSource
+ __OBJC_$_PROTOCOL_REFS_ADStorefrontSource
+ __OBJC_CLASS_PROTOCOLS_$_ADAdCoreSettingsStorefrontSource
+ __OBJC_CLASS_PROTOCOLS_$_ADCoreAnalyticsAccountSyncDiagnosticDepot
+ __OBJC_CLASS_PROTOCOLS_$_ADStorefrontToStorefrontIDSource
+ __OBJC_CLASS_RO_$_ADAccountSyncDiagnosticSample
+ __OBJC_CLASS_RO_$_ADAccountSyncDiagnostics
+ __OBJC_CLASS_RO_$_ADAdCoreSettingsStorefrontSource
+ __OBJC_CLASS_RO_$_ADCoreAnalyticsAccountSyncDiagnosticDepot
+ __OBJC_CLASS_RO_$_ADStorefront
+ __OBJC_CLASS_RO_$_ADStorefrontID
+ __OBJC_CLASS_RO_$_ADStorefrontToStorefrontIDSource
+ __OBJC_LABEL_PROTOCOL_$_ADAccountSyncDiagnosticDepot
+ __OBJC_LABEL_PROTOCOL_$_ADStorefrontIDSource
+ __OBJC_LABEL_PROTOCOL_$_ADStorefrontSource
+ __OBJC_METACLASS_RO_$_ADAccountSyncDiagnosticSample
+ __OBJC_METACLASS_RO_$_ADAccountSyncDiagnostics
+ __OBJC_METACLASS_RO_$_ADAdCoreSettingsStorefrontSource
+ __OBJC_METACLASS_RO_$_ADCoreAnalyticsAccountSyncDiagnosticDepot
+ __OBJC_METACLASS_RO_$_ADStorefront
+ __OBJC_METACLASS_RO_$_ADStorefrontID
+ __OBJC_METACLASS_RO_$_ADStorefrontToStorefrontIDSource
+ __OBJC_PROTOCOL_$_ADAccountSyncDiagnosticDepot
+ __OBJC_PROTOCOL_$_ADStorefrontIDSource
+ __OBJC_PROTOCOL_$_ADStorefrontSource
+ ___59-[ADCoreAnalyticsAccountSyncDiagnosticDepot depositSample:]_block_invoke
+ ___block_descriptor_40_e8_32s_e19_"NSDictionary"8?0ls32l8
+ _objc_retain_x4
CStrings:
+ "-,"
+ "@\"NSDictionary\"8@?0"
+ "com.apple.ap.adprivacyd.account.syncStatus"
+ "localSaveStatus"
+ "remoteLoadStatus"
+ "storefrontID"
```
