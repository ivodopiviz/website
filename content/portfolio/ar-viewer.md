+++
date = "2018-05-08T15:48:31+02:00"
tags = ["unity", "ar", "augmented reality", "mobile"]
title = "AR Viewer"
type = "post"

+++
### AR Viewer

![](/uploads/2018/05/08/screen1.PNG)

#### Description:

This was an interesting augmented reality project that, unfortunately, was never released. The basic idea was that cable technicians usually have trouble identifying what is what when dealing with crowded equipment and this project was aimed to provide a clean and advanced solution.

Several augmented reality "data layers" would give the technician information about the device itself, about each customer and real time data of the device performance and issues.

The project itself was split in three parts:

* The "viewer" that you can see in the screenshot above.
* A desktop client to be used by headquarters personnel, to guide and assist the on-site technician. The desktop app would get a pseudo real time video feed of what the technician could see and it would be able to "ping" different parts of the device to drive the technician's attention.
* A node.js server to tie all this together and to act as data aggregator to send to the viewer and desktop apps. It would also store incidence reports.

#### Technology:

Unity

Vuforia

node.js

iOS

Android