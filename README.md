# LearningKotlin
Practicing Android App development


## **Android Manifest**
- **Root configuration file** that declares essential app information to Android OS
- Contains app components, permissions, and metadata

## **Application Tag**
- **Container** for all app components (activities, services, etc.)
- Defines **app-level properties** like icon, label, and theme

## **Activity**
- **Represents a single screen** in your app
- **MainActivity** = The entry point/first screen that launches

## **Intent Filter**
- **Tells Android when an activity should be launched**
- **`LAUNCHER` category** = Makes MainActivity the **first screen** that opens when app starts
- Acts as a "welcome mat" specifying which actions trigger the activity

## **Simple Flow:**
**Manifest** (blueprint) → **Application** (app container) → **Activity** (screen) → **Intent Filter** (launch rule making it the entry point)
