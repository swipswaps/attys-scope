# attys_scope
## UDP receiver for UNREAL

![alt tag](unreal_editor_screenshot.png)

With the help of this C++ class you can
create an Attys outlet which provides you
with all filtered / visible channels
in AttysScope.

## Installation

 * Create an AttysActor C++ class within the UNREAL editor
 * Replace the template AttysActor.cpp and AttysActor.h with the files provided here
 * Replace the "SCROLLER" in "SCROLLER_API" with the name of your project in AttysActor.h
 * Add "Sockets", "Networking" to the "Build CS" file
 * Create a blueprint from it
 * You should see an Attys outlet

## Usage

 * Just make sure UDP broadcast is enabled in AttysScope and the port
   is 65000 (default).
 * Select the sensors you'd like to see
 * They will show up in the order you've selected them in UNREAL

See https://wiki.unrealengine.com/UDP_Socket_Sender_Receiver_From_One_UE4_Instance_To_Another
for more info!