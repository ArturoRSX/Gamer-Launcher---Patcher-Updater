## **Creating your own Skin and Selling it**

You are allowed to create your own WPF UI Application to use the Game Launcher Unity Asset. And sell it in Unity Asset Store

Mark your asset as Game Launcher dependant.

Marking your asset as dependant

Marking your asset as dependant will advise your buyers that they will need to buy Game Launcher to make your asset work properly.

**Game Launcher URL:**

​[https://assetstore.unity.com/packages/slug/217526](https://assetstore.unity.com/packages/slug/217526)

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOQCKadC4SNL7ML9xwPi2%2Fuploads%2FfqaAUR9rKC9jjCkcebt0%2Fimage.png?alt=media&token=68e9b29b-2ce1-45dd-b460-d62913b120f6)

Marking your asset as Game Launcher dependant

Pricing

**Recommended price: $30 or more**

The price will depend on the features like:

Images and Content

Use the images as you want.

In the asset description please set a note: _"This asset depends on GameLauncher Asset to work properly"_.

Considerations

**DO NOT INCLUDE** _GameLauncherCore.DLL_ **in the Asset**

**If you are not developing new Core Features, do not include it.**

If you are developing new functions for Game Launcher Core, compile it in a new **.DLL** file.

Like: _**MyCustomFunctions.DLL**_

We recommend you to create these features separated from the primary _**GameLauncherCore.DLL**_ because we will continue submitting _**GameLauncherCore.DLL**_ updates.

If there's no way to separate your new feature from the primary DLL, you can contact me in _**carlosarturors@gmail.com**_ and we can search for a solution for this.

If you deploy a modified **GameLauncherCore.DLL** **WARN IT TO YOUR USERS**

The users using your Custom WPF will use your modified _**GameLauncherCore.DLL**_

This means if your users update the _**GameLauncherCore.DLL**_ **they will get errors.**

**You as developer, will be responsible of updating your modified DLL file with new features everytime we update it.**

But don't worry, we will warn it in the Game Launcher changelog if this happens.
