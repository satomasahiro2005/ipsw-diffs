## CertInfo

> `/System/Library/PrivateFrameworks/CertInfo.framework/CertInfo`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf2c8` | `0xf284` | **`-0x44`** |

### Other Changes

```diff

-2054.0.0.0.0
+2055.0.0.0.0
Functions:
~ -[CertInfoTrustDetailsView _appendRemainingCertificates] : 288 -> 284
~ -[CertInfoTrustDetailsView initWithFrame:trustProperties:] : 580 -> 576
~ ___44-[NSData(CertInfoAdditions) CertUIHexString]_block_invoke : 144 -> 140
~ -[CertInfoCertificateDetailsView _cellInfosForSection:] : 596 -> 592
~ -[CertInfoCertificateDetailsView _sectionsFromProperties:] : 556 -> 552
~ -[CertInfoCertificateDetailsController _sectionsForProperties:currentSectionDictionary:] : 816 -> 804
~ -[CertUIItemDetailsSummaryCell layoutSubviews] : 424 -> 420
~ -[CertUIItemDetailsSummaryCell sizeThatFits:] : 388 -> 384
~ -[CertUIItemDetailsSummaryCell setDetailLabelOriginX:] : 300 -> 296
~ -[CertUIItemDetailsSummaryCell createViewWithDescriptors:] : 564 -> 560
~ -[CertUIItemDetailsSummaryCell createViewWithItemDetailArray:] : 608 -> 600
~ -[CertUICertificatePropertiesInfo _setup:] : 732 -> 728
~ -[CertUICertificatePropertiesInfo _cellInfosForSection:] : 640 -> 636
~ -[CertUICertificatePropertiesInfo _sectionsFromProperties:] : 556 -> 552
~ -[CertUICertificatePropertiesInfo _sendablePropertiesFromProperties:] : 340 -> 336
~ -[CertUICertificatePropertiesInfo _sendablePropertiesFromTrust:] : 340 -> 336
~ -[CertInfoDescriptionCellContentView drawRect:] : 544 -> 552
```
