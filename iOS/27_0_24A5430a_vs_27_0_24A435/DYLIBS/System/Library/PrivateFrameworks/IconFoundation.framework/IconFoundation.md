## IconFoundation

> `/System/Library/PrivateFrameworks/IconFoundation.framework/IconFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x39ad0` | `0x39ba4` | **`+0xd4`** |
| `__TEXT.__cstring` | `0x12ce1` | `0x12d0e` | **`+0x2d`** |
| `__DATA_CONST.__const` | `0x7550` | `0x7568` | **`+0x18`** |

### Other Changes

```diff

-  CStrings:  2890
+  CStrings:  2892
Functions:
~ -[CUIPlaceholderCUINamedRenditionInfo attributePresent:withValue:] : 1544 -> 1564
~ -[CUIPlaceholderCUINamedRenditionInfo setAttributePresent:withValue:] : 1540 -> 1560
~ -[CUIPlaceholderCUINamedRenditionInfo clearAttributePresent:withValue:] : 1540 -> 1560
~ -[CUIPlaceholderCUINamedRenditionInfo decrementValue:forAttribute:] : 3080 -> 3120
~ -[CUIPlaceholderCUINamedRenditionInfo incrementIndex:inValues:forAttribute:] : 3152 -> 3192
~ +[CUIPlaceholderCUINamedRenditionInfo subtypeToIndexWithPlatform:andInput:] : 1268 -> 1288
~ _CUIValidateIdiomSubtypes : 640 -> 644
~ _CUIRenditionKeySetValueForAttribute : 308 -> 316
~ _CUIRenditionKeyTokenCount : 44 -> 48
~ _CUIRenditionKeyTokenIsBaseKeyOfKeyList : 208 -> 216
~ -[CUIPlaceholderCUIThemeRendition _initializeCompositingOptionsFromCSIData:version:] : 172 -> 176
~ -[CUIPlaceholderCUIThemeRendition _initalizeMetadataFromCSIData:version:] : 212 -> 216
~ -[CUIPlaceholderCUIThemeRendition _initializePropertiesFromCSIData:version:] : 388 -> 392
~ -[CUIPlaceholder_CUIThemeMultisizeImageSetRendition _initWithCSIHeader:version:] : 440 -> 444
~ __ExpandBlockTable : 228 -> 232
~ __dense_addFreeRange : 252 -> 256
~ __findRemove : 1784 -> 1788
CStrings:
+ "APPLE11"
+ "kCoreThemeFeatureSetMetalGPUFamily11"
```
