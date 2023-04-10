# Android Emulator ios Skin
This is a skin for Android emulators that resembles an iPhone 14 Pro Max featuring the dynamic island.
It accurately depicts both its screen-size and resolution, so a developer such as myself can approximate 
how an application may look on an ios device, for those of us without direct access to a machine utilizing MacOS.

# Installation & Setup
1. Download the contents from this repository.
2. Move the folder containing said files to your Android Studio skins directory. By default this is **C:\Users\User\AppData\Local\Android\Sdk\skins**.
3. Open Android Studio and open the **Virtual Device Manager**.
4. Select **Create Device**.
5. Select **New Hardware Profile**.
6. Set **screen size** to 6.69", with a **resolution** of 1200x2720.
7. Scroll to the very bottom and browse for a **default skin** by pressing the menu icon.
8. Select the folder containing the iPhone skin and select **Finish**.
9. You'll be prompted to the **Select Hardware** page. Select your newly created device and press **Next**. Follow the prompts.
10. Lastly, press the ▶️ button to run your new AVD.

***Should the AVD fail to render with the skin, do the following:***
- Close all instances of the emulator, should there be one running.
- Select **Edit This AVD** (represented with the pencil icon).
- Select **Show Advanced Settings**.
- Repeat steps *six through eight*.
- Press the ▶️ button.
