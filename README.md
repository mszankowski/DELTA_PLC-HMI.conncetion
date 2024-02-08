# Delta wgrywanie i zgrywanie programów na PLC oraz HMI

## 1. Wykorzystanie
Zebrane w repozytorium dane przygotowanie zostały w celu usystematyzowania wiedzy na temat połączenia się do produktów producenta [DELTA](https://www.deltaww.com/en-US/index) 

> **_NOTE:_**  123


------------------------
## 3. Linki i programy
Przydatne linki do pobrania programów:

- **Delta Download Center** (m.in. ISPSoft, VFDSoft, ASDA-Soft) [DownloadCenter](https://downloadcenter.deltaww.com/en-US/DownloadCenter)
- **Delta DIAStudio** (DIADesigner, DIAScreen, DIADesigner-AX, COMMGR) [DIAStudio](https://diastudio.deltaww.com)

Use latest [ESPHome](https://esphome.io/)

### 3.1 Programy *Delta Download Center*
- `ISPSoft` programownie PLC
  - DVP (SS2, SA2, SX2, SV2)
  - AS (AS200, AS300)
  - AH
  - VFD (C200, C2000, CP2000, MS300, MH300)
  - TP
- `DOPSoft v2` programowanie HMI
  - DOP-B
  - DOP-W
- `DOPSoft v4` programowanie HMI - UWAGA zmiana na **DIAScreen** dostępny z DIAStudio
  - DOP-100
- `ASDA-Soft v5` programowanie serwo
  - ASDA-B2
  - ASDA-A2
- `ASDA-Soft v6` programowanie serwo
  - ASDA-B3
  - ASDA-A3
- `VFDSoft`
  - E
  - C200, C2000, CP2000
  - ME300, MS300, MH300

### 3.2 Programy *Delta DIAStudio*
- `DIADesigner` programownie PLC
  - AS100
  - AS200
  - AS300
  - DVP-ES3
  - DVP-EX3
  - DVP-SV3
  - DVP-SX3
- `DIAScreen` programowanie HMI
  - AX 
  - DOP-100 
  - DOP-H (Handheld)
  - DXMC 
  - IMP 
  - TP 

## 4. Przewody
- Programownie PLC
  - DVP 
    - **RS232** (okrągłe czarne) 
    RS232 ***UC-PRG020-12A*** (https://github.com/mszankowski/DELTA_PLC-HMI.conncetion/blob/main/Przewody/UC-PRG020-12A.jpg)
    > _SS2, SA2, SX2_ 
    - mini USB
    > SX2, SE
    - RS485 **IFD6500** (https://github.com/mszankowski/DELTA_PLC-HMI.conncetion/blob/main/Przewody/IFD6500.jpg)
    > SS2, SA2, SX2, SE, SV2




------------------------
## 5. Author

mszankowski, 2022-2024

test
```st
zmienna : BOOL;
```
