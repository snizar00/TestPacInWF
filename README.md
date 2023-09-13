# Power Platform Project Template

> [!WARNING]
> **This repository is still work-in-progress!**

This Power Platform Project Template makes it easier for developers to get started with Power Platform development. 

## First-time run

When creating a GitHub Codespace for the first time based on this template, the `pac auth create` command will run. This will start a device login flow, to make it easy to connect to your Power Platform tenant. Use the device code to authenticate with your Power Platform tenant. After that, you can run the scripts in the script folder to setup environments or to setup your tenant settings.

If your device login timed out, make sure to run the following command:

```
pac auth create
```
