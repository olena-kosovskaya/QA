### Sharing branding option

#### Pr: https://github.com/owncloud/android/issues/1631

Devices: Tablet Android 5.x or 6.x to OC8.2.2 <br>
         Smartphone Android 4.x to OC9


Server version: 9 and 8.2.2

<br>
 
Test Case ID | Test case     | Steps   | Expected behavior | Result | Related Comments
|:----:|:------------- |:-------------------|:-------------|:-------------:|:----------
***Branding variable API ENABlE***|
1|Disable share completely| 1.- Set "share_with_users_feature" to "false" in setup.xml <br> 2.- Set "share_via_link_feature" to "false" in setup.xml <br> 3.-Select to share a file| Share option is not shown | 
2 |Disable share completely| 1.- Set "share_with_users_feature" to "false" in setup.xml <br> 2.- "share_via_link_feature" to "false" in setup.xml <br> 3.-Select to share a file from the share link view| Share option is not shown | 
3 |Disable internal sharing - check portrait| 1.- Set "share_with_users_feature" to "false" in setup.xml <br> 2.- Select to share a file | just share by link is shown |  | 
4 |Disable internal sharing - check landscape| 1.- Set "share_with_users_feature" to "false" in setup.xml <br> 2.- Select to share a file | just share by link is shown |  | 
5 |Disable internal sharing - check landscape| 1.- Set "share_with_users_feature" to "false" in setup.xml <br> 2.- Select to share a file from the details view| just share by link is shown |  | 
6 |Disable share link - check portrait| 1.- "share_via_link_feature" to "false" in setup.xml <br> 2.- Select to share a file | Just internal sharing is shown | 
7 |Disable share link - check landscape| 1.- "share_via_link_feature" to "false" in setup.xml <br> 2.- Select to share a file | Just internal sharing is shown | 
8 |Disable share link - check landscape| 1.- "share_via_link_feature" to "false" in setup.xml <br> 2.- Select to share a file from the details view | Just internal sharing is shown | 
9 |Multiaccount - disable internal sharing| 1.- "share_via_link_feature" to "false" in setup.xml <br> 2.- Select to share a file from the details view | Just internal sharing is shown |  |





