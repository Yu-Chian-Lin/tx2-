�x��о� 
https://www.jetsonhacks.com/2019/06/04/nvidia-sdk-manager-for-jetson-jetpack-4-2/

jetpack ��ubuntu 
��� ��t�� 

����ĳ������:
https://www.itread01.com/content/1544768840.html

�q�s�}�l:
https://machine-learning-python.kspax.io/nvidia_jetson_tx2/1_host 

----------
tx2 usb���D  https://elinux.org/Jetson/TX2_USB
Q : L4T28.2 TX2 USB Lane Mapping    https://devtalk.nvidia.com/default/topic/1030635/jetson-tx2/tx2-config-4-for-usb-lane-mapping/
device tree  ��ʱҥ�USB�q��

�׸�DTB  
1. �U�����GTegra186-tx2-usb-base.tar.gz�ñN������Y��z��Jetson

�׸�DTS  �]�ƾ�

sudo apt-get install dtc    // dtc�n�z�Lapt�U��

home/miis/nvidia/nvidia_sdk/jetPack_4.2_Linux_P3310  ...  ���|�U�ק� dtc�ɮ�
�ޥ�:
sudo cp �ɮ�  �Y�n�Q�л\�ɮ�


�ǲ߲׺ݾ� vim ~  �����ҳ]�w�覡python 2.7 (������}��/����� ?) 

Flash Jetson���Ѱ��D : tx2 sdk manager could not detect target hardware
https://devtalk.nvidia.com/default/topic/1048803/jetson-tx2/sdk-manager-could-not-detect-target-hardware/1

----------------------------------------tx2 os

putty download �Ptx2�s��  �Ucmd����
https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html
com(�˸m�޲z��) 115200
sudo shutdown
�K�Xnvidia

winSCP ��r�������� 

nvidia sdk manager �˦b�׺�  �ɦW.deb  // �w��os  �ݵ��U�b�� 


micro-usb tx2�s��:
���U�q���}��
����_��O��}

���U���]�i�J�_��Ҧ�
�i�H��}�_����

terminal: 
lsusb    // �d��usb�˸m  �O�_��nvidia 

---------------
python  // �i�Jpython
ctrl + d //�h�Xpython
lsusb  //�d��usb
lsblk  //�d�ݳs�����A   http://man.linuxde.net/lsblk   linux���O http://man.linuxde.net/xinshoumingling
sudo reboot //���s�Ұ�


JetPack 4.2 Flashing Issues and how to resolve - NVIDIA Developer
https://devtalk.nvidia.com/default/topic/1050477/jetson-tx2/jetpack4-2-flashing-issues-and-how-to-resolve/