## Brackets 1.14.2 is here!
[**Open File in external Applications**](https://github.com/adobe/brackets/pull/15088) 
Brackets now offers support to open file of any arbitary type with any external applications. in User Preferences settings, You can associate a file extension to its OS default application or application you want.

Usage:
Example Preferences settings for associating file with extensions "svg" to its Google Chrome applications and "psd" to its default Applications.

  "externalApplications": {
    "svg": "google chrome",
    "psd": "default"
  }


 The application's name in this settings is OS dependant, for example if you would like to to open Chrome you have to use "google chrome" on macOS and "chrome" on Windows in your settings. We use the open npm utility under the hood, settings that works with this utility will work here.

 You may also pass in the app's full path. For example on Windows, this can be "C://Program Files (x86)//Google/Chrome//Application//chrome.exe" for the Windows installation of Chrome.


[**Automatically associate Graphics file types to its OS default application**](https://github.com/adobe/brackets/pull/15092) Also, If opened project would have any graphics file of type: [], then A dialog will be shown to associate all graphics files with its OS default Applications. If you click yes. Brackets will detect OS default Applications for all mentioned type and associate these graphics file type to its default applications in preference settings.