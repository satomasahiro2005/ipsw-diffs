## MapsIntents

> `/System/Library/ExtensionKit/Extensions/MapsIntents.appex/MapsIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5cec4` | `0x602a4` | **`+0x33e0`** |
| `__TEXT.__swift5_typeref` | `0x37b2` | `0x4120` | **`+0x96e`** |
| `__TEXT.__objc_stubs` | `0x1500` | `0x1900` | **`+0x400`** |
| `__TEXT.__oslogstring` | `0x1d2a` | `0x20bb` | **`+0x391`** |
| `__TEXT.__eh_frame` | `0x2928` | `0x2bc8` | **`+0x2a0`** |
| `__TEXT.__auth_stubs` | `0x1e50` | `0x2050` | **`+0x200`** |
| `__TEXT.__objc_methname` | `0x4c97` | `0x4e44` | **`+0x1ad`** |
| `__DATA_CONST.__const` | `0x1e88` | `0x2008` | **`+0x180`** |
| `__TEXT.__cstring` | `0x1f25` | `0x2075` | **`+0x150`** |
| `__DATA.__data` | `0x1fe8` | `0x2120` | **`+0x138`** |
| `__DATA.__objc_selrefs` | `0xe68` | `0xf68` | **`+0x100`** |
| `__DATA_CONST.__auth_got` | `0xf38` | `0x1038` | **`+0x100`** |
| `__TEXT.__swift5_fieldmd` | `0xbe8` | `0xcd0` | **`+0xe8`** |
| `__TEXT.__swift5_reflstr` | `0x1312` | `0x13eb` | **`+0xd9`** |
| `__TEXT.__unwind_info` | `0x1630` | `0x1708` | **`+0xd8`** |
| `__TEXT.__constg_swiftt` | `0x784` | `0x83c` | **`+0xb8`** |
| `__TEXT.__objc_methtype` | `0xff1` | `0x1090` | **`+0x9f`** |
| `__DATA.__bss` | `0x8640` | `0x86c0` | **`+0x80`** |
| `__TEXT.__const` | `0x51e4` | `0x5254` | **`+0x70`** |
| `__DATA_CONST.__got` | `0x668` | `0x6b8` | **`+0x50`** |
| `__DATA_CONST.__auth_ptr` | `0xa80` | `0xac0` | **`+0x40`** |
| `__TEXT.__swift5_assocty` | `0x820` | `0x838` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x158` | `0x170` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x3c` | `0x50` | **`+0x14`** |
| `__TEXT.__swift_as_cont` | `0x258` | `0x244` | **`-0x14`** |
| `__TEXT.__swift5_types` | `0xa8` | `0xb8` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0xf8` | `0x108` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0xe0` | `0xd8` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x42c` | `0x430` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`

### Other Changes

```diff

-2972.31.6.17.21
+2972.31.6.17.20

+  - /System/Library/PrivateFrameworks/Navigation.framework/Navigation

-  Functions: 1586
-  Symbols:   283
-  CStrings:  1305
+  Functions: 1624
+  Symbols:   298
+  CStrings:  1354
Symbols:
+ _GEOMapRectForMapRegion
+ _MKCoordinateForMapPoint
+ _MKMapPointsPerMeterAtLatitude
+ _MKMapRectInset
+ _MKMapRectIntersection
+ _MKMapRectNull
+ _MKMapRectUnion
+ _MKMapRectWorld
+ _OBJC_CLASS_$_GEOComposedRoute
+ _OBJC_CLASS_$_GEODirectionsService
+ _OBJC_CLASS_$_GEODirectionsServiceRequestParameters
+ _OBJC_CLASS_$_GEORouteAttributes
+ _OBJC_CLASS_$_MKMapSnapshot
+ _OBJC_CLASS_$_MNFamiliarRouteProvider
+ _OBJC_CLASS_$_UIGraphicsImageRenderer
+ _objc_retain_x1
+ _objc_retain_x25
+ _swift_bridgeObjectRetain_n
+ _swift_dynamicCastClass
+ _swift_isEscapingClosureAtFileLocation
- _OBJC_CLASS_$_GEOCommonOptions
- _OBJC_CLASS_$_GEOQuickETARequester
- _OBJC_CLASS_$_GEOTrafficAndETAResult
- _swift_retain_x28
- _swift_retain_x8
CStrings:
+ "CalculateETAIntent: %s snapshotter error: %s"
+ "CalculateETAIntent: Creating MKMapSnapshotter (%s)"
+ "CalculateETAIntent: Failed to render CurrentLocationGem to image"
+ "CalculateETAIntent: Returning route-derived ETAEntity — routeDurationInSeconds: %f, distanceMeters: %f"
+ "CalculateETAIntent: calculateETA — no routes available, returning distance-only ETAEntity"
+ "CalculateETAIntent: currentLocationInfo — missing current-location geoMapItem, treating as not current location"
+ "CalculateETAIntent: currentLocationInfo — origin=%{bool}d, destination=%{bool}d"
+ "CalculateETAIntent: currentLocationInfo — unable to fetch current location: %s"
+ "CalculateETAIntent: fetchRouteLines — MKMapService/traits unavailable, returning no routes"
+ "CalculateETAIntent: fetchRouteLines — no default route attributes for transportType=%s, returning no routes"
+ "CalculateETAIntent: fetched [%ld] route(s). hasFamiliarRoute=%{bool}d."
+ "CalculateETAIntent: generateRouteLineImageSet — adding current-location gem"
+ "CalculateETAIntent: generateRouteLineImageSet — origin is not current location, returning image set without gem"
+ "CalculateETAIntent: resolveMapImageSet — generating route-line image, routeCount=%ld"
+ "CalculateETAIntent: resolveMapImageSet — no route available, using geodesic distance image"
+ "CalculateETAIntent: resolveMapImageSet — no route lines returned, falling back to single-place image"
+ "CalculateETAIntent: route-line directions error - title: %s description: %s"
+ "CalculateETAIntent: route-line fetch failed: %s"
+ "Label indicating this ETA reflects the user's familiar/preferred route"
+ "Open Maps to continue."
+ "Route description indicating this is the user's familiar/preferred route, with traffic level"
+ "Separator between the route caption and traffic level"
+ "This operation is not supported during stepping navigation."
+ "Your preferred route"
+ "Your preferred route • %@"
+ "_setComposedRoutesForRouteLines:selectedRouteIndex:"
+ "_setShowsRouteAnnotations:"
+ "boundingMapRegion"
+ "createWaypoint(for:currentLocation:traits:)"
+ "defaultRouteAttributesForTransportType:"
+ "drawAtPoint:"
+ "drawInRect:"
+ "fetchRouteLines(from:to:transportationType:departureTime:)"
+ "geoWaypointRoute"
+ "imageWithActions:"
+ "initWithPurpose:reason:date:"
+ "initWithSize:"
+ "isFamiliarRoute"
+ "localizedDescription"
+ "localizedTitle"
+ "person.crop.badge.arrow.trianglehead.turn.up.right"
+ "pointForCoordinate:"
+ "requestRoutes:handler:"
+ "routeTrafficDetail"
+ "runSnapshotter(with:context:)"
+ "scale"
+ "setAutomobileOptions:"
+ "setCallbackQueue:"
+ "setCyclingOptions:"
+ "setFamiliarRouteProvider:"
+ "setHasTimepoint:"
+ "setIncludeRouteTrafficDetail:"
+ "setMapType:"
+ "setMaxRouteCount:"
+ "setRequestCallback:"
+ "setRequestType:"
+ "setRouteAttributes:"
+ "setTimepoint:"
+ "setTraits:"
+ "setTransitOptions:"
+ "setTransportType:"
+ "setWalkingOptions:"
+ "setWaypoints:"
+ "size"
+ "startDate"
+ "travelAndChargingDuration"
+ "v16@?0@\"GEODirectionsRequest\"8"
+ "v16@?0@\"UIGraphicsImageRendererContext\"8"
+ "v32@?0@\"NSArray\"8@\"NSError\"16@\"GEODirectionsError\"24"
- "CalculateETAIntent: Creating MKMapSnapshotter"
- "CalculateETAIntent: ETA request failed with error: %s"
- "CalculateETAIntent: ETA request returned no results"
- "CalculateETAIntent: ETA result indicates failure (no route available)"
- "CalculateETAIntent: Geodesic snapshotter error: %s"
- "CalculateETAIntent: Snapshotter error: %s"
- "CalculateETAIntent: Starting snapshotter..."
- "CalculateETAIntent: currentLocationFlags — missing current-location geoMapItem, treating as not current location"
- "CalculateETAIntent: currentLocationFlags — origin=%{bool}d, destination=%{bool}d"
- "CalculateETAIntent: currentLocationFlags — unable to fetch current location: %s"
- "Updating your route isn't supported for this type of navigation."
- "calculateETA(from:to:departureTime:resolvedTransportationType:)"
- "createWaypoint(for:traits:)"
- "expectedTimeOfDeparture"
- "generateGeodesicDistanceImageSet(from:to:layout:)"
- "generateMapImageSet(for:layout:)"
- "isSuccess"
- "requestETAFromOrigin:toDestinations:transportType:timepoint:includeDistance:commonOptions:automobileOptions:walkingOptions:transitOptions:cyclingOptions:familiarRoute:auditToken:handler:callbackQueue:"
- "seconds"
- "setIncludeSummaryForPredictedDestination:"
```
