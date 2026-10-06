## PrivateCloudCompute.plist

> `Domain/PrivateCloudCompute.plist`

```diff

-	<key>requestCancellationV2</key>
+	<key>protectedSystemContainerEmbedded</key>

-	<key>routingKey</key>
+	<key>protectedSystemContainerMacOS</key>

-	<key>secTaskBundleIDResolution</key>
+	<key>requestCancellationV2</key>
+	<dict>
+		<key>DevelopmentPhase</key>
+		<string>FeatureComplete</string>
+	</dict>
+	<key>requestExecutionLogCompression</key>

-	<key>serverDrivenIssuerMapping</key>
+	<key>routingKey</key>

-	<key>serverDrivenIssuerMappingPreProduction</key>
+	<key>secTaskBundleIDResolution</key>

+	<key>waitlistTokens</key>
+	<dict>
+		<key>DevelopmentPhase</key>
+		<string>FeatureComplete</string>
+	</dict>

```
