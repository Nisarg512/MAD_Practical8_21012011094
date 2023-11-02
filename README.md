# MAD_Practical_8_21012011094

Aim: What is BroadcastReceiver? Difference between Service and BroadcastReceiver. Create an Alarm application by using service & BroadcastReceiver by following below instructions.

Create MainActivity according to below UI design.

Create AlarmBroadcastReceiver class

Create AlarmService Class

Add android.permission.SCHEDULE_EXACT_ALARM Permission in Manifest file

Ans:-

Broadcast in android is the system-wide events that can occur when the device starts, when a message is received on the device or when incoming calls are received, or when a device goes to airplane mode, etc. Broadcast Receivers are used to respond to these system-wide events. Broadcast Receivers allow us to register for the system and application events, and when that event happens, then the register receivers get notified.

Apps can use services to do long-running processes in the background, such as downloading files from a server, or checking for email, or checking your location. Although services don't show up or interact with you directly, they still show up in the "Running apps" list. Broadcast receivers are the third kind of component. Like services, they only exist in the background and don't interact with you directly. But unlike services, they can't stay running or perform long tasks: they exist to respond to events. And unlike activities and services, more than one broadcast receiver can be started in one go.

Output:

![image](https://github.com/Nisarg512/MAD_Practical_8_21012011094/assets/139303998/5222ea79-e442-4391-9041-d337b830df2c)

![image](https://github.com/Nisarg512/MAD_Practical_8_21012011094/assets/139303998/5af0c433-8423-4d8b-903e-9c75d63d3388)

![image](https://github.com/Nisarg512/MAD_Practical_8_21012011094/assets/139303998/f434be4b-ed46-4d7c-9017-1e752cdb4249)


