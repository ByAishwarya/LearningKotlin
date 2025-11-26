# LearningKotlin
Practicing Android App development


## **Android Manifest**
- **Root configuration file** that declares essential app information to Android OS
- Contains app components, permissions, and metadata

### **Application Tag**
- **Container** for all app components (activities, services, etc.)
- Defines **app-level properties** like icon, label, and theme

### **Activity**
- **Represents a single screen** in your app
- **MainActivity** = The entry point/first screen that launches

### **Intent Filter**
- **Tells Android when an activity should be launched**
- **`LAUNCHER` category** = Makes MainActivity the **first screen** that opens when app starts
- Acts as a "welcome mat" specifying which actions trigger the activity

### **Simple Flow:**
**Manifest** (blueprint) → **Application** (app container) → **Activity** (screen) → **Intent Filter** (launch rule making it the entry point)

# **res Resource Folder**
- Resources in the form of files and static content that your code uses,
- such as colors and animations are contained in the Resource folder in Android Studio.
- The res folder has strict structure rules: exmaple: res/xml/ folder is strictly for executable XML resources that your app will use at runtime.
- You can't put arbitrary files directly in res like .txt
- We have 4 resources: string, color, font, dimensions

  ### **strings.xml**
  - String resource gives the capability to define the text in the res/values/strings.xml file.
  - Each entry is a key that represents the ID of the text and a value that is the text itself.
  - For instance, if I want a text to display Congratulations!, on my app, I might add this string to the string resource file called strings.xml.
 ```xml
<resources>
    <string name="message">Congratulations!</string>
</resources>
```
