# GoogleMap

https://developers.google.com/maps/documentation/ios-sdk/start

1) install sdk
2) get key
3) add in appdelegate
4) general->linked framework and libraries (add frameworks)
Open the Build Phases tab, and within Link Binary with Libraries, add the frameworks:

5) open the Build Settings tab. In the Other Linker Flags section, add -ObjC. 
6) info.plist
	1)Privacy - Location When In Use Usage Description 
	2)<key>LSApplicationQueriesSchemes</key>
<array>
    <string>googlechromes</string>
    <string>comgooglemaps</string>
</array>

	•	AT route draw time add 
		<key>NSAppTransportSecurity</key>
		<dict>
		  <key>NSAllowsArbitraryLoads</key>
		      <true/>
	</dict>
	
