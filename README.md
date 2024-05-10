# Lightweight Console Toast

A lightweight console application showing a toast notification.

#

I somehow found pleasure in the "Windows Toast Notifications". You know, those little notes in the bottom right corner, when windows wants to tell you something.

#

When I started researching and trying to get things running, my goal was to get those toasts show up using a console application in the most lightweight way to start off of that. Eventually after lots of desperate documentation reading and so on, I found just the right post by Karen Payne: https://dev.to/karenpayneoregon/using-toast-notifications-in-windows-forms-1dbe

#

My repo shows you get Windows Toasts running for console applications in the most basic way:

    1. Create a console application in Visual Studio
    2. Download this NuGet: https://www.nuget.org/packages/Microsoft.Toolkit.Uwp.Notifications/
    3. Add "-windows10.0.19041.0" to the <TargetFramework> property in the .csproj file 
    4. Add a new ToastContentBuilder to your Program.cs file
    5. Run the application
    6. Success