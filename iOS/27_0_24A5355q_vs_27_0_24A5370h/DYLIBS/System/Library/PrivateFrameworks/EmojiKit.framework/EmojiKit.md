## EmojiKit

> `/System/Library/PrivateFrameworks/EmojiKit.framework/EmojiKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc9fc` | `0xc9c8` | **`-0x34`** |
| `__AUTH_CONST.__auth_got` | `0x380` | `0x390` | **`+0x10`** |

### Other Changes

```diff

-  Symbols:   824
+  Symbols:   826
Symbols:
+ _objc_retain_x26
+ _objc_retain_x28
Functions:
~ -[EMKRippleAnimationCoordinator cleanupIncludingFilterEffect:] : 384 -> 380
~ +[EMKTextView(TextKit2Specific) __emk_setNeedsDisplayCurrentRenderAttributesForView:] : 276 -> 272
~ -[EMKGlyphRippler generateValues] : 1256 -> 1264
~ -[EMKGlyphRippler currentColorForGlyphIndex:numberOfGlyphs:timeIndex:] : 164 -> 160
~ -[EMKGlyphRippler currentShadowColorForGlyphIndex:numberOfGlyphs:timeIndex:] : 164 -> 160
~ -[_EMKTextContainerOverlayView layoutSubviews] : 288 -> 284
~ -[_EMKTextContainerOverlayView startAnimation] : 392 -> 388
~ -[_EMKTextContainerOverlayView updateAnimationAndGetFinished:] : 400 -> 396
~ -[NSTextLayoutFragment(Helper) animatingGlyphCount_emk] : 260 -> 256
~ ___81-[NSTextLayoutManager(Helper) _enumerateTextLineFragmentsInTextRange:usingBlock:]_block_invoke : 740 -> 768
~ __EMKSetNeedsDisplaySubviewsOf : 260 -> 256
~ -[_EMKTextKit2Controller _updateEmojiAttributesOfText:] : 520 -> 516
~ -[_EMKTextLayoutFragmentView drawRect:] : 424 -> 420
~ -[_EMKTextLayoutFragmentView _drawTextLineFragment:animatingGlyphCountBefore:drawnGlyphCount:] : 460 -> 456
~ -[_EMKTextLayoutFragmentView __drawAnimatingEmojiRun:textPosition:animatingGlyphCountBefore:drawnRunGlyphCount:] : 492 -> 476
~ -[EMKLayoutManager convertGlyphIndex:toAttributeRelativeGlyphIndex:numberOfAttributedGlyphs:] : 420 -> 416
~ -[EMKLayoutManager processEditingForTextStorage:edited:range:changeInLength:invalidatedRange:] : 1028 -> 1024
~ -[EMKTextView updateEmojiDisplay:] : 400 -> 396
~ -[EMKTextView _stopTextKit1EmojiDisplayUpdateTimer:] : 292 -> 288
~ -[EMKTextView setEmojiConversionLanguagesAndActivateConversion:] : 800 -> 796
~ -[EMKTextView personalizedEmojiTokenListForList:] : 676 -> 672
```
