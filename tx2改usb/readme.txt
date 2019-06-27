Q: tx2 usb lane mapping config  //圖

TX2 config#4 for USB LANE MAPPING
https://devtalk.nvidia.com/default/topic/1030635/jetson-tx2/tx2-config-4-for-usb-lane-mapping/1

usb rx/tx 說明: 成大資工
http://wiki.csie.ncku.edu.tw/embedded/USART


Jetson / TX2 USB  官方
https://elinux.org/Jetson/TX2_USB

Jetson TX2/FAQ 官方
https://elinux.org/Jetson_TX2/FAQ#USB.2FPCIE.2FSATA_mapping_difference_between_Jetson_TX1_and_Jetson_TX2

------------------vbus電路圖--------------------
https://developer.download.nvidia.com/assets/embedded/secure/jetson/TX2/docs/JetsonTX2_OEM_Product_DesignGuide.pdf?lLIQ4lZ_gG8wmikb8KSvvqEAjA1pTTsb5eU2FmJv2WBk3T42aOrMx3YIu6U6IVGkrWLr4iCPjNfSFQwVvJRhBFzsxJlpKJC5uJjsoxjUiCM25xG9IAC22y8V24TAZYkYbi2L0XMtf4M2HoAqTvphs29C7YiuUDNjq0SKi6-Cotg-f9FTsIoF3SUHQA


-----------如何開啟英偉達TX2的所有USB3.0--------------
https://blog.csdn.net/bhniunan/article/details/88605037

-------NVIDIA TX2自製底板的USB無法使用的一種解決方法---------
https://blog.csdn.net/He110__W0r1d/article/details/86666152
https://blog.csdn.net/bhniunan/article/details/80707569

vbus wiki  //提供電壓


---------------------------------
com speed  baud rate  成大資工
http://wiki.csie.ncku.edu.tw/embedded/USART


-------------------------------
Q: dtc -I dts -O dtb -o     //dtc (compiler)  DTC編譯*.dts生成的二進製文件(*.dtb)
device tree 樹狀結構 
https://www.cnblogs.com/aaronLinux/p/5496559.html

dtc指令參考
https://read01.com/jP73MG.html#.XQ94ZugzY2w 


-----------------------------   solution !
auvidea官方修改tx2 成config 6
https://auvidea.eu/search/firmware/


------------------------------  solution !

將xusb_padctl @ 3520000中將usb2-0的模式更改為“host”
https://devtalk.nvidia.com/default/topic/1047678/jetson-agx-xavier/usb-does-not-working-on-jatson-agx-xavier-/3
