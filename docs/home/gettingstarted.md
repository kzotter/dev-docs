# Getting Started


## Setup
To get started with Esper, you need a dedicated Esper endpoint set up on Esper Cloud through our Esper Trial. An Esper endpoint is a private instance where you can access the Esper Console to create and manage keys used for calling the Esper APIs. Follow the steps below to setup your Esper Trial and get started.


1. **Esper Trial Sign Up** Sign up for the Esper Trial to obtain access to the Esper Console with a private Esper Cloud account. During that process you will set up your endpoint name. Once your endpoint is set you can login to your account on `foo.shoonyacloud.com` where “foo” is your chosen endpoint name giving you access to the Esper Console. See [Requesting an Esper Dev Trial account](./module/register.md)
2. **Create API Key** In the Esper Console under Developer options you can generate an API key token which combined with your endpoint name is used to authenticate your API calls. Note for some APIs the Enterprise ID is also required, this ID is provided also in Developer options. 
3. **Install Esper Tools** If you plan on calling the APIs using Python, follow the steps to install the Esper SDK for Python. If you plan to use REST/HTTP, please refer to the API reference. Install the Esper CLI to call the Esper APIs from the command line. Finally, install the Esper Plugin for Android Studio which provides integration into your Esper Cloud endpoint and useful tools for building and debugging your applications. Note your endpoint name and API key are required to properly configure and / or use the tools.
4. **Upload an App** Upload one of your applications to your Esper endpoint. You can use the application upload API, or upload it using the Esper Console in the Apps seciton.
5. **Target Device**  An Android device used with Esper to directly target a Dedicated Device outside of emulation. If you don’t have a suitable device you can work with the emulation environment in Android Studio. You can use your own device or devices if they meet the requirements stated earlier. Or you can purchase Esper Development Devices running Esper Enhanced Android from Esper. See [Purchasing DevKits](./module/devkits.md)
6. **Device template** Next you create a Device Template where you define the initial profile for your device's security, apps, and settings. A device is then provisioned using the  Device Template. See [Creating a device template](https://consoledocs.esper.io/device-template/)
7. **Device Provisioning** Now you can provision your device using any of the supported methods. For developers, we suggest using ADB.

    1. [ADB provisioning](https://consoledocs.esper.io/device-provisioning/adb-provisioning/)
    2. [AFW provisioning](https://consoledocs.esper.io/device-provisioning/afw-provisioning/)
    3. [IMEI or Serial number based provisioning](https://consoledocs.esper.io/device-provisioning/imei-or-serial-number-based-provisioning/)
    4. [6 tap provisioning](https://consoledocs.esper.io/device-provisioning/6-tap-provisioning/)

    See [Provisioning a device](https://consoledocs.esper.io/device-provisioning/)

8. **Start Playing** Try out Esper during your app development sessions. Use the CLI to execute API calls for your apps and target devices as you create and build. Try the features of the Android Studio Plugin to see how it streamlines the process of loading and testing your apps on target devices. Automate some of the frequent app provisioning and loading processes using the Python SDK. Explore the Esper Console to see the capapilities offered to manage your apps and devices. 

In summary here are the reference or install points for the available Esper tools:

    - If you are calling the Esper APIs using `HTTP`, see the Esper [API Reference v1](https://api.esper.io)
    - If you are using the Python SDK in Android Studio to call the Esper APIs using the Esper SDK, see [Esper SDK](./pythonsdk.md)
    - Download the Command line tool, Esper CLI with full source code, to work the Esper APIs. Download the Esper CLI [here](./espercli.md)
    - If you want to the Esper Plugin for Android Studio, see Installing the Esper Plugin.

## Quick links

Below are the quick links to the guide for specific actions on the Esper platform.

- [Learn about Device management](https://consoledocs.esper.io/device-management/)
- [Learn about Application management](https://consoledocs.esper.io/app-management/)
- [Learn about Device Group management](https://consoledocs.esper.io/group-management/)
- [Getting started with Esper SDK](./pythonsdk.md)
- [Getting started with Esper CLI](./espercli.md)
