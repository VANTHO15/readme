## Template for Readme file

[<img src="images/1.jpg" width="240"/>](https://github.com/vantho15)

Tieu de 1.
- abc.
- xyz.

### Memory map
- [ 0x08000000 ] : **Boot** [[Hinh Anh 1]](https://github.com/VANTHO15/readme/blob/main/images/1.jpg)
- [ 0x08002000 ] : **BSF** [ Memory for data sharing between Boot and Application ]
- [ 0x08003000 ] : **Application** [[Hinh Anh 1]](https://github.com/VANTHO15/readme/blob/main/images/1.jpg)

**Note:** After loading boot & application firmware, you can use [Flash](https://github.com/VANTHO15/readme/blob/main/images/1.jpg) to load the application directly through the **USB** port on the KIT
```s
ak_flash /dev/ttyUSB0 stm32l151-application.bin 0x08003000
```

### Reference
| Topic | Link |
| ------ | ------ |
| Autosar | https://vantho0609.github.io/ |
| Infomation | https://autosarthonv.github.io |
