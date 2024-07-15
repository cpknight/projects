## Device Design and Development Projects
:information_source: This is the master index for my device design projects and, where applicable, corresponding Github repos.
  
| Project      | Summary                                                         | Github Repo                                                         | :clock10: |
| :----------- | :-------------------------------------------------------------- | :------------------------------------------------------------------ | :----: |
| :arrow_right: **`AIN`** | **Freefall/parachute data capture**. | [`Ain`](https://github.com/cpknight/Ain) | |
| :arrow_right: **`ALPES`**  | **Freefall data capture**. | [`Alpes`](https://github.com/cpknight/Alpes) | |
| :arrow_right: **`AUBE`** | **Freefall/parachute devices**. | [`Aube`](https://github.com/cpknight/Aube) | |
| :arrow_right: **`VEYRON`** | **Remote aerial vehicles**. | [`Aveyron`](https://github.com/cpknight/Aveyron) | |
| :arrow_right: **`BEAUFORT`** | **Small parachutes**. | [`Beaufort`](https://github.com/cpknight/Beaufort)  | |
| :arrow_right: **`CANTAL`** | **Cylindrical freefall** devices. | [`Cantal`](https://github.com/cpknight/Cantal) | :white_check_mark: |
| :arrow_right: **`DORDOGNE`** | **Common parts/subassemblies**. | [`Dordogne`](https://github.com/cpknight/Dordogne) | :white_check_mark: |
| :arrow_right: **`GARONNE`** | **Aerial imagery exploitation**. | `Garonne` | |
| :arrow_right: **`SARTHE`** | **Aerial recce neural networks**. | `Sarthe` | |
| :arrow_right: **`TARN`** | **Small-scale manufacturing** (meta). | [`Tarn`](https://github.com/cpknight/Tarn) | :white_check_mark: |
| :arrow_right: **`VOSGES`** | **Paro devices**: | [`Vosges`](https://github.com/cpknight/Vosges) | :white_check_mark: |
| | _Base mainboard PCB/firmware_. | [`Vosges-Mainboard`](https://github.com/cpknight/Vosges-Mainboard) | :white_check_mark: |
| | _Enclosure 3D design_. | [`Vosges-Enclosure`](https://github.com/cpknight/Vosges-Enclosure) | :white_check_mark: |
| | _End-user documentation_. | [`Paro`](https://github.com/cpknight/Paro) | :white_check_mark: |
| :arrow_right: **`YONNE`** | **Digital clock devices**. | [`Yonne`](https://github.com/cpknight/Yonne) | :white_check_mark: |

- Each project will correspond to a Github repository, while each sub-project will correspond to _either_ (i) a top-level directory in those repositories, _or_ (ii) a separate repository for the sub-project. 
- Projects are named after départements of France, and may correspond to any aspect of device design and prototyping component or development stage, eg: airframes, parachutes, hardware, software, or tactics.
- See the [`Tarn`](https://github.com/cpknight/Tarn) project for small-scale production (manufacturing) of some of these projects. 
- If you need access, contact [`@cpknight`](https://github.com/cpknight) with your Github username for access to the repository that you're working on – many of these repositories make use of [`Git Large File Storage`](https://git-lfs.github.com/), so please also enable that extension on your system. 

<!-- OLD INDEX:

| :arrow_right: **`PROJECT AIN`** | **Freefall/parachute data capture devices (500g)**: | [`Ain`](https://github.com/cpknight/Ain) |
| :black_small_square: `Ain-0.1`    | _Cardboard RPi freefall state machine: data capture._ | 
| :black_small_square: `Ain-0.1arp` | _Freefall state machine: Arduino RP2040 (Pico) port._ |
| :black_small_square: `Ain-0.3`    | _Cardboard RPi freefall state machine: servo chute deployment._ |
| :black_small_square: |  |  |
| :arrow_right: **`PROJECT ALPES`**  | **Freefall data capture devices (100g)**: | [`Alpes`](https://github.com/cpknight/Alpes) |
| :black_small_square: `Alpes-0.1` | _Materials and structure concept test (RPi Zero simulated payload)._ |
| :black_small_square: |  |  |
| :arrow_right: **`PROJECT AUBE`** | **Freefall/parachute aerial recce payload devices (500g)**: | [`Aube`](https://github.com/cpknight/Aube) |
| :black_small_square: `Aube-0.1` | _Static chute foil tape cardboard construction wtih digital camera payload._ |
| :black_small_square: `Aube-0.3` | _Static chute cardboard construction with RPi RF data capture payload. (Aube 0.5 Freefall State Machine forked from Ain 0.1)._ |
| :black_small_square: `Aube-0.5` | _Static chute foamcore construction with RPi sensor data capture payload. (Aube 0.5 Freefall State Machine forked from Ain 0.3)._ |
| :black_small_square: `Aube-0.7` | _Integrated chute deployment with RPi control and sensor payload._ |
| :black_small_square: |  |  |
| :arrow_right: **`PROJECT AVEYRON`** | **Flying wing autonomous aerial vehicles.**: | [`Aveyron`](https://github.com/cpknight/Aveyron) |
| :black_small_square: `Aveyron-0.1-X1a` | _Micro RPAS flight demonstrator I (Micro Flying Wing; 250g)_ |
| :black_small_square: `Aveyron-0.1-X1b` | _Micro RPAS flight demonstrator I (Micro Gliding Wing; 250g)_ |
| :black_small_square: `Aveyron-0.1-X2` | _Micro RPAS flight demonstrator I (Mini Flying Wing; 280g)_ |
| :black_small_square: `Aveyron-0.1-X3` | _RPAS flight demonstrator (Stable Mini Airfoil; 350g)_ |
| :black_small_square: `Aveyron-1.0ɑ` | _Autonomous ground-launch Flying Wing with integrated Cantal payload bay._ |
| :black_small_square: `Aveyron-1.0β` | _Autonomous ground-launch Flying Wing, initial production kit._ |
| :black_small_square: |  |  |
| :arrow_right: **`PROJECT BEAUFORT`** | **Small parachutes and deployment devices**: | [`Beaufort`](https://github.com/cpknight/Beaufort)  |
| :black_small_square: `Beaufort-02.01` | _Plastic bag parachute_ |
| :black_small_square: `Beaufort-02.02` | _Plastic and tulle parachute_ |
| :black_small_square: `Beaufort-03.01` | _Small chute deployment bag_ |
| :black_small_square: `Beaufort-03.03` | _0.75m round ripstop nylon parachute_ |
| :black_small_square: `Beaufort-03.05` | _1m cruciform ripstop nylon parachute_ |
| :black_small_square: `Beaufort-90.01` | _1m ram air parachute (3rd party design-build) tests_ |
| :black_small_square: |  |  |
| :arrow_right: **`PROJECT CANTAL`** | **Cylindrical freefall devices; integrated parachutes/payloads (250g)**: | [`Cantal`](https://github.com/cpknight/Cantal) |
| :black_small_square: `Cantal-0.1` | _Materials and structure test (Beaufort 03.03 chute, no payload)_ |
| :black_small_square: `Cantal-0.3` | _Small diameter materials and structure test (no chute, no payload)_ |
| :black_small_square: `Cantal-0.5` | _185mm diameter cylindrical payload enclosure (static chute)_ |
| :black_small_square: `Cantal-1.0` | _185mm payload enclosure and reference payload design_ |
| :black_small_square: `Cantal-1.5` | _185mm payload enclosure and reference payload design_ |
| :black_small_square: `Cantal-1.6` | _185mm payload enclosure and reference payload design_ |
| :black_small_square: |  |  |
| :arrow_right: **`PROJECT DORDOGNE`** | **Common Sub-Assemblies and Parts** to other projects. | [`Dordogne`](https://github.com/cpknight/Dordogne) |
| :arrow_right: **`PROJECT GARONNE`** | **ISRbot autonomous aerial imagery exploitation platform**: | [`Garonne`](https://github.com/cpknight/Garonne) |
| :black_small_square: `Garonne-0.1` | _ISRbot platform designs._ | |
| :black_small_square: `Garonne-0.5` | _ISRbot exploitation software demonstrator I._ | |
| :black_small_square: `Garonne-0.6` | _ISRbot exploitation software demonstrator II._ | |
| :black_small_square: `Garonne-Exp` | _Experimental algorithms and processing._ | [`PAR-Garonne-Experimental`](https://github.com/cpknight/PAR-Garonne-Experimental) |
| :black_small_square: |  |  |
| :arrow_right: **`PROJECT SARTHE`** | **Aerial Recce Convolutional Neural Networks (CNNs)**: | [`Sarthe`](https://github.com/cpknight/Sarthe) |
| :black_small_square: `Sarthe-NN04` | Recognition/detection of roads, vehicles, intersections (Oblique EO/rgb; 10cm to 1m GSD). | [`Sarthe-PAR-04`](https://github.com/cpknight/Sarthe-PAR-04) |
| :black_small_square: `Sarthe-NN05` | Recognition/detection of roads, vehicles, intersections (Vertical EO/rgb; 10cm to 1m GSD). | [`Sarthe-PAR-05`](https://github.com/cpknight/Sarthe-PAR-05) |
| :black_small_square: `Sarthe-NN06` | Recognition/detection of combatant/non-combatant items of interest (Oblique EO/rgb 10cm to 50cm GSD). | [`Sarthe-PAR-06`](https://github.com/cpknight/Sarthe-PAR-06) |
| :black_small_square: `Sarthe-NN07` | Recognition/detection of combatant/non-combatant items of interest (Vertical EO/rgb 50cm to 1m GSD). | [`Sarthe-PAR-07`](https://github.com/cpknight/Sarthe-PAR-07) |
| :black_small_square: `Sarthe-NN08` | Recognition/detection of downed aircraft from sub-optimal data (Vertical EO/rgb 50cm to 1m GSD). | [`Sarthe-PAR-08`](https://github.com/cpknight/Sarthe-PAR-08) |
| :black_small_square: `Sarthe-NN09` | Detection of active wildfires (Vertical EO/rgb 50cm to 1m GSD). | [`Sarthe-PAR-09`](https://github.com/cpknight/Sarthe-PAR-09) |
| :black_small_square: `Sarthe-NN0B` | Recognition/detection of pipelines, compressor stations, extraction sites (Vertical EO/rgb 10cm to 1m GSD). | [`Sarthe-PAR-0B`](https://github.com/cpknight/Sarthe-PAR-0B) |
| :black_small_square: `Sarthe-NN0C` | Recognition/detection of transmission lines, generating stations, substations (Vertical EO/rgb 10cm to 1m GSD). | [`Sarthe-PAR-0C`](https://github.com/cpknight/Sarthe-PAR-0C) |
| :black_small_square: `Sarthe-NN0E` | Recognition/detection for active wildfire operations (Vertical EO/rgb 10cm to 1m GSD). | [`Sarthe-PAR-0E`](https://github.com/cpknight/Sarthe-PAR-0E) |
| :black_small_square: `Sarthe-NN0F` | Recognition/detection of "built" infrastructure in wilderness locations (Oblique EO/rgb 10cm to 50cm GSD). | [`Sarthe-PAR-0F`](https://github.com/cpknight/Sarthe-PAR-0F) |
| :black_small_square: `Sarthe-NN10` | Recognition/detection of built aircraft landing sites (Vertical EO/rgb 10cm to 50cm GSD). | [`PAR-Sarthe-NN10`](https://github.com/cpknight/PAR-Sarthe-NN10) |
| :black_small_square: |  |  |
| :arrow_right: **`PROJECT TARN`** | **Small Scale Manufacturing**: Production Systems and Logistics. | [`Tarn`](https://github.com/cpknight/Tarn) |
| :arrow_right: **`PROJECT VOSGES`** | **Paro MVP Payload Devices**: | [`Vosges`](https://github.com/cpknight/Vosges) |
| :black_small_square: `Vosges-Mainboard` | Base mainboard pcb and firmware with ESP32-CAM. | [`PARO-Vosges-Mainboard`](https://github.com/cpknight/PARO-Vosges-Mainboard) |
| :black_small_square: `Vosges-Case` | Case 3D Design. | [`PARO-Vosges-Case`](https://github.com/cpknight/PARO-Vosges-Case) |
| :black_small_square: `Paro` | End-User Documentation. | [`Paro`](https://github.com/cpknight/Paro) |
| :black_small_square: |  |  |
| :arrow_right: **`PROJECT YONNE`** | **GNSS Clock Devices** | [`Yonne`](https://github.com/cpknight/Yonne) |
| :black_small_square: |  |  |

-->



