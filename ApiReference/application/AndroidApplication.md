---
nav-title: "Class application.AndroidApplication"
title: "Class application.AndroidApplication"
description: "Class application.AndroidApplication"
---
## Object: "application".AndroidApplication  
The abstraction of an Android-specific application object.

##### Properties
 - **nativeApp** - _Object_.    
  The android.app.Application object instance provided to the init of the module.
 - **context** - _Object_.    
  The application android.content.Context object instance.
 - **foregroundActivity** - _Object_.    
  The currently active (loaded) android.app.Activity. This property is automatically updated upon Activity events.
 - **currentContext** - _Object_.    
  The currently active (loaded) Context. This is typically the top-level Activity that is just created.
 - **startActivity** - _Object_.    
  The main (start) Activity for the application.
 - **packageName** - _String_.    
  The name of the application package.
 - **onActivityCreated** - _Function_(activity _Object_, bundle _Object_).    
  Direct handler of the android.app.Application.ActivityLifecycleCallbacks.onActivityCreated method.
 - **onActivityDestroyed** - _Function_(activity _Object_).    
  Direct handler of the android.app.Application.ActivityLifecycleCallbacks.onActivityDestroyed method.
 - **onActivityStarted** - _Function_(activity _Object_).    
  Direct handler of the android.app.Application.ActivityLifecycleCallbacks.onActivityDestroyed method.
 - **onActivityPaused** - _Function_(activity _Object_).    
  Direct handler of the android.app.Application.ActivityLifecycleCallbacks.onActivityPaused method.
 - **onActivityResumed** - _Function_(activity _Object_).    
  Direct handler of the android.app.Application.ActivityLifecycleCallbacks.onActivityResumed method.
 - **onActivityStopped** - _Function_(activity _Object_).    
  Direct handler of the android.app.Application.ActivityLifecycleCallbacks.onActivityStopped method.
 - **onSaveActivityState** - _Function_(activity _Object_, bundle _Object_).    
  Direct handler of the android.app.Application.ActivityLifecycleCallbacks.onSaveActivityState method.
 - **onActivityResult** - _Function_(requestCode _Number_, resultCode _Number_, data _Object_).    
  Direct handler of the onActivityResult method.

##### Functions
 - **getActivity(** intent _Object_ **)** _Object_  
     This method is called by the JavaScript Bridge when navigation to a new activity is triggered.
The return value of this method should be com.tns.NativeScriptActivity.extend implementation.
   - **intent** - _Object_
   - _**return**_ - _Object_