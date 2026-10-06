## 🔑 Entitlements

### filesystem

### CheckerBoard

> `/Applications/CheckerBoard.app/CheckerBoard`

```diff

+	<key>com.apple.aop.hid-driver.user-client</key>
+	<dict>
+		<key>orientation_1</key>
+		<dict>
+			<key>send-command</key>
+			<dict/>
+		</dict>
+	</dict>

-	<key>com.apple.private.diagnosticscheckupd.launch</key>
-	<true/>

-	<key>com.apple.runningboard.assertions.frontboard</key>
-	<true/>

+		<string>AppleSPUHIDDriverUserClient</string>

+	<key>com.apple.springboard.display-region-blanking</key>
+	<true/>

```
### Diagnostic-4009

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-4009.appex/Diagnostic-4009`

```diff

+		<string>AppleCameraUserClient</string>

+		<string>com.apple.cameraispd</string>

```

### 🆕 Diagnostic-6023

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-6023.appex/Diagnostic-6023`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.DiagnosticsKit.extension</key>
	<true/>
	<key>com.apple.private.applemesa.allow</key>
	<true/>
	<key>com.apple.security.exception.iokit-user-client-class</key>
	<array>
		<string>AppleBiometricServicesUserClient</string>
	</array>
</dict>
</plist>

```

### 🆕 Diagnostic-6024

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-6024.appex/Diagnostic-6024`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.DiagnosticsKit.extension</key>
	<true/>
	<key>com.apple.aop.hid-driver.user-client</key>
	<dict>
		<key>orientation_1</key>
		<dict>
			<key>send-command</key>
			<dict/>
		</dict>
	</dict>
	<key>com.apple.private.hid.client.event-filter</key>
	<true/>
	<key>com.apple.private.hid.client.event-monitor</key>
	<true/>
	<key>com.apple.security.exception.files.absolute-path.read-write</key>
	<array>
		<string>com.apple.CoreMotion</string>
	</array>
	<key>com.apple.security.exception.iokit-user-client-class</key>
	<array>
		<string>AppleSPUHIDDriverUserClient</string>
	</array>
	<key>com.apple.system.diagnostics.iokit-properties</key>
	<true/>
</dict>
</plist>

```

### 🆕 Diagnostic-6025

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-6025.appex/Diagnostic-6025`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.DiagnosticsKit.extension</key>
	<true/>
	<key>com.apple.private.mobilerepair.shipmode</key>
	<true/>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.mobilerepair.shipmode</string>
	</array>
</dict>
</plist>

```
### SystemReport

> `/Applications/DiagnosticsService.app/PlugIns/SystemReport.appex/SystemReport`

```diff

+	<key>com.apple.private.iokit.battery-shipping-charge-limit</key>
+	<true/>

```
### ServicesPaymentAngel

> `/Applications/ServicesPaymentAngel.app/ServicesPaymentAngel`

```diff

+	<key>com.apple.cdp.followup</key>
+	<true/>
+	<key>com.apple.cdp.recovery</key>
+	<true/>
+	<key>com.apple.cdp.recoverykey</key>
+	<true/>
+	<key>com.apple.cdp.statemachine</key>
+	<true/>
+	<key>com.apple.cdp.telemetry</key>
+	<true/>
+	<key>com.apple.cdp.utility</key>
+	<true/>
+	<key>com.apple.cdp.walrus</key>
+	<true/>
+	<key>com.apple.cdp.walrus.pcskeys</key>
+	<true/>

+	<key>com.apple.keystore.device</key>
+	<true/>

+	<key>com.apple.mkb.usersession.keybagopaquedata</key>
+	<true/>

+		<string>kTCCServiceAddressBook</string>

+		<string>com.apple.aa.identity.xpc</string>
+		<string>com.apple.cdp.daemon</string>
+		<string>com.apple.hsa-authentication-server</string>
+		<string>com.apple.icloud.findmydeviced</string>
+		<string>com.apple.identityservicesd.embedded.auth</string>

+		<string>com.apple.mobile.keybagd.xpc</string>
+		<string>com.apple.mobile.usermanagerd.xpc</string>

```

### 🆕 t8140.RELEASE.restore.stripped.sharedcache

> `/System/ExclaveCore/usr/share/exclavecore_sharedcache/t8140.RELEASE.restore.stripped.sharedcache`

- No entitlements *(yet)*

### 🆕 t8140.RELEASE.stripped.sharedcache

> `/System/ExclaveCore/usr/share/exclavecore_sharedcache/t8140.RELEASE.stripped.sharedcache`

- No entitlements *(yet)*
### AccessibilityUIServer

> `/System/Library/CoreServices/AccessibilityUIServer.app/AccessibilityUIServer`

```diff

+		<string>com.apple.relevanced.AudioUnderstanding</string>

```

### 🆕 MobileDevices-0001

> `/System/Library/CoreServices/CoreTypes.bundle/Contents/Library/MobileDevices-0001.bundle/MobileDevices-0001`

- No entitlements *(yet)*

### 🆕 MobileDevices-0003

> `/System/Library/CoreServices/CoreTypes.bundle/Contents/Library/MobileDevices-0003.bundle/MobileDevices-0003`

- No entitlements *(yet)*

### 🆕 AMSNearFieldExtension

> `/System/Library/ExtensionKit/Extensions/AMSNearFieldExtension.appex/AMSNearFieldExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>adi-client</key>
	<string>409835401</string>
	<key>application-identifier</key>
	<string>com.apple.AppleMediaServicesUI.AMSNearFieldExtension</string>
	<key>aps-connection-initiate</key>
	<true/>
	<key>com.apple.UIKit.vends-view-services</key>
	<true/>
	<key>com.apple.ak.auth.xpc</key>
	<true/>
	<key>com.apple.application-identifier</key>
	<string>com.apple.AppleMediaServicesUI.AMSNearFieldExtension</string>
	<key>com.apple.authkit.client.internal</key>
	<true/>
	<key>com.apple.cards.all-access</key>
	<true/>
	<key>com.apple.internal.nfc.allow.backgrounded.session</key>
	<true/>
	<key>com.apple.internal.seserviced.ptattestation</key>
	<true/>
	<key>com.apple.keystore.device</key>
	<true/>
	<key>com.apple.managedconfiguration.profiled-access</key>
	<true/>
	<key>com.apple.mobileactivationd.spi</key>
	<true/>
	<key>com.apple.nfcd.assertion.handover</key>
	<true/>
	<key>com.apple.nfcd.assertion.tagreading</key>
	<true/>
	<key>com.apple.nfcd.background.tag.reading.extension.urls</key>
	<array>
		<string>https://giftcard.apple.com</string>
		<string>https://gc.apple.com</string>
	</array>
	<key>com.apple.nfcd.hwmanager</key>
	<true/>
	<key>com.apple.nfcd.session.reader.internal</key>
	<true/>
	<key>com.apple.nfcd.session.se</key>
	<true/>
	<key>com.apple.payment.all-access</key>
	<true/>
	<key>com.apple.payment.card-on-file</key>
	<true/>
	<key>com.apple.private.CoreAuthentication.SPI</key>
	<true/>
	<key>com.apple.private.MobileGestalt.AllowedProtectedKeys</key>
	<array>
		<string>SerialNumber</string>
		<string>UniqueDeviceID</string>
	</array>
	<key>com.apple.private.accounts.allaccounts</key>
	<true/>
	<key>com.apple.private.applemediaservices</key>
	<true/>
	<key>com.apple.private.appstored</key>
	<array>
		<string>Install</string>
		<string>Queue</string>
		<string>Library</string>
		<string>Purchase</string>
	</array>
	<key>com.apple.private.biometrickit.allow-connect</key>
	<true/>
	<key>com.apple.private.biometrickit.allow-default</key>
	<true/>
	<key>com.apple.private.fairplay.FPDI</key>
	<dict>
		<key>capabilities</key>
		<array>
			<integer>4014732562</integer>
		</array>
		<key>client-identifier</key>
		<string>com.apple.AppleMediaServicesUI.AMSNearFieldExtension</string>
	</dict>
	<key>com.apple.private.tcc.allow</key>
	<array>
		<string>kTCCServiceFaceID</string>
	</array>
	<key>com.apple.security.app-sandbox</key>
	<true/>
	<key>com.apple.security.attestation.access</key>
	<true/>
	<key>com.apple.security.exception.files.home-relative-path.read-write</key>
	<array>
		<string>/Library/Caches/com.apple.AppleMediaServices/</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.xpc.amsaccountsd</string>
		<string>com.apple.appstored.xpc</string>
		<string>com.apple.xpc.amstoold</string>
		<string>com.apple.fairplaydeviceidentityd</string>
		<string>com.apple.nfcd.hwmanager</string>
		<string>com.apple.seserviced</string>
		<string>com.apple.passd.payment</string>
		<string>com.apple.passd.account</string>
		<string>com.apple.passd.library</string>
		<string>com.apple.passd.in-app-payment</string>
		<string>com.apple.mobile.keybagd.xpc</string>
	</array>
	<key>com.apple.security.network.client</key>
	<true/>
	<key>com.apple.seserviced.key</key>
	<true/>
	<key>com.apple.seserviced.kmlXpcService</key>
	<true/>
	<key>com.apple.springboard.opensensitiveurl</key>
	<true/>
	<key>fairplay-client</key>
	<string>1445028844</string>
	<key>keychain-access-groups</key>
	<array>
		<string>apple</string>
	</array>
</dict>
</plist>

```

### 🆕 NTKHermes2026FaceBundle

> `/System/Library/NanoTimeKit/FaceBundles/NTKHermes2026FaceBundle.bundle/NTKHermes2026FaceBundle`

- No entitlements *(yet)*

### 🆕 NTKHero27FaceBundle

> `/System/Library/NanoTimeKit/FaceBundles/NTKHero27FaceBundle.bundle/NTKHero27FaceBundle`

- No entitlements *(yet)*
### heard

> `/System/Library/PrivateFrameworks/HearingCore.framework/heard`

```diff

+		<string>com.apple.relevanced.AudioUnderstanding</string>

```
### callservicesd

> `/System/Library/PrivateFrameworks/TelephonyUtilities.framework/callservicesd`

```diff

+	<key>com.apple.developer.icloud-container-identifiers</key>
+	<array>
+		<string>com.apple.facetime</string>
+	</array>
+	<key>com.apple.developer.icloud-services</key>
+	<array>
+		<string>CloudDocuments</string>
+	</array>

+	<key>com.apple.developer.ubiquity-container-identifiers</key>
+	<array>
+		<string>com.apple.facetime</string>
+	</array>

+	<key>com.apple.private.clouddocs.auto-accept-share</key>
+	<true/>
+	<key>com.apple.private.clouddocs.sharing.private-interface</key>
+	<true/>

+		<string>com.apple.private.alloy.gftaastest.communication</string>

+		<string>com.apple.private.alloy.gftaastest.communication</string>

+		<string>com.apple.private.alloy.gftaastest.communication</string>

+		<string>com.apple.private.alloy.gftaastest.communication</string>

+		<string>com.apple.private.alloy.gftaastest.communication</string>

+		<string>com.apple.private.alloy.gftaastest.communication</string>

+	<key>com.apple.private.librarian.container-proxy</key>
+	<true/>

+	<key>com.apple.private.security.storage.MobileDocuments</key>
+	<true/>

```
### nfcd

> `/usr/libexec/nfcd`

```diff

+	<key>com.apple.security.exception.files.absolute-path.read-only</key>
+	<array>
+		<string>/usr/standalone/firmware/nfrestore/firmware/fw-hashes/SN450V-hashes.plist</string>
+		<string>/usr/standalone/firmware/nfrestore/firmware/fury-fw-hashes/PN800V-hashes.plist</string>
+	</array>

-		<string>AppleSMCSensorDispatcherUserClient</string>

+		<string>com.apple.stockholm.services.NFReportingService</string>

+		<string>com.apple.timed.xpc</string>
+		<string>com.apple.seserviced.presentment-authorization</string>

+	<key>com.apple.seserviced.presentment-authorization</key>
+	<true/>

+	<key>com.apple.timed</key>
+	<true/>

```
### proximitycontrold

> `/usr/libexec/proximitycontrold`

```diff

+	<key>com.apple.aop.hid-driver.user-client</key>
+	<dict>
+		<key>orientation_1</key>
+		<dict>
+			<key>send-command</key>
+			<dict/>
+		</dict>
+	</dict>

```


