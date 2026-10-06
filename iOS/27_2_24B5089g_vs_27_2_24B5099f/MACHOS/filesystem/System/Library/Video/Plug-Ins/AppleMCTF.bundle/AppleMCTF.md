## AppleMCTF

> `/System/Library/Video/Plug-Ins/AppleMCTF.bundle/AppleMCTF`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x87c38` | `0x89228` | **`+0x15f0`** |
| `__TEXT.__cstring` | `0x286c9` | `0x28d9b` | **`+0x6d2`** |
| `__TEXT.__const` | `0x229e8` | `0x22a98` | **`+0xb0`** |
| `__TEXT.__auth_stubs` | `0xd70` | `0xdc0` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x6c8` | `0x6f0` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x670` | `0x688` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x628` | `0x62c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-913.48.1.0.0
+913.63.1.0.0

-  Functions: 672
-  Symbols:   341
-  CStrings:  3444
+  Functions: 678
+  Symbols:   346
+  CStrings:  3474
Symbols:
+ _CMBlockBufferAppendBufferReference
+ _CMBlockBufferCreateEmpty
+ _CMBlockBufferCreateWithBufferReference
+ _CMBlockBufferGetDataLength
+ _CMSampleBufferCreateCopyWithNewTiming
CStrings:
+ "%lld %d AVE %s: %s::%s:%d %s | %p TokenPush null frame"
+ "%lld %d AVE %s: %s::%s:%d %s | %p TokenPush null frame\n"
+ "%lld %d AVE %s: %s::%s:%d %s | AV1 token overflow %p %d"
+ "%lld %d AVE %s: %s::%s:%d %s | AV1 token overflow %p %d\n"
+ "%lld %d AVE %s: %s::%s:%d %s | AV1 token push failed %d frame %d"
+ "%lld %d AVE %s: %s::%s:%d %s | AV1 token push failed %d frame %d\n"
+ "%lld %d AVE %s: %s::%s:%d %s | WrapAV1BlockBuffer CMSampleBufferCreate failed %d"
+ "%lld %d AVE %s: %s::%s:%d %s | WrapAV1BlockBuffer CMSampleBufferCreate failed %d\n"
+ "%lld %d AVE %s: %s::%s:%d %s | WrapAV1BlockBuffer bad size %zu"
+ "%lld %d AVE %s: %s::%s:%d %s | WrapAV1BlockBuffer bad size %zu\n"
+ "%lld %d AVE %s: %s::%s:%d %s | WrapAV1BlockBuffer null block buffer"
+ "%lld %d AVE %s: %s::%s:%d %s | WrapAV1BlockBuffer null block buffer\n"
+ "%lld %d AVE %s: AV1 reorder bundle bbuf create failed %d"
+ "%lld %d AVE %s: AV1 reorder bundle bbuf create failed %d\n"
+ "%lld %d AVE %s: AV1 reorder disengaged with %d held / %d token(s) pending; flushing at frame %d"
+ "%lld %d AVE %s: AV1 reorder disengaged with %d held / %d token(s) pending; flushing at frame %d\n"
+ "%lld %d AVE %s: AV1 reorder hold overflow, dropping frame %d"
+ "%lld %d AVE %s: AV1 reorder hold overflow, dropping frame %d\n"
+ "%lld %d AVE %s: AV1 reorder ready FIFO overflow (bundle)"
+ "%lld %d AVE %s: AV1 reorder ready FIFO overflow (bundle)\n"
+ "%lld %d AVE %s: AV1 reorder ready FIFO overflow (sfx)"
+ "%lld %d AVE %s: AV1 reorder ready FIFO overflow (sfx)\n"
+ "%lld %d AVE %s: AV1 reorder retime failed %d for frame %lld; using placeholder timing"
+ "%lld %d AVE %s: AV1 reorder retime failed %d for frame %lld; using placeholder timing\n"
+ "20:41:26"
+ "913.63.1"
+ "Sep 27 2026"
+ "TokenPush"
+ "WrapAV1BlockBuffer"
+ "bb != __null"
+ "err == noErr && sbuf != __null"
+ "iSampleSize > 0"
+ "m_iAV1TokenCount >= 0 && m_iAV1TokenCount < 32"
- "20:00:47"
- "913.48.1"
- "Sep 13 2026"
```
