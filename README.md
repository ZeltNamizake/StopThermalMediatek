# How to disable thermal on Mediatek chipset with Termux
<div align="center">
  <img src="https://telegra.ph/file/48fa03b640a63e3012ef4.png" width="200" height="200">
</div>

## Note!
The device must be rooted, if it is not rooted then you cannot disable thermal on the device

#### How to disable the thermal
•Open the Termux application and Type in terminal:

`su`

•Allow application Termux for Superuser in Magisk

###### For Disable Thermal

`stop thermal thermal_manager thermald thermalloadalgod`

###### For Enable Thermal

`start thermal thermal_manager thermald thermalloadalgod`


