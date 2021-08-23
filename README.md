# UniGraphic
Fork of mbed-os [UniGraphic](https://os.mbed.com/teams/GraphicsDisplay/code/UniGraphic/)  

The UniGrapich Library is extended to support:
* 240x240 LCD on ILI9341V driver - https://www.panelook.com/NMLCD-220Q33-2-2-inch-320x320-160nits-39pins-16-bit-RGB-I-F-With-RTP-TN-LCD-detail_83363.html

* "Fast SPI" that utilises HAL directly as an mbed-os SPI interface is to slow to play video with FPS the video looks smoothly. Even the interface is called SPI_DMA but actually it does not support DMA yet(Have a plan to that later). Btw it is much faster than mbed-os SPI.

* Alow external display reset
