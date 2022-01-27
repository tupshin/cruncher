# cruncher
Notes on building a low profile vertically mounted CNC machine



# Software configuration
* LinuxCNC

# Parts List

## Structure
* Frame
  * [2x3 1/4" steel tubing](https://www.bushwickmetals.com/how-strong-is-square-tubing-and-when-should-you-use-it/) (roughly 7lb/ft)
* X axis carriage (holds z axis and slides on gantry)
  * [4x6 3/8" angle aluminum](https://www.metalsdepot.com/aluminum-products/aluminum-angle-6061)
* rails
  * 1500mm sbr25 mounted on steel tubing
  
## Basic Electronics
* [CL86T Stepper Driver](https://www.omc-stepperonline.com/closed-loop-stepper-driver-0~82a-24~80vdc-for-nema-34-stepper-motor-cl86t.html)
  * [User Manual](https://www.omc-stepperonline.com/download/CL86T.pdf)
  * [Software Manual](https://www.omc-stepperonline.com/download/software_manual_for_CL86T_CLA86T.pdf)
* [Nema 34 Stepper Motor](https://www.omc-stepperonline.com/s-series-nema-34-closed-loop-stepper-motor-12-0-nm-1699-68oz-in-encoder-1000ppr-4000cpr.html)
  * [Torque Curve](https://www.omc-stepperonline.com/download/34HS59-6004D-E1000_Torque_Curve.pdf)
  * [Datasheet](https://www.omc-stepperonline.com/download/34HS59-6004D-E1000.pdf)
* [Mesa 7i76E](http://store.mesanet.com/index.php?route=product/product&product_id=290) Ethernet FPGA Card
  * [Manual](http://www.mesanet.com/pdf/parallel/7i76eman.pdf)
 * [extension cable](https://www.omc-stepperonline.com/cable-kit-1-7-m-67-long-motor-extension-cable-and-1-7-m-67-long-encoder-extension-cable-for-nema-34-closed-loop-stepper-motors-just-for-aviation-plug-model-motor.html)
 * [60v switching power supply](https://www.omc-stepperonline.com/)
 ## Additional Electronics
* [Current Meter](https://aimdynamics.com/product/AIMH021-025A-420T/)
* 