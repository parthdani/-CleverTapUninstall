# Steps:

1) Add Synch Listener in Main Application class file.
2) Push CleverTap ID to Fireabse as custom user property i.e. "ct_objectId"
3) When you call onUserlogin function for CLeverTap, Once again set the synch listener and pass it on new CleverTap Id to Firebase. [Refer Main Activity file]
