## QuickLook

> `/System/Library/Frameworks/QuickLook.framework/QuickLook`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xddff8` | `0xdddb4` | **`-0x244`** |
| `__TEXT.__cstring` | `0x54b4` | `0x5354` | **`-0x160`** |
| `__TEXT.__eh_frame` | `0x4a34` | `0x49ac` | **`-0x88`** |
| `__DATA.__bss` | `0x3528` | `0x34a8` | **`-0x80`** |
| `__AUTH_CONST.__const` | `0x39c0` | `0x3958` | **`-0x68`** |
| `__TEXT.__const` | `0x3b34` | `0x3b94` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x1d08` | `0x1d4a` | **`+0x42`** |
| `__AUTH_CONST.__auth_got` | `0x1508` | `0x1548` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0xb864` | `0xb894` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x11b90` | `0x11bb0` | **`+0x20`** |
| `__DATA.__common` | `0x80` | `0xa0` | **`+0x20`** |
| `__DATA.__data` | `0x3460` | `0x3480` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x74a0` | `0x74b8` | **`+0x18`** |
| `__AUTH.__data` | `0x1680` | `0x1670` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xb58` | `0xb4c` | **`-0xc`** |
| `__TEXT.__swift5_assocty` | `0x360` | `0x368` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x19c` | `0x198` | **`-0x4`** |
| `__TEXT.__swift_as_cont` | `0x4f0` | `0x4ec` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x1e8` | `0x1e4` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-1032.0.0.0.0
+1034.0.0.0.0

-  - /System/Library/Frameworks/CoreTransferable.framework/CoreTransferable

-  Functions: 5736
-  Symbols:   7540
-  CStrings:  915
+  Functions: 5745
+  Symbols:   7549
+  CStrings:  904
Symbols:
+ -[QLPreviewController(Overlay) _prefersBottomToolbarOverVerticalBarForTraitCollection:]
+ -[QLPreviewController(Overlay) _updateVerticalBarAllowanceForTraitCollection:]
+ _associated conformance 9QuickLook16QLDocumentEntityV10AppIntents04FileD0AaD0eD0
+ _associated conformance 9QuickLook23ResolveQLDocumentIntentV10AppIntents0fE0AA13PerformResultAdEP_AD0eI0
+ _associated conformance 9QuickLook23ResolveQLDocumentIntentV10AppIntents0fE0AA14SummaryContentAdEP_AD09ParameterH0
+ _associated conformance 9QuickLook23ResolveQLDocumentIntentV10AppIntents0fE0AaD09_SupportsF12Dependencies
+ _associated conformance 9QuickLook23ResolveQLDocumentIntentV10AppIntents0fE0AaD24PersistentlyIdentifiable
+ _get_witness_table 10AppIntents21IntentResultContainerVys5NeverOA3EGAA0cD0HPyHC
+ _symbolic $s10AppIntents0A6IntentP
+ _symbolic _____ 9QuickLook23ResolveQLDocumentIntentV
+ _symbolic _____Sg 10AppIntents12IntentDialogV
+ _symbolic _____Sg 10Foundation23LocalizedStringResourceV
+ _symbolic _____Sg 9QuickLook16QLDocumentEntityV
+ _symbolic _____y_____A3BG 10AppIntents21IntentResultContainerV s5NeverO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 22UniformTypeIdentifiers6UTTypeV
+ _symbolic _____y_____SgG 10AppIntents15IntentParameterC 9QuickLook16QLDocumentEntityV
+ _symbolic _____y______Qo_ 10AppIntents0A6IntentPAAE16parameterSummaryQrvpZQO 9QuickLook017ResolveQLDocumentC0V
+ _type_layout_string 9QuickLook23ResolveQLDocumentIntentV
- _NSPaperSizeDocumentAttribute
- _associated conformance 9QuickLook16QLDocumentEntityV16CoreTransferable0F0AA14RepresentationAdEP_AD08TransferG0
- _associated conformance 9QuickLook16QLDocumentEntityV5ErrorOSHAASQ
- _get_witness_table 16CoreTransferable18FileRepresentationVy9QuickLook16QLDocumentEntityVGAA08TransferD0HPyHC
- _symbolic $s16CoreTransferable0B0P
- _symbolic _____ 9QuickLook16QLDocumentEntityV5ErrorO
- _symbolic _____y_____G 16CoreTransferable18FileRepresentationV 9QuickLook16QLDocumentEntityV
- _symbolic _____y_____G s23_ContiguousArrayStorageC 10AppIntents13_IntentTargetV
- _symbolic _____y_____SgG 10AppIntents14EntityPropertyC 10Foundation3URLV
CStrings:
+ "Resolve Document"
- "com.apple.MobileCBP"
- "com.apple.MobileSMS"
- "com.apple.Passbook"
- "com.apple.TapToRadar"
- "com.apple.freeform"
- "com.apple.mobilemail"
- "com.apple.mobilenotes"
- "com.apple.mobilesafari"
- "com.apple.mobileslideshow"
- "com.apple.preview"
- "com.apple.reminders"
- "com.apple.shortcuts"
```
