[:octocat:](https://github.com) / [`cpknight`](https://github.com/cpknight) / [`projects`](/)

## Projects

:information_source: This repo is simply an index of projects (and their repos) related to the [reconnaissance devices](#reconnaissance-device-design-and-development-projects) that I'm working on, as well as a second table listing [miscellaneous](#miscellaneous-projects) projects. Projects with open source content are indicated with :unlock: unlocked lock' emoji, and your should be able to access these directly. For access to :lock: locked project materials, or for any other reason, please :envelope: [contact me](mailto:chris@cpknight.io).

  
### Reconnaissance Device (Design and Development) Projects

| PDLC                    | Project/Repo                                                                  | Description                          | Activty          |    
| :---------------------- | :-----------------------------------------------------------------------------| :----------------------------------- | :--------------: | 
| Research                | :lock: [**`Ain`**](https://github.com/cpknight/Ain)                           | Freefall/parachute data capture.     | :black_circle:   | 
| Research                | :lock: **`Garonne`**                                                          | Aerial imagery exploitation methods. | :black_circle:   |  
| Research                | :lock: [**`Aveyron`**](https://github.com/cpknight/Aveyron)                   | Small remote aerial vehicles.        | :black_circle:   |
| Research/Prototyping    | :lock: **`Sarthe`**                                                           | Aerial recce CNN design and training.| :black_circle:   |
| Research/Prototyping    | :lock: [**`Alpes`**](https://github.com/cpknight/Alpes)                       | Freefall data capture experiments.   | :orange_circle:  |  
| Research/Prototyping    | :lock: [**`Aube`**](https://github.com/cpknight/Aube)                         | Freefall/parachute devices.          | :orange_circle:  |
| Research/Prototyping    | :lock: [**`Beaufort`**](https://github.com/cpknight/Beaufort)                 | Small parachute designs.             | :orange_circle:  |
| Prototyping/Design      | :lock: [**`Cantal`**](https://github.com/cpknight/Cantal)                     | Cylindrical freefall devices.        | :orange_circle:  |
| Prototyping/Design      | :lock: [**`Gironde`**](https://github.com/cpknight/Gironde)                   | POE Ethernet recce hard/firmware.    | :green_circle:   |
| Design/Production       | :lock: [**`Tarn`**](https://github.com/cpknight/Tarn)                         | Small batch device production system.| :green_circle:   |
| Design/Production       | :lock: [**`Dordogne`**](https://github.com/cpknight/Dordogne)                 | Common parts/sub-assemblies.         | :green_circle:   |
| Design/Production       | :lock: [**`Drôme`**](https://github.com/cpknight/Drome)                       | Next-generation device power PCB.    | :green_circle:   |
| Design/Production       | :lock: [**`Vosges`**](https://github.com/cpknight/Vosges)                     | "Paro" device design and production. | :green_circle:   |
| Design/Production       | :lock: [`Vosges-Enclosure`](https://github.com/cpknight/Vosges-Enclosure)     | "Paro" Cantal-compatable enclosure.  | :green_circle:   |
| Design/Production       | :lock: [`Vosges-Mainboard`](https://github.com/cpknight/Vosges-Mainboard)     | "Paro" mainboard PCB and G0 firmware.| :green_circle:   |
| Design/Production       | :lock: [`Vosges-Firmware-G1`](https://github.com/cpknight/Vosges-Firmware-G1) | "Paro" Gen1 firmware (`PlatformIO`). | :green_circle:   |
| Design/Production       | :lock: [`Vosges-Firmware-G2`](https://github.com/cpknight/Vosges-Firmware-G2) | "Paro" Gen2 firmware (`ESP-IDF`).    | :green_circle:   |
| Design/Production       | :lock: `Vosges-Management`                                                    | "Paro" CLI, web, and admin control.<sup>2</sup> | :green_circle: |
| Design/Production       | :lock: [**`Yonne`**](https://github.com/cpknight/Yonne)                       | Digital satellite/network clocks.    | :green_circle:   |
| Design/Production       | :lock: [**`Eure`**](https://github.com/cpknight/Eure)                         | Sensor assemblies (PCB and firmware).| :green_circle:   |

_Notes_:
1. Reconnaissance projects are named after départements of France, and may correspond to any aspect of device design and prototyping component or development stage, eg: airframes, parachutes, hardware, software, or tactics.
2. Projects will generally span 1 or two PDLC phases. The approach/phases I use for rapid prototyping and iterative design/production is: `Research` :arrows_counterclockwise: `Prototyping` :arrows_counterclockwise: `Design` :arrows_counterclockwise: `Production`. Where applicable, `Design` phases include `Testing` and `Certification` sub-phases; and `Production` phases include `QA/QC` sub-phases. 
3. The `Vosges-Management` sub-project is to be consolidated, and includes `aws-iot-test`, [`Website-Reconnaissance-Services`](https://github.com/cpknight/Website-Reconnaissance-Services), and [`Paro`](https://github.com/cpknight/Paro) (user documentation).
4. If you need access to a :lock: repo, contact [`@cpknight`](https://github.com/cpknight) with your Github username for access to the repository that you're collaborating on. :open_book: Open repos should automatically let you fork or view/download whatever you need.
5. Many of these repositories make use of [`Git Large File Storage`](https://git-lfs.github.com/), so please also enable that extension on your system. 

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

### Miscellaneous Projects

| Category                | Project/Repo                                                                  | Description                               | Activty          |    
| :---------------------- | :-----------------------------------------------------------------------------| :---------------------------------------- | :--------------: |
| Utility                 | :open_book: [**`digicam-rtsp`**](https://github.com/cpknight/digicam-rtsp)    | Stream `rtsp` from `gphoto2` digicams.    | :green_circle:   |
| Experimental            | :stopwatch: Proton Email Automation                                           | Proton Email Automation.                  | :green_circle:   |
| Preliminary             | :open_book: [**`Sisu`**](https://github.com/cpknight/Sisu)                    | Vintage electronic device restoration.    | :green_circle:   |
| Preliminary             | :stopwatch: **Torch**                                                         | Restoring vintage typewriters to glory.   | :green_circle:   |
| Preliminary             | :stopwatch: **Tricorn**                                                       | WiFi retrofit kit for Selectric printers. | :green_circle:   |
| Preliminary             | :stopwatch: **Envoy**                                                         | (Digital Cameras)                         | :green_circle:   |
| Preliminary             | :stopwatch: **Hydra**                                                         | (WiFi Routers)                            | :green_circle:   |
| Preliminary             | :stopwatch: **Dora**                                                          | (RJ45 Ethernet)                           | :green_circle:   |
| Preliminary             | :stopwatch: **Tours**                                                         | (SIP Telephony)                           | :green_circle:   |
| Preliminary             | :stopwatch: **Asgard**                                                        | (RS-232 / TTL / USB Serial)               | :green_circle:   |
| Preliminary             | :stopwatch: **Gremlin**                                                       | (RPAS/UAV Drones)                         | :green_circle:   |
| Preliminary             | :stopwatch: **Minerva**                                                       | (SBC Devices)                             | :green_circle:   |
| Preliminary             | :stopwatch: **Vanguard**                                                      | (A/V Devices)                             | :green_circle:   |
| Preliminary             | :stopwatch: **Infinity**                                                      | (Amateur Radio)                           | :green_circle:   |
| Preliminary             | :stopwatch: **Nautilus**                                                      | (Magnetic Optical Media)                  | :green_circle:   |
| Preliminary             | :stopwatch: **Polestar**                                                      | (IoT & Electrics 120V/240V 50/60Hz, &c.)  | :green_circle:   |
| Preliminary             | :stopwatch: **XXX**                                                           | (XXX)                                     | :green_circle:   |

<!-- 

NOTE

Project Torch
Description: Electro-mechanical typewriter restoration/refurbishment, focusing on IBM Selectrics, Adler, and Brother machines. Also Olympia mechanicals.
Rationale: Named after the “torchship” from Heinlein’s Double Star, evoking the power and precision of restoring vintage typewriters to full function.

Project Tricorn
Description: Development of a new-generation actuator solution/kit to retrofit IBM Selectrics into WiFi-enabled line printers.
Rationale: Inspired by the Raven from The Moon is a Harsh Mistress, symbolizing the sleek, advanced tech that modernizes classic machines.

Schema
Use single-word spaceship names from Robert A. Heinlein’s universe (e.g., Hawk, Dart, Star, Flame, Scout) for project codenames.

-->

### Starship Projecct Name Table

|  X  | Name        | Description                                                           | Source                                                           |
| :-: |-------------|-----------------------------------------------------------------------|------------------------------------------------------------------|
|  X  | Dora        | Intelligent spaceship used in multiverse adventures.                  | Novel: The Number of the Beast (Robert A. Heinlein)              |
|  X  | Sisu        | Family-owned free trader spaceship in interstellar commerce.          | Novel: Citizen of the Galaxy (Robert A. Heinlein)                |
|  X  | Torch       | High-thrust interstellar spaceship using torch drive for exploration. | Novel: Time for the Stars (Robert A. Heinlein)                   |
|  X  | Envoy       | Exploration vessel to Mars.                                           | Novel: Stranger in a Strange Land (Robert A. Heinlein)           |
|  X  | Tours       | Troop transport in interstellar wars.                                 | Novel: Starship Troopers (Robert A. Heinlein)                    |
|  X  | Hydra       | Military cruiser in interstellar operations.                          | Novel: Citizen of the Galaxy (Robert A. Heinlein)                |
|  X  | Asgard      | Passenger starship, formerly the Einstein, for interstellar travel.   | Novel: Starman Jones (Robert A. Heinlein)                        |
|  X  | Tricorn     | Passenger liner traveling to Venus and Mars.                          | Novel: Podkayne of Mars (Robert A. Heinlein)                     |
|  X  | Gremlin     | Spacecraft in orbital operations.                                     | Short story: “Space Jockey” (Robert A. Heinlein)                 |
|  X  | Minerva     | AI-controlled ship in alternate universes.                            | Novel: The Number of the Beast (Robert A. Heinlein)              |
|  X  | Vanguard    | Generation ship whose inhabitants forgot their mission.               | Novel: Orphans of the Sky (Robert A. Heinlein)                   |
|  X  | Infinity    | Faster-than-light exploration vessel.                                 | Novel: Time for the Stars (Robert A. Heinlein)                   |
|  X  | Nautilus    | Torchship for relativistic interstellar exploration.                  | Novel: Time for the Stars (Robert A. Heinlein)                   |
|  X  | Polestar    | Construction ship in space station building.                          | Short story: “Delilah and the Space Rigger” (Robert A. Heinlein) |
|     | Valkyrie    | Ship involved in space ordeal.                                        | Short story: “Ordeal in Space” (Robert A. Heinlein)              |
|     | Champion    | Ship that transported the Martian to Earth.                           | Novel: Stranger in a Strange Land (Robert A. Heinlein)           |
|     | Wanderlust  | Passenger ship for interplanetary travel.                             | Novel: Podkayne of Mars (Robert A. Heinlein)                     |
|     | Serendipity | Exploration torchship seeking new worlds.                             | Novel: Time for the Stars (Robert A. Heinlein)                   |
