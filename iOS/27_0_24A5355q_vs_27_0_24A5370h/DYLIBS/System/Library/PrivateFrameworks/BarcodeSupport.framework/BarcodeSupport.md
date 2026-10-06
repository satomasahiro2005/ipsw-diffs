## BarcodeSupport

> `/System/Library/PrivateFrameworks/BarcodeSupport.framework/BarcodeSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__ustring` | `0xea` | `0x198` | **`+0xae`** |
| `__TEXT.__cstring` | `0x4449` | `0x43e9` | **`-0x60`** |
| `__TEXT.__text` | `0x34890` | `0x3487c` | **`-0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b18` | `0x1b20` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x11c0` | `0x11c8` | **`+0x8`** |

### Other Changes

```diff

-1038.6.0.0.0
+1038.7.0.0.0
Functions:
~ -[BCSAction preferItemsInSubmenu] : 308 -> 304
~ -[BCSAction menuElements] : 840 -> 836
~ -[BCSActionPickerViewAssistant showActionPickerWithItems:fromViewController:presentingRect:] : 1156 -> 1152
~ -[BCSNFCReader _readTag:] : 1232 -> 1228
~ +[BCSCalendarEventParser _validatedICSString:] : 636 -> 632
~ -[CIImage(BCSCIImageExtras) _bcs_stringValueIfQRCode] : 572 -> 568
~ -[BCSDataDetectorsSupportedAction actionPickerItems] : 368 -> 364
~ -[BCSDataDetectorsSupportedAction _actionStringsArray] : 328 -> 324
~ -[BCSDataDetectorsSupportedAction preferItemsInSubmenu] : 356 -> 352
~ -[BCSNotification _supplementActions] : 444 -> 440
~ -[BCSNotification _orderAppLinkActionsByRecency:] : 504 -> 500
~ -[BCSNotificationManager _notificationWithIdentifier:] : 336 -> 332
~ -[BCSNotificationManager withdrawNotificationsWithProcessID:codeType:] : 556 -> 548
~ -[NSString(BCSNSStringExtras) _bcs_looksLikeEmailAddress] : 152 -> 212
~ +[BCSParser parseString:] : 528 -> 524
~ -[BCSQRCodeParser _qrCodeFeatureFromImage:] : 712 -> 708
~ -[BCSURLAction _actionPickerItemsForUnlockedAppLinks] : 584 -> 580
~ -[BCSURLAction actionPickerItems] : 1060 -> 1056
~ -[BCSURLAction _queryApplicationRecordForURL:completionHandler:] : 1564 -> 1560
~ -[BCSContinuityCameraAction performDefaultActionWithCompletionHandler:] : 1504 -> 1500
CStrings:
+ "Add Verification Code in “%@”"
+ "Add Verification Codes in “%@”"
+ "Open “%@”"
+ "Open “%@” in %@"
+ "airplayPayload"
- "Add Verification Code in \"%@\""
- "Add Verification Codes in \"%@\""
- "Open \"%@\""
- "Open \"%@\" in %@"
- "airplayPlayload"
```
