# Navigation-UCC-ITM_A-IVI_V1.11
Ce calculateur sert pour tout ce qui concerne l'Eazylink

## Diagnosis
Cette catégorie sert essentiellement au diagnostic et la la réinitialisation de l'Eazylink. Ne touchez à rien à moins de savoir exactement ce que vous faites et d'en avoir l'utilité.

## Configuration
Cette catégorie sert à effectuer des parametrages.

### Vehicle information $DAB0
Ne pas modifier ce qui est dans l'encadré rouge "Power Management", risque de bricker votre système.

#### VR / SPVR

| Commande | Utilité |
| :---- |:---- |
| BlowerReductionRequest | ? |
| Steering_SW | Type de commande multimédia au volant |
| Microphone | Définit le type de micro connecté au système |


#### Multimédia Information

| Commande | Utilité |
| :---- |:---- |
| Cd_value | ? |
| Destination | ? |
| ETC 2.0 | ? |
| Ethernet interface | ? |
| External_CD_drive | ? |
| Fuel_consumption_info | ? |
| HUD | ? |
| HUD_Setting | ? |
| Inductive charger | Définit si la voiture est equipée d'un chargeur sans fil /Non Testé/ |
| IT-Commander_/_Central_Switch | ? |
| Media_Player | ?  |
| Meter_setting_icon | ? |
| Navi_available | Définit si le système comprend la navigation /Non Testé/ |
| RCS_(Rear_Armrest_Switch) | ? |
| RSE | ? |
| TCU | ? |
| Seat_Guidance_DR | ? |
| Seat_Guidance_PS | ? |
| RADIO SATELLITE SWITCH | ? |

#### Vehicle information
Toutes les informations concernant la voiture. De manière générale ne modifiez rien ici sans raison

| Commande | Utilité |
| :---- |:---- |
| Type_of_meter | ? |
| Driving_type | 4rm / traction / propulsion |
| Fuel_type | Energie du véhicule |
| Petrol_type | Qualité de l'essence |
| Steering_position | LHD = volant a gauche / RHD = volant à droite |
| Transmission | Type de transmission |
| Vehicle_Type | ? |
| Height_of_vehicle | Dimensions de la voiture |
| Length_of_vehicle | Dimensions de la voiture |
| Weight_of_vehicle | Poids de la voiture |
| Width_of_vehicle | Dimensions de la voiture |
| Vehicle-body_shape | Type de carosserie |

Steering_position : LHD = volant à gauche / RHD = volant à droite

Transmission : Unknown = inconnu / AT = automatique / CVT = variation continue (electrique) / MT = manuel

#### ADAS
Tout ce qui va concerner les aides à la conduite

| Commande | Utilité |
| :---- |:---- |
| IPA/HFP | ? |
| Learning_Park_function | ? surement en lien avec le park assist /Non Testé/ |
| Intelligent_speed_assist | Detection des panneaux de limitation de vitesse /Non Testé/ |
| Remote_Park_function | Park assist ? /Non Testé/ |
| Traffic_sign_recognition | Détection des autres panneaux /Non Testé/ |

#### EV
Tout ce qui concerne les véhicules électriques / hybrides rechargeables

| Commande | Utilité |
| :---- |:---- |
| Charging cable grouping | ? |
| CNF_CHG_FACTYPE | ? |
| CNF_CHGCAB_SPTEND | ? |
| CNF_CHGCAB_VEHEND | ? |
| The maximum motoy output power | ? visiblement la puissance moteur maxi. /Non testé/ |
| Motor maximum regenerative power | ? visiblement puissance de recharge au freinage /Non testé/  |
| HEV_Shape_of_body | ? |
| CNF_VEH_CHG_CON | ? Peut-être le connecteur de charge /Non testé/ |
| Reduction_gear_efficiency | ? |
| Smart charging | Recharge intelligente ? /Non testé/ |
| EV_HVAC | Commande de clim / chauffage à distance / programmée ? /Non testé/ |
| Motor_efficiency | ? |

#### TPMS

| Commande | Utilité |
| :---- |:---- |
| TPMS | ? |

#### Camera parameters

Paramètrage de la caméra de recul

| Commande | Utilité |
| :---- |:---- |
| Camera Picture Color | ? |
| DynamicLenght | ? |
| Warning Text Pos | Position du texte d'avertissement (regarder dans toutes les directions) /Non testé/ |
| TuningDeltaXFarLeftDyn | ? |
| RearView Activation | ? |
| TuningDeltaXFarRightDyn | ? |
| Additional RVC configuration items | ? |
| Crop-Up | ? |
| Crop-Down | ? |
| Crop-Left | ? |
| Crop-Right | ? |
| Camera Picture Holding Time | Temps de maintien de la caméra à l'écran après le passage au neutre ou en marche avant /Non testé/ |
| Reverse Gear Debouncing | ? |
| Camera rear trunk behaviour | Peut-être action sur la caméra en cas d'ouverture du coffre /Non testé/ |
| Camera Picture Contrast | Reglage du contraste de la caméra /Non testé/ |
| Camera Picture Tint | ? |
| Camera Image Mirror | Mise en miroir de la caméra |
| Vehicle Speed "Too High" | Vitesse de désactivation de la caméra /Non testé/ |
| Camera Picture Blank Level Day | ? |
| Camera Picture Blank Level Night | ? |

### System Information $DAB1

#### Display

| Commande | Utilité |
| :---- |:---- |
| Touch_screen_configuration | Type d'écran |
| ESE_HMI | ? Peut-être en lien avrec le MultiSense /Non testé/ |

#### VR / SPVR

| Commande | Utilité |
| :---- |:---- |
| Auto_barge_in | ? |
| Sound_on_encoder_press | ? |
| TTS | TextToSpeech ?? /Non testé/ |
| VA/SPVR | ? |
| VA_on_shortpress | ? |
| Voice_recognition | Active ou désactive la commande vocale /Non testé/ |
| VR_beep_only | ? |
| VR_short_prompts | ? |


#### Tuner Radio

| Commande | Utilité |
| :---- |:---- |
| AM tuner activation | Active ou désactive les fréquences AM /Non testé/ |
| DAB | Active ou désactive le DAB+ /Non testé/ |



#### BT/Wifi/Carplay/Android Auto
Tout ce qui concerne l'intégration smartphone

Si vous souhaitez activer la prise en charge de Android Auto / Carplay sans fil il faut absolument activer aussi les 3 options "Wifi_function" / "Wifi_IVC_tethering" / "Wifi_5GHz_support", si non cela ne fonctionnera pas. 

**Il est aussi possible que la commande "Bluetooth_function" soit désactivée alors que le Bluetooth fonctionne sur votre Eazylink. Dans ce cas** **_NE TOUCHEZ PAS A CETTE OPTION ET LAISSEZ LA DESACTIVEE_** **sans quoi votre Eazylink risquerait de finir brické (1200€ de réparations chez Renault !).**  


| Commande | Utilité |
| :---- |:---- |
| Android_Auto | Active / désactive la prise en charge Android Auto |
| Wireless_Android_Auto_function | Active / désactive la prise en charge AA sans fil |
| Carplay | Active / désactive la prise en charge Carplay |
| Wireless_CarPlay_Function | Active / désactive la prise en charge Carplay sans fil |
| SIRI | Active / désactive la prise en charge de Siri /Non testé/ |
| MySPIN | ? |
| OnCar | ? |
| ATBOX | ? |
| Baidu_CarLife_function | ? |
| Bluetooth_Function | **Ne touchez pas a cette option si votre bluetooth fonctionne même si elle est désactivée !** |
| CNF_VPA | ? |
| WBS | ? |
| Wifi_function | Active/désactive la fonction Wifi |
| Wifi_IVC_tethering | Active/désactive la fonction Hotspot Wifi |
| Wifi_5GHz_support | Active la prise en charge du Wifi 5GHz |









| Commande | Utilité |
| :---- |:---- |
|  |  |
|  |  |
|  |  |
|  |  |
