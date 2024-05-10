# Lightweight Console Toast

A lightweight console application showing a toast notification.

#

I somehow found pleasure in the "Windows Toast Notifications". You know, those little notes in the bottom right corner, when windows wants to tell you something.

![image](https://github.com/Molukkenberg/LightweightConsoleToast/assets/71791126/eb5fdd8b-ee1f-4a17-b363-44232a98ee98)


#

When I started researching and trying to get things running, my goal was to get those toasts show up using a console application in the most lightweight way to start off of that. Eventually after lots of desperate documentation reading and so on, I found just the right post by Karen Payne: https://dev.to/karenpayneoregon/using-toast-notifications-in-windows-forms-1dbe

#

My repo shows you get Windows Toasts running for console applications in the most basic way:

1. Create a console application in Visual Studio
2. Download this NuGet: https://www.nuget.org/packages/Microsoft.Toolkit.Uwp.Notifications/

    ![image](https://github.com/Molukkenberg/LightweightConsoleToast/assets/71791126/cb046c07-ccb8-43e0-9b38-9a0cb3dee8fb)

3. Add "-windows10.0.19041.0" to the "TargetFramework" property in the .csproj file 
4. Add a new ToastContentBuilder to your Program.cs file

    ![image](https://github.com/Molukkenberg/LightweightConsoleToast/assets/71791126/9cb882be-dc9a-42c7-bd82-8127c3828ebb)

5. Run the application
6. Success
