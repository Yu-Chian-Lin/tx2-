官方教學 
https://www.jetsonhacks.com/2019/06/04/nvidia-sdk-manager-for-jetson-jetpack-4-2/

jetpack 灌ubuntu 
刷機 灌系統 

不建議虛擬機:
https://www.itread01.com/content/1544768840.html

從零開始:
https://machine-learning-python.kspax.io/nvidia_jetson_tx2/1_host 

----------
tx2 usb問題  https://elinux.org/Jetson/TX2_USB
Q : L4T28.2 TX2 USB Lane Mapping    https://devtalk.nvidia.com/default/topic/1030635/jetson-tx2/tx2-config-4-for-usb-lane-mapping/
device tree  手動啟用USB電源

修補DTB  
1. 下載文件：Tegra186-tx2-usb-base.tar.gz並將其解壓縮到您的Jetson

修補DTS  設備樹源

sudo apt-get install dtc    // dtc要透過apt下載

home/miis/nvidia/nvidia_sdk/jetPack_4.2_Linux_P3310  ...  路徑下修改 dtc檔案
技巧:
sudo cp 檔案  某要被覆蓋檔案


學習終端機 vim ~  改環境設定方式python 2.7 (分為剛開機/剛執行 ?) 

Flash Jetson失敗問題 : tx2 sdk manager could not detect target hardware
https://devtalk.nvidia.com/default/topic/1048803/jetson-tx2/sdk-manager-could-not-detect-target-hardware/1

----------------------------------------tx2 os

putty download 與tx2連接  下cmd關機
https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html
com(裝置管理員) 115200
sudo shutdown
密碼nvidia

winSCP 文字介面遠端 

nvidia sdk manager 裝在終端  檔名.deb  // 安裝os  需註冊帳號 


micro-usb tx2連接:
按下電源開機
按住復原別放開

按下重設進入復原模式
可以放開復原鍵

terminal: 
lsusb    // 查看usb裝置  是否有nvidia 

---------------
python  // 進入python
ctrl + d //退出python
lsusb  //查看usb
lsblk  //查看連接狀態   http://man.linuxde.net/lsblk   linux指令 http://man.linuxde.net/xinshoumingling
sudo reboot //重新啟動


JetPack 4.2 Flashing Issues and how to resolve - NVIDIA Developer
https://devtalk.nvidia.com/default/topic/1050477/jetson-tx2/jetpack4-2-flashing-issues-and-how-to-resolve/