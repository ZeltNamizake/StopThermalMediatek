# How to stop and run thermal on Mediatek chipset with Termux
<div align="center">
  <img src="https://telegra.ph/file/48fa03b640a63e3012ef4.png" width="200" height="200">
  <br>
  <br>
<img alt="Static Badge" src="https://img.shields.io/badge/MAGISK-%2300AF9C?style=for-the-badge&logo=Magisk&labelColor=black" width="200" height="50">
</div>

## Note!
The device must be rooted, if it is not rooted then you cannot stop or run thermal on the device

#### How to get Termux to access root
•Open the Termux application and type on terminal:

`su`

•Allow application Termux for Superuser

•Click CTRL+D (for exit)

##### How to install it:
`pkg install tsu`

`git clone https://github.com/ZeltNamizake/StopThermalMediatek`

`cd StopThermalMediatek`

`tsu`

##### How to stop Thermal
`bash dthermal.sh`

##### How to run Thermal
`bash ethermal.sh`

##### To determine whether it is stop or run
`getprop | grep thermal`
