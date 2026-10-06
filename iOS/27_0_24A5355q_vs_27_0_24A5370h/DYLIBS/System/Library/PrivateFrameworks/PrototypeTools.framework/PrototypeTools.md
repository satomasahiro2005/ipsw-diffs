## PrototypeTools

> `/System/Library/PrivateFrameworks/PrototypeTools.framework/PrototypeTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18c34` | `0x18c18` | **`-0x1c`** |
| `__AUTH_CONST.__objc_intobj` | `0x288` | `0x2a0` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1488` | `0x1490` | **`+0x8`** |
| `__TEXT.__cstring` | `0x1319` | `0x1313` | **`-0x6`** |

### Other Changes

```diff

-163.0.0.0.0
+164.0.0.0.0
Functions:
~ +[PTSettingsClassStructure structureForSettingsClass:] : 1304 -> 1300
~ -[PTSettings _createChildren] : 288 -> 284
~ ____NSObjectProtocolProperties_block_invoke : 184 -> 180
~ -[PTDefaults _bindAndRegisterDefaults] : 976 -> 980
~ -[PTSettings _createOutlets] : 300 -> 296
~ +[PTProxySettingsDefinition definitionForSettingsClass:] : 532 -> 528
~ -[PTProxySettingsDefinition allSettingsClassesExistAndHaveCorrectVersion] : 308 -> 304
~ -[PTRow _sendValueChanged] : 292 -> 288
~ -[PTRow _sendTitleChanged] : 292 -> 288
~ -[PTRow _sendImageChanged] : 292 -> 288
~ -[PTRow _sendRowDidReload] : 292 -> 288
~ ___27+[PTDomain _sharedInstance]_block_invoke_2 : 368 -> 364
~ ___27+[PTDomain _sharedInstance]_block_invoke.7 : 380 -> 376
~ ___27+[PTDomain _sharedInstance]_block_invoke.9 : 368 -> 364
~ ___27+[PTDomain _sharedInstance]_block_invoke.10 : 248 -> 244
~ -[PTOutlet _invokeActions] : 284 -> 280
~ -[PTSettingsClassStructure filteredForProxySettings] : 816 -> 812
~ -[PTSettingsClassStructure _generateClassNamesIfNecessary] : 344 -> 340
~ _PTDebugServerInterface : 20 -> 204
~ -[PTSection initWithRows:] : 384 -> 380
~ -[PTSection setSettings:] : 400 -> 396
~ -[PTSection _remoteEditingWhitelistedComponent] : 452 -> 448
~ -[PTSection _updateEnabledRows] : 440 -> 436
~ -[PTSection _reloadEnabledRows] : 292 -> 288
~ _PTObjectIsRecursivelyPlistable : 576 -> 568
~ _PTValidateDictionary : 376 -> 372
~ _PTValidateArray : 320 -> 316
~ _PTValidateSet : 320 -> 316
~ -[PTModule initWithContents:] : 504 -> 500
~ -[PTModule dealloc] : 288 -> 284
~ -[PTModule setSettings:] : 448 -> 444
~ -[PTModule section:didInsertRows:deleteRows:] : 616 -> 612
~ -[PTModule sectionDidReload:] : 328 -> 324
~ -[PTModule _computeEnabledSections] : 348 -> 344
~ -[PTModule _reportSectionInsertsAndDeletesRelativeTo:] : 604 -> 596
~ -[PTModule _remoteEditingWhitelistedModule] : 436 -> 432
~ __PTMigrateIfNecessary : 496 -> 492
~ -[PTSettings _validateChildren] : 328 -> 324
~ -[PTSettings _applyArchiveDictionary:] : 592 -> 588
~ -[PTSettings archiveDictionary] : 580 -> 576
~ -[PTSettings applySettings:] : 512 -> 504
~ -[PTSettings _startObservingProperties] : 268 -> 264
~ -[PTSettings _stopObservingProperties] : 260 -> 256
~ -[PTSettings _startObservingChildren] : 288 -> 284
~ -[PTSettings _stopObservingChildren] : 284 -> 280
~ -[PTSettings _keyForChild:] : 340 -> 336
~ -[PTSettings _sendKeyChanged:] : 272 -> 268
~ -[PTSettings _sendKeyPathChanged:] : 272 -> 268
~ ___44-[PTDomainServer sendEvent:forTestRecipeID:]_block_invoke : 452 -> 448
~ -[PTDomainServer _queue_persistChanges] : 576 -> 572
~ -[PTDomainServer _queue_sendArchiveValue:forKeyPath:domainID:] : 316 -> 312
~ -[PTDomainServer _queue_sendRestoreDefaultsForDomainID:] : 260 -> 256
~ -[PTDomainServer _queue_invokeOutletAtKeyPath:domainID:] : 404 -> 400
CStrings:
+ "MultiWindowMode"
+ "multiWindowMode"
- "MultiWindowEnabled"
- "multiWindowEnabled"
```
