# Adobe Express Embed SDK – Android

---

## Installation Guide

Follow these steps to add the SDK to your Android project.

---

### **Step 1 — Add the Maven repository**

Add the SDK’s Maven repository to your root project.
    
    dependencyResolutionManagement {
        repositories {
            google()
            mavenCentral()
            maven { url = uri("https://adobedocs.github.io/express-embed-mobile-sdk-android-release/maven/") }
        }
    }
    
<img width="933" height="327" alt="image" src="https://github.com/user-attachments/assets/81746890-9d63-4aac-b91e-242b75d008e7" />


### **Step 2 — Add the SDK dependency**

Add the latest stable Adobe Express Embed SDK release to your module’s build.gradle:

Version - Please refer to [GitHub Releases](https://github.com/AdobeDocs/express-embed-mobile-sdk-android-release/releases) to get the latest version.
    
    dependencies {
        implementation "com.adobe.express.embed:embedsdk:x.y.z"
    }
    
<img width="869" height="666" alt="image" src="https://github.com/user-attachments/assets/b3b6b8dd-8ddb-4c29-b3bc-48047c48ee66" />


That’s it — sync your project and start using the SDK

