# BLU Smart #
This Project Show list of duties  and Update Duties 

### Build Configuration ###
	This project was build on JDK 1.8.0
    compileSdkVersion 28
    minSdkVersion 16
    targetSdkVersion 28
	

### AndroidMainfest Permission 
	
#### Internet ####
     
	 <uses-permission android:name="android.permission.INTERNET" />
	
#### Location ####
   
  	<uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />



### Dependencies Used###

#### Butterknife ####

    implementation 'com.jakewharton:butterknife:8.8.1'
    annotationProcessor 'com.jakewharton:butterknife-compiler:8.8.1'
	Butterknife is used to Bind the view with activity/fragments.
	

#### Recyclerview ####

    implementation 'com.android.support:recyclerview-v7:28.0.0'
	REcyclerview is used for Showing List 
	
	
#### Runtime Permission ####

    implementation 'me.tankery.lib:permission-requester:1.1.0'
 
#### bcrypt ####

    implementation group: 'org.mindrot', name: 'jbcrypt', version: '0.3m'

	
#### Lint 
		
	Android Lint is used to scans Android project sources for potential bugs. 
	Lint configuration can be found in build.gradle file:
	lintOptions {
    abortOnError true
    checkAllWarnings true
    warningsAsErrors true
	}
