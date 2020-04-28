
# Intune Device Tokens

# User Tokens

{{userprincipalname}}—for example, John@contoso.com

{{mail}}—for example, John@contoso.com

{{partialupn}}—for example, John

{{accountid}}—for example, fc0dc142-71d8-4b12-bbea-bae2a8514c81

{{userid}}—for example, 3ec2c00f-b125-4519-acf0-302ac3761822

{{username}}—for example, John Doe

## Device Tokens

{{deviceid}}—for example, b9841cd9-9843-405f-be28-b2265c59ef97

{{serialnumber}}—for example, F4KN99ZUG5V2 (for iOS/iPadOS devices)

{{serialnumberlast4digits}}—for example, G5V2 (for iOS/iPadOS devices)

{{aaddeviceid}}—for example, ab0dc123-45d6-7e89-aabb-cde0a1234b56

{{udidlast4digits}} - last 4 of UDID

{{udid}} - device UDID

{{aaddeviceid}} - Azure Device ID

## XML Definitions

```xml
<dict>
  <key>userprincipalname</key>
  <string>{{userprincipalname}}</string>
  <key>mail</key>
  <string>{{mail}}</string>
  <key>partialupn</key>
  <string>{{partialupn}}</string>
  <key>accountid</key>
  <string>{{accountid}}</string>
  <key>deviceid</key>
  <string>{{deviceid}}</string>
  <key>userid</key>
  <string>{{userid}}</string>
  <key>username</key>
  <string>{{username}}</string>
  <key>serialnumber</key>
  <string>{{serialnumber}}</string>
  <key>serialnumberlast4digits</key>
  <string>{{serialnumberlast4digits}}</string>
  <key>udidlast4digits</key>
  <string>{{udidlast4digits}}</string>
  <key>aaddeviceid</key>
  <string>{{aaddeviceid}}</string>
</dict>
```
