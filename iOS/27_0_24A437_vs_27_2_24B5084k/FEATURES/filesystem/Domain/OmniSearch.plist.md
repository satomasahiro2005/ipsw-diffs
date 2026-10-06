## OmniSearch.plist

> `Domain/OmniSearch.plist`

```diff

-	<key>HybridLocalSearchService</key>
+	<key>ConversationMemory</key>

-	<key>MessagesSearchService</key>
+	<key>HomeKitSearchService</key>

-	<key>ResolveAllAnswersToPlaceDescriptors</key>
+	<key>HybridLocalSearchService</key>

-	<key>SkipPegasusForPlaceDescriptorResolution</key>
+	<key>MessagesSearchService</key>

-	<key>SoftAndHardFilterHeuristic</key>
+	<key>ResolveAllAnswersToPlaceDescriptors</key>
+	<dict>
+		<key>DevelopmentPhase</key>
+		<string>FeatureComplete</string>
+	</dict>
+	<key>SkipPegasusForPlaceDescriptorResolution</key>

```
