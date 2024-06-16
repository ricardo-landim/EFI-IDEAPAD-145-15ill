# Lenovo IdeaPad S145 (Ice Lake) Hackintosh 2024


EFI para Lenovo IdeaPad S145 OpenCore Bootloader

Compativel com Lenovo Ideapad S145 10.º Geração Ice Lake com os processadores i3-1005G1 UHD, i5-1035G1 UHD e i7-1065G7 Intel® Iris® Plus Graphics.

                                         
### Laptop Especificações:


| Component        | Brank                              |
| ---------------- | ---------------------------------- |
|                                                       |
| CPU              | Intel i5 1035G1                    |
| iGPU             | Intel® Iris Plus Graphics          |
| Audio            | Realtek ALC230                     |
| Ram              | 20 GB DDR4 2667 Mhz                |
| Wifi + Bluetooth | BCM94360NG                         |
| SmBios           | MacBookPro 16,2                    |
| BootLoader       | OpenCore 1.0.1                     |
| macOS            | Monterey 12.7.4 (21H1123)          |


### O que funciona 100%?

- iGPU (excepto saída HDMI)
- Total ALC230 (Som e microfone) ALC ID layout 13
- Sleep / Wake
- I2C Touchpad com gestos (ELAN & SYNA)(Modo Polling)
- Teclado (PS2)
- Teclas de brilho e volume
- Wi-Fi & Bluetooth BCM94360NG
- Leitor Micro SD 
- WebCam (Monterey > talvez precise ManyCam modo 240p / Ventura > iPhone Camera pode ser uma solução)
- ACPI Bateria
- NVRAM 
- Recovery (macOS) boot do OpenCore


### Special Config:

- USB port mapping performed

## Warning

Não me responsabilizo por danos. Sempre faça Backup;

## Credits

- [Apple](https://apple.com/osx) for macOS.
- [Acidanthera](https://github.com/acidanthera) for OpenCore and some kexts
