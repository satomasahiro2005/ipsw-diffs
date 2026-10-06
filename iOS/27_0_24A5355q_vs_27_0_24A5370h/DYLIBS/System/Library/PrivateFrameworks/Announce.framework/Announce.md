## Announce

> `/System/Library/PrivateFrameworks/Announce.framework/Announce`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3da88` | `0x3da24` | **`-0x64`** |
| `__TEXT.__objc_methlist` | `0x3208` | `0x3220` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x5600` | `0x5610` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c18` | `0x1c28` | **`+0x10`** |

### Other Changes

```diff

-327.0.0.0.0
+328.0.0.0.0
Functions:
~ -[NSArray(ANParticipant) idsIdentifiers] : 352 -> 348
~ -[NSArray(ANParticipant) rapportIDs] : 352 -> 348
~ -[NSArray(ANParticipant) messages] : 324 -> 320
~ -[ANAnnouncement description] : 1200 -> 1192
~ -[ANAnnouncement fileData] : 292 -> 288
~ -[ANAnnouncement removeAudioFileDataItems] : 336 -> 332
~ -[ANAnnouncement initWithMessage:] : 1220 -> 1216
~ -[ANAnnouncement _uuidFromUUIDs:] : 308 -> 304
~ -[NSArray(ANAnnouncements) an_unplayedAnnouncements] : 348 -> 344
~ -[NSArray(ANAnnouncements) an_playedAnnouncements] : 348 -> 344
~ -[NSArray(ANAnnouncements) an_identifiers] : 372 -> 368
~ -[HMHome(Announce_ObjC) usersIncludingCurrentUserWithAnnounceAndRemoteAccessEnabled] : 332 -> 328
~ +[ANProcessAudio _configureEngine:player:effect:sourceFile:error:] : 932 -> 928
~ -[ANAccessorySettingsCache _updateSettings:forAccessoryWithIdentifier:] : 484 -> 480
~ -[ANAccessorySettingsCache _notifySettingsDidChange:forAccessoryWithIdentifier:] : 428 -> 424
~ -[ANHomeManager homesSupportingAnnounce] : 312 -> 308
~ -[ANHomeManager _notifyManagerLoadedHomes:] : 392 -> 388
~ ___43-[ANHomeManager homeManagerDidUpdateHomes:]_block_invoke : 892 -> 888
~ ___40-[ANHomeManager homeManager:didAddHome:]_block_invoke : 552 -> 548
~ ___43-[ANHomeManager _executeBlockForDelegates:]_block_invoke : 456 -> 452
~ -[ANHomeManager(Home) homeForID:] : 348 -> 344
~ -[ANHomeManager(Home) homeWithName:] : 348 -> 344
~ -[ANHomeManager(Home) homesSupportingAnnounceFromHomes:] : 328 -> 324
~ -[ANLocation initWithMessage:] : 1180 -> 1168
~ -[ANLocation message] : 964 -> 952
~ sub_24b439a44 -> sub_24c54a9cc : 32 -> 36
~ sub_24b439c70 -> sub_24c54abfc : 172 -> 176
~ sub_24b439f60 -> sub_24c54aef0 : 1432 -> 1444
~ sub_24b43b0ec -> sub_24c54c088 : 356 -> 352
~ sub_24b43b340 -> sub_24c54c2d8 : 328 -> 332
~ sub_24b43bd64 -> sub_24c54cd00 : 1008 -> 1004
~ sub_24b442ef0 -> sub_24c553e88 : 996 -> 1020
~ sub_24b4435b4 -> sub_24c554564 : 276 -> 280
~ sub_24b443794 -> sub_24c554748 : 280 -> 276
~ sub_24b449e34 -> sub_24c55ade4 : 100 -> 96
~ sub_24b44a3c4 -> sub_24c55b370 : 604 -> 596
~ ___swift_closure_destructor.4 : 140 -> 148
~ sub_24b44ba30 -> sub_24c55c9dc : 168 -> 172
~ sub_24b44ec8c -> sub_24c55fc3c : 428 -> 424
~ sub_24b44ee38 -> sub_24c55fde4 : 428 -> 424
~ sub_24b44efe4 -> sub_24c55ff8c : 428 -> 424
~ sub_24b44f190 -> sub_24c560134 : 552 -> 544
~ sub_24b44f9fc -> sub_24c560998 : 3648 -> 3652
~ sub_24b450924 -> sub_24c5618c4 : 1604 -> 1596
~ sub_24b45597c -> sub_24c566914 : 544 -> 548
```
