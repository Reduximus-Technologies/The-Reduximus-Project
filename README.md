# The-Reduximus-Project


The Reduximus Project (TRP) seeks to updated retro consoles with newer technolgy, giving them a new lease on life. Our first project is the Original Xbox. 

TRP OG XBox
1. Updated Modchip- The Reduxichip hosts 2 RP2040s and 1 ESP-32. The RP2040s serve two purposes, the first RP2040 runs the mod chip. The second RP2040 acts an enviromental supervisor for the other boards, ensuring they have intialized properly and reporting the status to the user via the imbeded OLED.
2. WiFi Adapter- The Reduximus WiFi adapter, is a custom designed PCB that fits perfectly into the holes left when the ethernet port of the OG Xbox is removed. It is powered by a ESP-32 and has a custom PHY designed to translate the WiFi signal into ethernet signal that the OG Xbox can understand.
3. HDMI Adapter- The Reduximus HDMI adapter, is a custom built adapter that connects to the Reduxichip for logical interface communication and status. It has its own video translation chips on board and boasts a flex cable that allows the user to remove thier OG Xbox video encoder and solder the flex cable directly to the motherboard. Then the Video Encoder is soldered to the HDMI adapter. This allows for a cleaner less stressful installation.
4. Bluetooth Controller Board- The Blueduximus controller board is a custom designed Bluetooth board that allows for bluetooth controllers to connect to the OG Xbox. This is accomplished by having an onboard usb conversion chip that converts the bluetooth logic from the controller and ESP-32s to USB for the OG Xbox to interpret.

Stay tuned for more updates as this project comes to life and the boards are produced and tested. As this currently is an R and D project, all code and PCB designes will be posted here. However, the use license for this is simple, you will credt Reduximus Technologies in all uses of intellelectual property designed and distributed by Reduximus Technologies LLC. Failure to properly source and credit Reduximus Technologies for their work will result in coressponding legal action. 
