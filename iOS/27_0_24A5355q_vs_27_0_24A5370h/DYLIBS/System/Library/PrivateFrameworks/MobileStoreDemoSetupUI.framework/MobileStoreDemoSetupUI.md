## MobileStoreDemoSetupUI

> `/System/Library/PrivateFrameworks/MobileStoreDemoSetupUI.framework/MobileStoreDemoSetupUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f6f8` | `0x1f6c0` | **`-0x38`** |

### Other Changes

```diff

-1865.0.0.0.0
+1871.0.14.0.0
Functions:
~ -[NSString(AluminiumAuthenticator) _dataUsingHexEncoding] : 872 -> 880
~ -[AluminiumAuthenticator addAuthenticationHeadersToRequest:includedHeaders:body:algorithm:error:] : 1992 -> 1988
~ -[AluminiumAuthenticator verifyAuthenticationWithRequest:includedHeaders:algorithm:error:] : 2208 -> 2216
~ -[MSDBAAInterface serializeCertificateChain:] : 364 -> 360
~ -[MSDBAAInterface printAllKeys:] : 832 -> 824
~ -[NSDictionary(xpcdictConv) createXPCDictionary] : 1092 -> 1088
~ -[MSDPlatform isValidProductList:] : 560 -> 556
~ -[MSDLanguageAndRegionHelper _preferredLocalizedLanguageCodeFromArray:] : 428 -> 424
~ -[MKClusterAnnotation(MSDSetupUI) isSameCoordinate] : 432 -> 428
~ -[MSDMapViewController deselectAnnotation] : 348 -> 344
~ -[MSDMapViewController annotateStores:] : 356 -> 352
~ -[MSDMapViewController mapView:didSelectAnnotationView:] : 876 -> 872
~ -[MSDMapViewController mapView:didDeselectAnnotationView:] : 832 -> 828
~ -[MSDMapViewController _zoomToAnnotation] : 408 -> 404
~ -[MSDMapViewController _getAnnotationWithStoreInfo:] : 432 -> 428
~ -[MSDContactsViewController init] : 448 -> 444
~ -[MSDContactsViewController initWithContactsModel:] : 448 -> 444
~ -[MSDStoreContactsModel sortContacts:] : 800 -> 796
~ ___53-[MSDStoreSearchViewController _searchStoreWithText:]_block_invoke : 372 -> 368
```
