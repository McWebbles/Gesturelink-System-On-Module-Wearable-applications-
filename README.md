# Gesturelink-System-On-Module-Wearable-applications-
Gesturelink is a system on module that is designed for wearable applications originally designed for medtech and biomedical applications. This System on Module was originally designed for a specific application in the embedded/biomedical sector, although all hardware and design files will be included to make informed changes for differing usecases.

Gesturelink SoM is designed around wearable Edge AI applications that possesses a full audio front-end and D-Class amplifier, WiFI-5 or WiFi 802.11a/b/g/n/ac & Bluetooth v5.2, and a shared GPU or NPU capable of running LLM computation at 900MHz, capable of running OpenGL, Tensorflow, ONNX, etc.

The attached documents have all **altium** design files, schematics, PCB documents and schematic and PCB libraries that have been used up to the current date. The reason why it is altium is because this design was originated in altium, but migration into KiCad can be done. I am uploading the design files as they are. 

I have also attached the schematic design for what was to be my custom backplane for the Gesturelink SoM Module itself. It is **NOT**
complete, but has some foundational building blocks to grow from. 

**Current Considerations**
This has **NOT BEEN TESTED AND VALIDATED IN PERSON**. This is a ECAD design that was meant to be employed in a commercial setting, but due to uncontrollable factors can no longer, hence the value proposition to validate in person is now void.

The display breakout is designed currently for the PV13904PY24G ~1.4-1.7" AMOLED circular touchscreen display. This can be changed to any other DSI breakout display, although re-routing will be required. 

This SoM is mainly designed for performance in mind within the smallest space possible. Cost considerations were made at some stages although with the design techniques used to achieve this SOM, prototyping with this SOM is very cost inefficient, unless high-volume production is considered. 

JLC cannot manufacturer this SOM, but PCBWay can. Look into manufacturing capabilities of PCB manufacturers if you wish to employ this PCB for any application. 



