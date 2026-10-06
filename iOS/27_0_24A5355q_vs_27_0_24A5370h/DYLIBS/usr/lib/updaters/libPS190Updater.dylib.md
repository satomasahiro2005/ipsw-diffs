## libPS190Updater.dylib

> `/usr/lib/updaters/libPS190Updater.dylib`

### Other Changes

```diff

-1576.0.0.0.0
+1587.0.3.0.3
Functions:
~ +[PS190IODPDevice allDevices] : 1012 -> 1008
~ -[PS190Device queryBootNonceHash] : 260 -> 264
~ -[PS190Device updateWithFile:] : 564 -> 560
~ -[PS190PacketDumper dumpDPCDRegisterRead:bytes:length:] : 168 -> 184
~ -[PS190PacketDumper dumpDPCDRegisterWrite:bytes:length:] : 184 -> 200
~ _FormatDataAsHexSimple : 184 -> 180
~ _FormatHex : 1320 -> 1344
~ -[PS190UpdaterController initializeUpdaterInstances] : 1016 -> 1004
~ -[PS190UpdaterController queryInfoAggregate] : 576 -> 572
~ -[PS190UpdaterController performUpdateWithDictionaryAggregate:firmwareFile:] : 324 -> 320
~ -[PS190UpdaterController isDone] : 272 -> 268
~ -[PS190Instance findDevice] : 336 -> 332
~ -[PS190FirmwareFile crc32ForBlocksInRange:] : 376 -> 372
~ -[PS190FirmwareFile dumpBlocksString] : 356 -> 352
~ +[PS190IICDevice allDeviceNames] : 400 -> 396
~ +[PS190IICDevice allDevices] : 392 -> 388
~ -[NSData(Utils) byteString] : 208 -> 204
```
