## VideoSubscriberAccount

> `/System/Library/Frameworks/VideoSubscriberAccount.framework/VideoSubscriberAccount`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe4428` | `0xe4204` | **`-0x224`** |

### Other Changes

```diff

-607.0.0.0.0
+608.0.0.0.0
Functions:
~ -[VSSubscriptionPredicateFactory subscriptionFetchPredicateForTask:withOptions:] : 1996 -> 1992
~ -[VSSubscriptionPredicateFactory _expressionByConvertingSubscriptionKeyPathInExpression:toAttributeKeysInEntity:] : 1084 -> 1076
~ -[VSSubscriptionPredicateFactory predicateByConvertingSubscriptionKeyPathsInPredicate:toAttributeKeysInEntity:] : 1024 -> 1020
~ -[VSAppChannelsFilter _updateAdamIDs] : 496 -> 492
~ -[VSAppChannelsFilter personalAppDescriptions] : 372 -> 368
~ -[VSJSEventTargetObject dispatchEvent:withInfo:] : 392 -> 388
~ -[VSAccountStore _fetchAccountsSimulatingExpiredToken:forProviderIDs:completion:] : 3728 -> 3708
~ ___58-[VSAccountStore _updateCachedFirstAccountWithCompletion:]_block_invoke_2.180 : 376 -> 372
~ ___53-[VSAccountStore fetchAccountsWithCompletionHandler:]_block_invoke_4 : 384 -> 380
~ ___53-[VSAccountStore saveAccounts:withCompletionHandler:]_block_invoke : 732 -> 728
~ ___55-[VSAccountStore removeAccounts:withCompletionHandler:]_block_invoke : 864 -> 860
~ -[VSAppleSubscription initWithCustomerID:productCodes:] : 608 -> 604
~ _VSValueTypeInit : 420 -> 416
~ _VSValueTypeEncodeWithCoder : 532 -> 528
~ _VSValueTypeCopyWithZone : 504 -> 500
~ _VSValueTypeHash : 416 -> 412
~ _VSValueTypeIsEqual : 632 -> 620
~ _VSValueTypeDescription : 652 -> 648
~ ___58-[VSPersistentSubscription _deriveValuesFromProvidedInfo:]_block_invoke : 1240 -> 1236
~ ___65-[VSAccountSerializationCenter importData:withCompletionHandler:]_block_invoke : 988 -> 984
~ -[VSStateMachine activateWithState:] : 1416 -> 1408
~ +[VSApplicationUserAccount userAccountsFromApplicationUserAccounts:ForProviderID:allowedBundleIDs:] : 368 -> 364
~ +[VSApplicationUserAccount applicationUserAccountsFromUserAccounts:] : 316 -> 312
~ +[VSJSUserAccount userAccountsFromJSUserAccounts:] : 320 -> 316
~ +[VSJSUserAccount jsUserAccountsFromUserAccounts:] : 332 -> 328
~ -[VSUnbinder dealloc] : 508 -> 504
~ -[VSSubscription _updateHash:withValueForProperty:] : 1724 -> 1720
~ ___55+[VSSubscription keyPathsForValuesAffectingVersionHash]_block_invoke_2 : 344 -> 340
~ -[VSSubscription versionHash] : 336 -> 332
~ -[NSPropertyDescription(VSSubscriptionAdditions) vs_expectedJSONValueClasses] : 392 -> 388
~ -[NSPropertyDescription(VSSubscriptionAdditions) vs_setExpectedJSONValueClasses:] : 360 -> 356
~ -[VSTreeNode(VSEnumeration) _descendantNodesAtDepth:] : 408 -> 404
~ -[VSTreeNode(VSEnumeration) enumerateDescendantsWithOptions:usingBlock:] : 612 -> 604
~ ___67-[NSManagedObjectContext(VSAdditions) vs_removeAllPersistentStores]_block_invoke : 416 -> 412
~ -[VSSubscriptionFetchOptionsValidator subscriptionFetchOptionsAllowedForSecurityTask:] : 1376 -> 1372
~ -[VSSubscriptionFetchOptionsValidator standardizedFetchOptionsFromOptions:withSecurityTask:] : 1412 -> 1408
~ _VSSubscriptionFetchOptionsForBundleIdentifiersAndDomainNames : 616 -> 608
~ ___VSAllSubscriptionFetchOptions_block_invoke_2 : 932 -> 928
~ -[VSPrivacyFacade _voucherForProcess:providerID:] : 552 -> 548
~ -[VSPrivacyFacade knownAppBundles] : 888 -> 880
~ -[VSKeychainItem changedValues] : 536 -> 532
~ -[VSKeychainItem description] : 656 -> 652
~ ___103-[VSManagedProfileConnection profileConnectionDidReceiveEffectiveSettingsChangedNotification:userInfo:]_block_invoke : 296 -> 292
~ -[VSBinder dealloc] : 360 -> 356
~ ___28-[VSBinder tearDownBinding:]_block_invoke : 484 -> 480
~ -[VSBinder observeValueForKeyPath:ofObject:change:context:] : 816 -> 812
~ ___79-[VSIdentityProviderInfoCenter enqueueIdentityProviderAppsQueryWithCompletion:]_block_invoke_2 : 500 -> 496
~ ___80-[VSIdentityProviderInfoCenter _identityProviderForSetTopBoxProfile:completion:]_block_invoke_2 : 376 -> 372
~ -[NSArray(VSAdditions) vs_componentsJoinedByAttributedString:] : 592 -> 552
~ +[VSJSAppleSubscription appleSubscriptionsFromJSAppleSubscriptions:] : 296 -> 292
~ +[VSJSAppleSubscription jsAppleSubscriptionsFromAppleSubscriptions:] : 332 -> 328
~ ___77-[VSDeveloperModeStore fetchDeveloperIdentityProvidersWithCompletionHandler:]_block_invoke.67 : 1700 -> 1696
~ ___86-[VSDeveloperModeStore removeDeveloperIdentityProviderWithUniqueID:completionHandler:]_block_invoke : 868 -> 864
~ -[VSExpressionEvaluator _observersForExpression:] : 1672 -> 1668
~ -[VSExpressionEvaluator _observersForPredicate:] : 796 -> 792
~ ___57-[VSSubscriptionRegistry _saveChangesToContext:withDate:]_block_invoke : 1932 -> 1920
~ ___80-[VSSubscriptionRegistry fetchActiveSubscriptionsWithOptions:completionHandler:]_block_invoke_2 : 2056 -> 2044
~ -[VSSubscriptionRegistry _predicateForPersistentAttributesOfSubscriptions:withEntity:forFiltering:] : 564 -> 560
~ ___68-[VSSubscriptionRegistry removeSubscriptions:withCompletionHandler:]_block_invoke_2 : 1488 -> 1484
~ ___104-[VSUserAccountManager fetchUserAccountWithSourceIdentifier:sourceType:deviceIdentifier:withCompletion:]_block_invoke : 436 -> 432
~ -[VSSubscriptionRegistrationCenter _resetExpirationOperation] : 1132 -> 1124
~ -[VSSubscriptionRegistrationCenter registerSubscription:] : 964 -> 960
~ -[VSSubscriptionRegistrationCenter removeSubscriptions:] : 648 -> 644
~ -[VSSecurityTask shouldAllowAccessToSubscriberIdentifierHashModifier:] : 888 -> 884
~ -[VSIdentityProviderUserAccountUpdateOperation executionDidBegin] : 688 -> 684
~ -[VSIdentityProviderUserAccountUpdateOperation _allowedBundleIDs] : 412 -> 408
~ -[NSDictionary(VSAdditions) vs_objectForCaseInsensitiveKey:] : 336 -> 332
~ -[NSDictionary(VSAdditions) vs_objectForNormalizedKey:] : 516 -> 512
~ -[VSKeychainItemKind attributesByName] : 360 -> 356
~ -[VSKeychainItemKind attributesBySecItemAttributeKey] : 352 -> 348
~ -[VSIdentityProviderUserAccountFetchOperation executionDidBegin] : 640 -> 636
~ ___64-[VSIdentityProviderUserAccountFetchOperation executionDidBegin]_block_invoke.5 : 588 -> 584
~ +[VSApplicationAppleSubscription appleSubscriptionsFromApplicationAppleSubscriptions:] : 320 -> 316
~ +[VSApplicationAppleSubscription applicationAppleSubscriptionsFromAppleSubscriptions:] : 332 -> 328
~ -[VSAuthenticationSchemeValueTransformer reverseTransformedValue:] : 604 -> 600
~ ___39-[VSDevice cloudConfigurationDidChange]_block_invoke : 296 -> 292
~ -[VSSubscriptionPropertyListStore save:] : 816 -> 812
~ +[NSManagedObjectModel(VSDeveloperModeAdditions) vs_identityProviderEntityForVersion:] : 1440 -> 1432
~ +[VSPrivacyVoucherLockbox getVouchersFromSelectedAppDescriptions:forProviderID:] : 472 -> 468
~ _secureCodingSafeObject : 1476 -> 1468
~ -[VSServiceListener listener:shouldAcceptNewConnection:] : 876 -> 872
~ +[VSReverseValueTransformer reverseValueTransformerWithValueTransformer:] : 704 -> 700
~ +[NSEntityDescription(VSSubscriptionAdditions) vs_subscriptionEntityForVersion:] : 3776 -> 3764
~ -[VSAppInstallationInfoCenter installedAppBundleIDs] : 404 -> 400
~ -[VSKeychainEditingContext _populateQuery:usingPredicate:withItemKind:] : 1856 -> 1840
~ -[VSKeychainEditingContext _findOrCreateItemForCommittedValues:withItemKind:] : 556 -> 552
~ -[VSKeychainEditingContext _populateResult:forRequest:fromMatch:] : 548 -> 544
~ -[VSKeychainEditingContext _queryForItemValues:withItemKind:] : 396 -> 392
~ -[VSKeychainEditingContext _deleteQueryForItemValues:withItemKind:] : 548 -> 544
~ -[VSKeychainEditingContext executeFetchRequest:error:] : 1532 -> 1524
~ -[VSKeychainEditingContext save:] : 3104 -> 3044
~ ___29-[VSJSApp _initializeContext]_block_invoke_3 : 496 -> 492
~ -[VSCompoundValueTransformer transformedValue:] : 336 -> 332
~ -[VSCompoundValueTransformer reverseTransformedValue:] : 348 -> 344
~ sub_245cc9a70 -> sub_246e2a83c : 280 -> 276
~ sub_245ccab0c -> sub_246e2b8d4 : 392 -> 384
~ ___swift_closure_destructorTm : 124 -> 132
~ sub_245cd95e0 -> sub_246e3a3a8 : 412 -> 388
~ sub_245cd977c -> sub_246e3a52c : 256 -> 276
~ sub_245cd98d8 -> sub_246e3a69c : 256 -> 264
~ sub_245cd99d8 -> sub_246e3a7a4 : 248 -> 268
~ sub_245ce31a4 -> sub_246e43f84 : 96 -> 92
```
