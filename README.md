# PCB_startup_steps:
1. Connect to Jetson through ssh<br>
   ssh nvidia@192.168.0.122
   password: nvidia
2. Enter image_capture
3. Run Nvidia startup<br>
   ./ionis-startup.sh
4. Initialize camera 3 times.<br>
   ./image_capture_init
5. Check if the file init_image.png exists and good.
6. Fix the camera parameter<br>
   ./image_capture_init_post
7. To check Thermal camera<br>
   ./image_capture

8. New tab and login to jetson using ssh. Start ./a.sh
9. New tab and login to jetson using ssh. Start ./q.sh
10. New tab and login to jetson using ssh. Start ./cli.sh
11. New tab and login to jetson using ssh. Start ./i.sh
