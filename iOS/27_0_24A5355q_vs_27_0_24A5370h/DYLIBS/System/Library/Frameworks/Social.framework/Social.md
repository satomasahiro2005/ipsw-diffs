## Social

> `/System/Library/Frameworks/Social.framework/Social`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3e944` | `0x3e854` | **`-0xf0`** |

### Other Changes

```text
Functions:
~ -[SLRequest setMultiPartBoundary:] : 284 -> 280
~ -[SLRequest multiPartBodyData] : 780 -> 772
~ -[SLRequest completeMultiParts] : 436 -> 432
~ -[SLRequest _parameterString] : 828 -> 824
~ +[SLSystemConfigManager sharedInstanceForCallbackWhileLocked:] : 288 -> 284
~ +[SLGoogleOAuth2TokenRequest _urlRequestForParams:tokenURL:] : 728 -> 724
~ +[SLYahooWebAuthRequest clearCookiesFromStorage:authRequestURL:] : 388 -> 384
~ __SLServiceChineseKeyboardInstalled : 336 -> 332
~ -[SLLegacyGooglePlusUserInfoResponse _populateDataFromResponseDictionary:] : 768 -> 764
~ -[SLBatchRequest preparedURLRequest] : 740 -> 736
~ -[SLAOLWebClient clientSecret] : 268 -> 272
~ +[SLComposeViewController _serviceTypeForExtensionIdentifier:] : 364 -> 360
~ -[SLComposeViewController removeAllImages] : 436 -> 432
~ -[SLComposeViewController removeAllURLs] : 764 -> 760
~ -[SLSheetPlaceViewController _regionForPlaces:] : 1180 -> 1176
~ ___65-[SLSheetPlaceViewController _forceSelectPlace:setMapAnnotation:]_block_invoke : 584 -> 580
~ -[SLSheetPlaceViewController tableView:didSelectRowAtIndexPath:] : 776 -> 772
~ -[SLPlace encodeWithCoder:] : 312 -> 308
~ -[SLGoogleUserInfoResponse _populateDataFromResponseDictionary:] : 1036 -> 1028
~ +[NSDictionary(SocialAdditions) SLDictionaryWithOAuthAccessTokenResponseData:] : 472 -> 468
~ +[SLGoogleLegacyTokenMigrationRequest urlRequestForAuthTokenFromLegacyClientToken:username:password:] : 848 -> 844
~ -[SLGoogleLegacyTokenMigrationTokenResponse initWithData:urlResponse:error:] : 424 -> 420
~ -[SLGoogleLegacyTokenMigrationCodeResponse initWithData:urlResponse:error:] : 572 -> 568
~ -[SLDataMigrationController removeAncillarySocialDatabaseFilesWithPrefix:serviceNameForLogging:] : 492 -> 488
~ -[NSString(SLTwitterStringAdditions) SLTwitterCharacterCountWithShortenedURLLength:] : 616 -> 612
~ -[SLMicroBlogComposeViewController _beginLoadingAccountProfileImages] : 664 -> 660
~ ___62-[SLMicroBlogComposeViewController setMicroBlogSheetDelegate:]_block_invoke_2 : 656 -> 652
~ -[SLMicroBlogComposeViewController isContentValid] : 648 -> 644
~ -[SLMicroBlogComposeViewController completeText:withAttachments:] : 460 -> 456
~ -[SLMicroBlogComposeViewController characterCountForEnteredText:attachments:] : 368 -> 364
~ -[SLMicroBlogComposeViewController didSelectPost] : 636 -> 632
~ -[SLSheetRootViewController resetConfigurationItems] : 280 -> 276
~ -[SLSheetRootViewController observeConfigurationItems:] : 260 -> 256
~ -[SLMicroBlogAccountsTableViewController tableView:didSelectRowAtIndexPath:] : 556 -> 552
~ -[SLSheetPhotoAlbumImageView initWithPrincipalAttachments:] : 1232 -> 1228
~ +[SLRemoteServicePlistLoader loadRemoteServicesFromPlistResourceName:inBundle:] : 520 -> 516
~ +[SLGoogleWebAuthRequest clearCookiesFromStorage:authRequestURL:] : 344 -> 340
~ -[NSArray(SLSocialNSArrayAdditions) countObjectsPassingTest:] : 292 -> 288
~ -[NSArray(SLSocialNSArrayAdditions) firstObjectPassingTest:] : 312 -> 308
~ -[NSArray(SLSocialNSArrayAdditions) objectsPassingTest:] : 336 -> 332
~ -[SLRequestBodyInputStream initWithMultiParts:multiPartBoundary:] : 880 -> 872
~ -[SLWebAuthFlowController shouldHideWebViewForLoadWithRequest:] : 732 -> 728
~ -[SLAttachment encodeWithCoder:] : 392 -> 388
~ +[SLFacebookAlbum albumsWithAlbumDataDictionaries:] : 336 -> 332
~ -[SLServiceListener _verifyAuthorizationForConnection:] : 336 -> 332
~ -[SLManagedObject encodeWithCoder:] : 356 -> 352
~ -[SLYahooWebClient clientSecret] : 268 -> 272
~ -[NSArray(SLSocialNSArrayAdditions) countObjectsPassingTest:] : 292 -> 288
~ -[NSArray(SLSocialNSArrayAdditions) firstObjectPassingTest:] : 312 -> 308
~ -[NSArray(SLSocialNSArrayAdditions) objectsPassingTest:] : 336 -> 332
~ -[SLComposeServiceViewController _areAttachmentsReady] : 312 -> 308
~ -[SLComposeServiceViewController _previewDisplayFormat] : 300 -> 296
~ -[SLComposeServiceViewController loadPreviewView] : 1668 -> 1664
~ -[SLComposeServiceViewController _convertExtensionItemProvidersToAttachments:] : 796 -> 792
~ -[SLRemoteSessionProxy _remoteSessionConnectionWasInterrupted] : 528 -> 524
~ -[SLRemoteService infoDictHasRequiredKeys:] : 476 -> 472
~ -[SLRemoteService encodeWithCoder:] : 688 -> 684
~ -[SLRemoteService initWithCoder:] : 1028 -> 1024
~ +[SLRemoteService _cachedServiceWithType:] : 348 -> 344
~ +[ACAccountStore(SLUtilities) SLDuplicateAccountExistsForAccount:withTypeIdentifier:andAccountPropertyIDKey:] : 532 -> 528
~ +[SLYahooWebOAuth2TokenRequest _urlRequestForParams:clientID:secret:tokenURL:] : 936 -> 932
```
