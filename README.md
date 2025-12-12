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
            maven { url = uri("https://annu588.github.io/embed-sdk-mobile/maven/") }
        }
    }
    
<img width="914" height="702" alt="image" src="https://github.com/user-attachments/assets/8b45ea39-a8c1-4d15-ab72-b689b46e5262" />


### **Step 2 — Add the SDK dependency**
Add the latest stable Adobe Express Embed SDK release to your module’s build.gradle:
You can always find the latest build number and full release details on the
[GitHub Releases](https://github.com/AdobeDocs/express-embed-mobile-sdk-android-release) page.
    
    dependencies {
        implementation "com.adobe.express.embed:embedsdk:0.2.81"
    }
    
<img width="869" height="666" alt="image" src="https://github.com/user-attachments/assets/b3b6b8dd-8ddb-4c29-b3bc-48047c48ee66" />


That’s it — sync your project and start using the SDK

