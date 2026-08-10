Ce projet a été abandonné et on ne peut plus le flasher depuis le WEB FLASHER du créateur original j'ai reussi a recompiler les fichiers afin de remettre la v1.1.5 de Flipper port et remmetre bruce avec loption "switch to flipper" il ne sera probablment pas mis a jour. Vous pouvez installer une version plus récente de Bruce mais vous naurez plus le bouton 'switch to flipper' il faut reset a chaque fois 


This project was abandoned and you can no longer flash it from the original creator's WEB FLASHER. I managed to recompile the files to restore Flipper port v1.1.5 and bring back Bruce with the 'switch to flipper' option. It probably won't be updated. You can install a newer version of Bruce, but you won't have the 'switch to flipper' button anymore. you have to reset each time.

((((Copiez le contenu de la carte SD à la racine de votre carte SD pour que Flipper OS fonctionne correctement----Copy the SD card content to the root of your SD card for Flipper OS to function correctly))))

Secteur d'installation-installation sectors

- Bootloader : 0x0
- Partition Table : 0x8000
- Flipper OS (Furi) : 0x20000
- Bruce (Dualboot) : 0x510000

vous pouvez installer depuis le web via:

https://esptool.spacehuhn.com

ou/or

esptool (multiple) :
esptool.py --chip esp32s3 write_flash 0x0 bootloader.bin 0x8000 partitions.bin 0x20000 furi_esp32.bin 0x510000 bruce.bin




enjoy


