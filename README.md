## PAR-Aero Devices – Design and Prototype Projects
 
This is the master index for [PAR Aero](https://palliser.aero/) device design projects; below this table is a summary of each sub-project/version/revision. Each project will correspond to a `PAR-Aero-...` Github repository, while each sub-project will correspond to _either_ (i) a top-level directory in those repositories, _or_ (ii) a separate repository for the sub-project. Projects are named after départements of France, and may correspond to any aspect of PAR Aero device design and prototyping - airframes, parachutes, hardware, software, or tactics. 

Contact [@cpknight](https://github.com/cpknight) with your Github username for access to the repository that you're working on – many of these repositories make use of [Git Large File Storage](https://git-lfs.github.com/), so please also enable that extension on your system. 
  
| PROJECT      | SUMMARY                                                         | REPO                                                                |
|--------------|-----------------------------------------------------------------|---------------------------------------------------------------------|
| :arrow_right: **`PROJECT AIN`** | **Freefall/parachute data capture devices (500g)**: | [PAR-Aero-Ain](https://github.com/cpknight/PAR-Aero-Ain) |
| `Ain-0.1`    | _Cardboard RPi freefall state machine: data capture._ | 
| `Ain-0.1arp` | _Freefall state machine: Arduino RP2040 (Pico) port._ |
| `Ain-0.3`    | _Cardboard RPi freefall state machine: servo chute deployment._ |
| :arrow_right: **`PROJECT ALPES`**  | **Freefall data capture devices (100g)**: | [PAR-Aero-Alpes](https://github.com/cpknight/PAR-Aero-Alpes) |
| `Alpes-0.1` | _Materials and structure concept test (RPi Zero simulated payload)._ |
| :arrow_right: **`PROJECT AUBE`** | **Freefall/parachute aerial recce payload devices (500g)**: | [PAR-Aero-Aube](https://github.com/cpknight/PAR-Aero-Aube) |
| `Aube-0.1` | _Static chute foil tape cardboard construction wtih digital camera payload._ |
| `Aube-0.3` | _Static chute cardboard construction with RPi RF data capture payload. (Aube 0.5 Freefall State Machine forked from Ain 0.1)._ |
| `Aube-0.5` | _Static chute foamcore construction with RPi sensor data capture payload. (Aube 0.5 Freefall State Machine forked from Ain 0.3)._ |
| `Aube-0.7` | _Integrated chute deployment with RPi control and sensor payload._ |
| :arrow_right: **`PROJECT AVEYRON`** | **Flying wing autonomous aerial vehicles.**: | [PAR-Aero-Aveyron](https://github.com/cpknight/PAR-Aero-Aveyron) |
| `Aveyron-0.1-X1a` | _Micro RPAS flight demonstrator I (Micro Flying Wing; 250g)_ |
| `Aveyron-0.1-X1b` | _Micro RPAS flight demonstrator I (Micro Gliding Wing; 250g)_ |
| `Aveyron-0.1-X2` | _Micro RPAS flight demonstrator I (Mini Flying Wing; 280g)_ |
| `Aveyron-0.1-X3` | _RPAS flight demonstrator (Stable Mini Airfoil; 350g)_ |
| `Aveyron-1.0ɑ` | _Autonomous ground-launch Flying Wing with integrated Cantal payload bay._ |
| `Aveyron-1.0β` | _Autonomous ground-launch Flying Wing, initial production kit._ |
| :arrow_right: **`PROJECT BEAUFORT`** | **Small parachutes and deployment devices**: | [PAR-Aero-Beaufort](https://github.com/cpknight/PAR-Aero-Beaufort)  |
| `Beaufort-02.01` | _Plastic bag parachute_ |
| `Beaufort-02.02` | _Plastic and tulle parachute_ |
| `Beaufort-03.01` | _Small chute deployment bag_ |
| `Beaufort-03.03` | _0.75m round ripstop nylon parachute_ |
| `Beaufort-03.05` | _1m cruciform ripstop nylon parachute_ |
| `Beaufort-90.01` | _1m ram air parachute (3rd party design-build) tests_ |
| :arrow_right: **`PROJECT CANTAL`** | **Cylindrical freefall devices; integrated parachutes/payloads (250g)**: | [PAR-Aero-Cantal](https://github.com/cpknight/PAR-Aero-Cantal) |
| `Cantal-0.1` | _Materials and structure test (Beaufort 03.03 chute, no payload)_ |
| `Cantal-0.3` | _Small diameter materials and structure test (no chute, no payload)_ |
| `Cantal-0.5` | _185mm diameter cylindrical payload enclosure (static chute)_ |
|              |  + _(reference payload bay and payload designs)_              |
| :arrow_right: **`PROJECT GARONNE`** | **ISRbot autonomous aerial imagery exploitation platform**: | [PAR-Aero-Garonne](https://github.com/cpknight/PAR-AERO-Garonne) |
| `Garonne-0.1` | _ISRbot platform designs._ |
| `Garonne-0.5` | _ISRbot exploitation software demonstrator I._ |
| `Garonne-0.6` | _ISRbot exploitation software demonstrator II._ |
| :arrow_right: **`PROJECT SARTHE`** | **Aerial Recce Convolutional Neural Networks (CNNs)**: | [PAR-Aero-Sarthe](https://github.com/cpknight/PAR-Aero-Sarthe) |
| `Sarthe-NN04` | Recognition/detection of roads, vehicles, intersections (Oblique EO/rgb; 10cm to 1m GSD). | [PAR-Aero-Sarthe-PAR-04](https://github.com/cpknight/PAR-Aero-Sarthe-PAR-04) |
| `Sarthe-NN05` | Recognition/detection of roads, vehicles, intersections (Vertical EO/rgb; 10cm to 1m GSD). | [PAR-Aero-Sarthe-PAR-05](https://github.com/cpknight/PAR-Aero-Sarthe-PAR-05) |
| `Sarthe-NN06` | Recognition/detection of combatant/non-combatant items of interest (Oblique EO/rgb 10cm to 50cm GSD). | [PAR-Aero-Sarthe-PAR-06](https://github.com/cpknight/PAR-Aero-Sarthe-PAR-06) |
| `Sarthe-NN07` | Recognition/detection of combatant/non-combatant items of interest (Vertical EO/rgb 50cm to 1m GSD). | [PAR-Aero-Sarthe-PAR-07](https://github.com/cpknight/PAR-Aero-Sarthe-PAR-07) |
| `Sarthe-NN08` | Recognition/detection of downed aircraft from sub-optimal data (Vertical EO/rgb 50cm to 1m GSD). | [PAR-Aero-Sarthe-PAR-08](https://github.com/cpknight/PAR-Aero-Sarthe-PAR-08) |
| `Sarthe-NN09` | Detection of active wildfires (Vertical EO/rgb 50cm to 1m GSD). | [PAR-Aero-Sarthe-PAR-09](https://github.com/cpknight/PAR-Aero-Sarthe-PAR-09) |
| `Sarthe-NN0B` | Recognition/detection of pipelines, compressor stations, extraction sites (Vertical EO/rgb 10cm to 1m GSD). | [PAR-Aero-Sarthe-PAR-0B](https://github.com/cpknight/PAR-Aero-Sarthe-PAR-0B) |
| `Sarthe-NN0C` | Recognition/detection of transmission lines, generating stations, substations (Vertical EO/rgb 10cm to 1m GSD). | [PAR-Aero-Sarthe-PAR-0C](https://github.com/cpknight/PAR-Aero-Sarthe-PAR-0C) |
| `Sarthe-NN0E` | Recognition/detection for active wildfire operations (Vertical EO/rgb 10cm to 1m GSD). | [PAR-Aero-Sarthe-PAR-0E](https://github.com/cpknight/PAR-Aero-Sarthe-PAR-0E) |
| `Sarthe-NN0F` | Recognition/detection of "built" infrastructure in wilderness locations (Oblique EO/rgb 10cm to 50cm GSD). | [PAR-Aero-Sarthe-PAR-0F](https://github.com/cpknight/PAR-Aero-Sarthe-PAR-0F) |
| `Sarthe-NN10` | Recognition/detection of built aircraft landing sites (Vertical EO/rgb 10cm to 50cm GSD). | [PAR-Sarthe-NN10](https://github.com/cpknight/PAR-Sarthe-NN10) |
| :arrow_right: **`PROJECT VOSGES`** | **Paro MVP Payload Devices**: | [PAR-Aero-Vosges](https://github.com/cpknight/PAR-Aero-Vosges) |
| `Vosges-Mainboard` | Base mainboard pcb and firmware with ESP32-CAM. | [PARO-Vosges-Mainboard](https://github.com/cpknight/PARO-Vosges-Mainboard) |
| `Vosges-Case` | Case 3D Design. | [PARO-Vosges-Case](https://github.com/cpknight/PARO-Vosges-Case) |
| :arrow_right: **`PROJECT NAME`** | **Project Description**: | [PAR-Aero-Reponame](https://github.com/cpknight/PAR-AERO-Reponame) |
| `` | _Lorem_ |
| `` | _Lorem_ |
| `` | _Lorem_ |
| `` | _Lorem_ |
| `12345678901234567890` | (_This row included just to force MD spacing on GitHub..._) | `123456789012345678901234567890` |



