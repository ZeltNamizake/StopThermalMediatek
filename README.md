# How to disable thermal on Mediatek chipset with Termux
<div align="center">
  <img src="https://telegra.ph/file/48fa03b640a63e3012ef4.png" width="200" height="200">
  <br>
<img alt="Static Badge" src="https://img.shields.io/badge/MAGISK-%2300AF9C?style=for-the-badge&logo=Magisk&labelColor=black" width="200" height="50">

</div>

## Note!
The device must be rooted, if it is not rooted then you cannot disable thermal on the device

#### How to disable the thermal
•Open the Termux application and type on terminal:

`su`

•Allow application Termux for Superuser in Magisk

###### For Disable Thermal

`stop thermal thermal_manager thermald thermalloadalgod`

Disable Thermal on the device so that the CPU does not experience throttling and the performance on the device is more stable, however, the temperature on the device will heat up quickly


###### For Enable Thermal

`start thermal thermal_manager thermald thermalloadalgod`


