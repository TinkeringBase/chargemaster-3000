[English](https://github.com/FTIndustries/chargemaster-3000)
# FT Industries Chargemaster-3000
![preview](https://github.com/FTIndustries/chargemaster-3000/blob/main/3dpreview.png?raw=true)\
BQ25606칩에 기반한 리튬이온/리튬폴리머 배터리 충전 모듈입니다. 최대 3A로 배터리를 충전할 수 있습니다. 입력부가 TVS로 보호되어 있어 정전기로부터 최소한의 방호력을 지닙니다. USB-PD 장치로 기능하며 9V의 전압을 입력받습니다. 과충전 방지, 전원 경로 제어, 최대 충전 전류 설정을 제공합니다. 충전 중에도 안전하게 배터리 전원을 사용할 수 있어 전류 부족에 대해 걱정할 필요가 없습니다.
## 배터리 전압 설정
배터리 전압은 초기에 4.2V로 설정되어 있습니다. 전면의 VSET 점퍼를 납땜하여 4.35V로 설정할 수 있습니다.
## 최대 충전 전류 설정
![backpreview](https://github.com/FTIndustries/chargemaster-3000/blob/main/pcbbackpreview.png?raw=true)\
최대 충전 전류는 초기에 3A로 설정되어 있습니다. 모듈 뒤의 점퍼를 끊어서 2A로 제한할 수 있습니다. 3A 전류로 다시 설정하려면 점퍼를 납땜하세요.
## 충전 전류 경고
배터리 팩의 스펙을 초과하는 전류로 충전하지 마십시오. 배터리가 과열되고 손상될 것이며, 화재로 이어질 수 있습니다. 배터리가 0.5C의 충전 속도를 보장하고 2000mAh의 용량을 가지고 있다면, 최대 충전 전류는 1000mA 입니다. (2000*0.5)
## 커넥터
MOLEX 51021 RB 타입 커넥터를 수용합니다. 국내에서 판매하는 DTP사와 TW사의 배터리가 호환됩니다. 연결하기 전 항상 극성을 확인하십시오.\
![adsf](https://github.com/FTIndustries/chargemaster-500/assets/47267045/8cbb29fd-9ee4-4e2c-87f2-7d67e7da962e)
### 배터리 보호
일반적인 TP4056 모듈과는 다르게, 이 모듈은 과방전 방지와 과전류 방지를 제공하지 않습니다. 때문에 보호 회로가 내장된 배터리 팩을 사용하거나, 추가적인 배터리 보호 회로를 사용해야 합니다.
