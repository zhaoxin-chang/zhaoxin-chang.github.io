---
layout: archive
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Bio
======
I am a second-year PhD student at [Institut Polytechnique de Paris (IP Paris)](https://www.ip-paris.fr/en), advised by Prof. [Daqing Zhang](https://scholar.google.com.hk/citations?hl=en&user=qn8CqEYAAAAJ&view_op=list_works&sortby=pubdate) and Prof. [Badii Jouaber](https://badiijouaber.wp.imtbs-tsp.eu/en/biography/). I received my B.S. degree from [Peking University](https://english.pku.edu.cn/) in 2020 and my M.S. degree from [IP Paris](https://www.ip-paris.fr/en) in 2023.

Research Interests
======
I am interested in wireless sensing and mobile computing for health monitoring and human-computer interaction. My research focuses on addressing key challenges in wireless sensing to bridge the gap between wireless sensing theories and real-world development.

News
======

- **Apr 2025** One paper accepted at IEEE TMC
- **Apr 2025** Serve on MobiCom 2025 Artifacts Evaluation Committee
- **Feb 2025** One paper accepted at IEEE TMC


Awards and Honors
======

- **AIoTSys 2025** Best Paper Award
- **MobiCom 2022** Best Paper Award Runner-up
- **MobiCom 2022** Best Community Paper Award Runner-up
- **MobiCom 2022** Student Travel Grant
- **IPIN 2021** Indoor Positioning Competition, Winner
- **IMWUT Vol. 4 (UbiComp 2020)** Distinguished Paper Award

Selected Publications
======

- [WiCG: In-Body Cardiac Motion Sensing Based on a Mix-Medium Wi-Fi Fresnel Zone Model.](https://ieeexplore.ieee.org/document/10978106)\
  *Pei Wang, Anlan Yu, Xujun Ma, Rong Zheng, Jingfu Dong, <strong>Zhaoxin Chang</strong>, Duo Zhang, Djamal Zeghlache, Daqing Zhang.*\
  **IEEE Transactions on Mobile Computing, 2025** (Early Access)
  <details>
    <summary>Abstract</summary>
    <div style="font-size: smaller;">
    Cardiovascular diseases (CVDs) are a leading cause of mortality worldwide, highlighting the critical need for accurate and continuous heart health monitoring. Electrocardiograms (ECG), considered as the golden standard for diagnosing and monitoring heart-related conditions, offer precise measurements but require direct skin contact, limiting their practicality for long-term and everyday use. On the other hand, existing RF sensing techniques that analyze signals reflected off the skin struggle to distinguish micro cardiac motions of the heart due to weak motion amplitude and respiration interference at the chest wall. To overcome these limitations, we introduce WiCG, a novel contact-less cardiac motion monitoring system that employs 2.4 GHz Wi-Fi signals to penetrate the chest and detect subtle cardiac movements. A mix-medium Wi-Fi Fresnel zone model is developed to explain the enhanced phase sensitivity of in-body Wi-Fi signals, which is crucial for accurately detecting cardiac motions. By strategically positioning antennas near the heart, WiCG captures ventricular motions effectively. A novel cardiac Doppler method is proposed to suppress phase noise and interference from static paths and extract the time interval between the systole and diastole of the ventricular. Extensive experiments demonstrate that the proposed system can robustly estimate the R-R and Q-T intervals of human cardiac cycles across 21 subjects and different environments with an average accuracy of 99.22% and 92.8%, achieving performance comparable to ECG.
      </div>
  </details>

- [mmRotation: Unlocking Versatility of a Single mmWave Radar via Azimuth Panning and Elevation Tilting.](https://ieeexplore.ieee.org/document/10878446)\
  *Duo Zhang, Xusheng Zhang, Zhehui Yin, Yaxiong Xie, Wen He, **Zhaoxin Chang**, Wenwei Li, Daqing Zhang.*\
  **IEEE Transactions on Mobile Computing, Vol. 24, No. 7**
  <details>
    <summary>Abstract</summary>
    <div style="font-size: smaller;">
    Indoor mmWave-based sensing technologies have garnered substantial interest from both the industrial and academic. Yet, the intrinsic challenge posed by the limited Field-of-View (FOV) of mmWave radars significantly restricts their coverage. This limitation necessitates careful selection of installation positions and orientations to optimize performance, thereby severely curtailing the versatility and widespread adoption of these systems. Traditionally, expanding coverage involved increasing the number of radar units. This paper introduces a novel approach to enhance the FOV by incorporating mobility, achieved by affixing the radar onto a pan-tilt unit capable of rotating along both the horizontal and azimuthal. Nevertheless, the disparity between the pan-tilt and the radar presents significant challenges for accurately rotating the radar's orientation. To mitigate this, we propose an automated calibration algorithm for radar and pan-tilt, ensuring precise calibration. Additionally, we have devised a radar orientation adjustment algorithm intended to automatically align the radar's FOV with the positions of detected objects to facilitate various applications. Through three case studies, we have demonstrated that mmRotation can greatly expand the sensing range, enabling support for multiple applications on a single radar, such as vital signs monitoring and fall detection. Comprehensive experimental results underscore that our system surpasses the current state-of-the-art (SOTA).
      </div>
  </details>

- [MmECare: Enabling Fine-grained Vital Sign Monitoring for Emergency Care with Handheld MmWave Radars.](https://doi.org/10.1145/3699766)\
  *<strong>Zhaoxin Chang</strong>, Fusang Zhang, Xujun Ma, Pei Wang, Weiyan Chen, Duo Zhang, Badii Jouaber, Daqing Zhang.* \
  **ACM IMWUT Vol. 8/UbiComp 2025**
  <details>
    <summary>Abstract</summary>
      <p align="center">
        <img src="/files/mmecare.png" alt="图片描述" width="700px">
      </p>
    <div style="font-size: smaller;">
    Fine-grained vital sign monitoring in emergency care is crucial for accurately assessing patient conditions, predicting disease progression, and formulating effective rescue plans. In non-hospital settings, limited equipment often necessitates manual observation of respiration and heartbeat, which can lead to significant errors. Contactless monitoring using wireless signals offers a promising alternative. Unlike traditional systems that require stationary devices for contactless sensing, handheld devices are more practical for rescuers during emergency care. However, sensing performance can be severely compromised by involuntary hand movements. Previous research has achieved respiration monitoring with handheld devices, but the randomness of hand motion still prevents reliable heartbeat monitoring. In this paper, we first demonstrate that the key to mitigating the effects of device motion lies in accurately estimating the motion direction. We then introduce a novel method that uses two static objects, i.e., corner reflectors, to precisely estimate the random motion direction of the device. These reflectors can be quickly and easily deployed by the rescuer before initiating vital sign monitoring, enabling a more thorough elimination of device motion effects. Comprehensive experiments validate the effectiveness of our solution using mmWave radar. Real-world tests demonstrate that our system can accurately monitor both respiration and heartbeat with handheld devices, significantly enhancing emergency medical response by improving the accuracy and feasibility of vital sign monitoring in urgent situations.
      </div>
  </details>

- [UWBOri: Enabling Accurate Orientation Estimation with Ultra-wideband Signals.](https://ieeexplore.ieee.org/document/10925144)\
  *<strong>Zhaoxin Chang</strong>, Fusang Zhang, Jie Xiong, Xinyu Xue, Zeyu Wang, Badii Jouaber, Daqing Zhang.* \
  **IEEE UIC 2024**
  <details>
    <summary>Abstract</summary>
      <p align="center">
        <img src="/files/uwbori.png" alt="图片描述" width="700px">
      </p>
    <div style="font-size: smaller;">
    The development of smart devices has highlighted the need for human-device interaction. A key aspect of this interaction lies in the estimation of the physical orientation of the device, which is crucial for various applications. Conventional methods employing Inertial Measurement Units (IMU) encounter limitations such as cumulative errors and magnetic interference. In this paper, we propose UWBOri, a novel method for orientation estimation using Ultra-wideband (UWB) technology. UWB technology, which is increasingly integrated into smart devices, offers superior ranging accuracy owing to its large bandwidth. By leveraging the localization information obtained between a fixed UWB-equipped anchor device and the user device, UWBOri can accurately estimate the orientation of the user device. The efficacy of UWBOri has been validated through extensive laboratory experiments designed to evaluate the accuracy of orientation estimation. Furthermore, we demonstrate the practical applicability of UWBOri in two distinct scenarios: IoT device selection and augmented reality (AR). These applications illustrate the potential of our solution in real-world scenarios.
      </div>
  </details>

- [Demonstration of Multi-Target Wireless Sensing Using High-Scanning-Rate Coupled-Patch Antenna.](https://ieeexplore.ieee.org/abstract/document/10602751)\
  *Shuguang Xiao\*, **Zhaoxin Chang**\*, Jiachen Du, Ge Zhang, Amir K. Rashid, Yi Huang, Chaijie Duan, Daqing Zhang, Qingfeng Zhang. (\*Equal contribution)*\
  **IEEE Antennas and Wireless Propagation Letters, 23(11), 2024**
  <details>
    <summary>Abstract</summary>
      <p align="center">
        <img src="/files/FSA.png" alt="图片描述" width="500px">
      </p>
    <div style="font-size: smaller;">
    This paper proposes a frequency-diverse multi-target wireless sensing system for integrated sensing and communication (ISAC) applications. A coupled-patch antenna (CPA) with frequency-dependent beam scanning capability is employed as the key component for multi-target localization and respiration detection. Owing to the high scanning rate of 25.8° per 1% bandwidth, the designed CPA is able to continuously scan an angle range of 93° across broadside as frequency varies from 3.26 GHz to 3.38 GHz, which well fits the ISAC application in Sub-6 GHz frequency. Four examples are given to demonstrate the benefit of high-scanning-rate CPA for multi-target localization, respiration detection, and surrounding interference mitigation.
      </div>
  </details>

- [MSense: Boosting Wireless Sensing Capability Under Motion Interference.](https://dl.acm.org/doi/10.1145/3636534.3649350)\
  *<strong>Zhaoxin Chang</strong>, Fusang Zhang, Jie Xiong, Weiyan Chen, Daqing Zhang.* \
  **ACM MobiCom 2024** (Acceptance rate: 103/494 = 20.9%)
  <details>
    <summary>Abstract</summary>
      <p align="center">
        <img src="/files/MSense.png" alt="图片描述" width="500px">
      </p>
    <div style="font-size: smaller;">
    Wireless signals have been widely utilized for human sensing. However, wireless sensing systems face a fundamental limitation, i.e., the wireless device must keep static during the sensing process. Also, when sensing fine-grained human motions such as respiration, the human target is required to stay stationary. This is because wireless sensing relies on signal variations for sensing. When device is moving or human body is moving, the signal variation caused by the target area (e.g., chest for respiration sensing) is mixed with the signal variation induced by device or other body parts, failing wireless sensing. In this paper, we propose MSense, a general solution to deal with motion interference from wireless device and/or human body, moving wireless sensing one step forward towards real-life adoption. We establish the sensing model by taking both device motion and interfering body motion into consideration. By extracting the effect of body and device motions through pure signal processing, the motion interference can be removed to achieve accurate target sensing. Comprehensive experiments demonstrate the effectiveness of the proposed scheme. The achieved solution is general and can be applied to different sensing tasks involving both periodic and aperiodic motions.
      </div>
  </details>

- [Quantum Wireless Sensing: Principle, Design and Implementation.](https://dl.acm.org/doi/10.1145/3570361.3613258)\
  *Fusang Zhang, Beihong Jin, Zitong Lan, **Zhaoxin Chang**, Daqing Zhang, Yuechun Jiao, Meng Shi, Jie Xiong.*\
  **ACM MobiCom 2023** (Acceptance rate: 92/377=24.4%)
  <details>
    <summary>Abstract</summary>
    <p align="center">
        <img src="/files/quantum.png" alt="图片描述" width="800px">
    </p>
    <div style="font-size: smaller;">
    Recent years have witnessed a tremendous amount of interest in wireless sensing, i.e., instead of employing traditional sensors, wireless signal is utilized for sensing purposes. Contact-free wireless sensing has been successfully demonstrated using various RF signals such as WiFi, RFID, LoRa, and mmWave, enabling a large range of applications. However, limited by hardware thermal noise, the granularity of RF sensing is still relatively coarse. In this paper, instead of using the macro signal power/phase for sensing, we propose the first quantum wireless sensing system, which uses the micro energy level of atoms for sensing, improving the sensing granularity by an order of magnitude. The proposed quantum wireless sensing system is capable of utilizing a wide spectrum of frequencies (e.g., 2.4 GHz, 5 GHz and 28 GHz) for sensing. We demonstrate the superior performance of quantum wireless sensing with two widely-used signals, i.e., WiFi and 28 GHz millimeter wave. We show that quantum wireless sensing can push the sensing granularity of WiFi from millimeter level to sub-millimeter level and push the sensing granularity of millimeter wave to micrometer level.
      </div>
  </details>

- [Environment-aware Multi-person Tracking in Indoor Environments with MmWave Radars.](https://dl.acm.org/doi/10.1145/3610902)\
  *Weiyan Chen, Hongliu Yang, Xiaoyang Bi, Rong Zheng, Fusang Zhang, Peng Bao, **Zhaoxin Chang**, Xujun Ma, Daqing Zhang.*\
  **ACM IMWUT Vol. 7/UbiComp 2023**
  <details>
    <summary>Abstract</summary>
      <p align="center">
        <img src="/files/multitarget.png" alt="图片描述" width="800px">
      </p>
    <div style="font-size: smaller;">
    Device-free indoor localization and tracking using commercial millimeter wave radars have attracted much interest lately due to their non-intrusive nature and high spatial resolution. However, it is challenging to achieve high tracking accuracy due to rich multipath reflection and occlusion in indoor environments. Static objects with non-negligible reflectance of mmWave signals interact with moving human subjects and generate time-varying multipath ghosts and shadow ghosts, which can be easily confused as real subjects. To characterize the complex interactions, we first develop a geometric model that estimates the location of multipath ghosts given the locations of humans and static reflectors. Based on this model, the locations of static reflectors that form a reflection map are automatically estimated from received radar signals as a single person traverses the environment along arbitrary trajectories. The reflection map allows for the elimination of multipath and shadow ghost interference as well as the augmentation of weakly reflected human subjects in occluded areas. The proposed environment-aware multi-person tracking system can generate reflection maps with a mean error of 15.5cm and a 90-percentile error of 30.3cm, and achieve multi-person tracking accuracy with a mean error of 8.6cm and a 90-percentile error of 17.5cm, in four representative indoor spaces with diverse subjects using a single mmWave radar.
      </div>
  </details>

- [Embracing Consumer-level UWB-equipped Devices for Fine-grained Wireless Sensing.](https://dl.acm.org/doi/10.1145/3569487)\
  *Fusang Zhang, **Zhaoxin Chang**, Jie Xiong, Junqi Ma, Jiazhi Ni, Wenbo Zhang, Beihong Jin, Daqing Zhang.*\
  **ACM IMWUT Vol. 6/UbiComp 2023**
  <details>
    <summary>Abstract</summary>
      <p align="center">
        <img src="/files/uwb.png" alt="图片描述" width="500px">
      </p>
    <div style="font-size: smaller;">
    RF sensing has been actively exploited in the past few years to enable novel IoT applications. Among different wireless technologies, WiFi-based sensing is most popular owing to the pervasiveness of WiFi infrastructure. However, one critical issue associated with WiFi sensing is that the information required for sensing can not be obtained from consumer-level devices such as smartphones or smart watches. The commonly-seen WiFi devices in our everyday lives actually can not be utilized for sensing. Instead, dedicated hardware with a specific WiFi card (e.g., Intel 5300) needs to be used for WiFi sensing. This paper involves Ultra-Wideband (UWB) into the ecosystem of RF sensing and makes RF sensing work on consumer-level hardware such as smartphones and smart watches for the first time. We propose a series of methods to realize UWB sensing on consumer-level electronics without any hardware modification. By leveraging fine-grained human respiration monitoring as the application example, we demonstrate that the achieved performance on consumer-level electronics is comparable to that achieved using dedicated UWB hardware. We show that UWB sensing hosted on consumer-level electronics is able to achieve fine granularity, robustness against interference and also multi-target sensing, pushing RF sensing one step towards real-life adoption.
      </div>
  </details>

- [Mobi$^2$Sense: Empowering Wireless Sensing with Mobility.](https://dl.acm.org/doi/10.1145/3495243.3560518) <font color=red font-weight=bold>(Best Paper Award Runner-up)</font>\
  *Fusang Zhang, Jie Xiong, **Zhaoxin Chang**, Junqi Ma, Daqing Zhang.*\
  **ACM MobiCom 2022** (Acceptance rate: 56/314=17.8%)
  <details>
    <summary>Abstract</summary>
      <p align="center">
        <img src="/files/Mobi2Sense.png" alt="图片描述" width="500px">
      </p>
    <div style="font-size: smaller;">
    Besides the conventional communication function, wireless signals are actively exploited for sensing purposes recently. However, a missing component of existing wireless sensing is sensing under device motions. This is challenging because device motions can easily overwhelm target motions such as chest displacement used for respiration sensing. This paper takes a first step in the direction of involving device mobility into the ecosystem of wireless sensing. Owning to the miniaturization and low cost of ultra-wideband (UWB) chip in recent years, we propose to integrate the accuracy of UWB sensing with mobility to support truly ubiquitous wireless sensing. We propose Mobi2Sense, a system design to support sensing under device motions. We propose novel signal processing schemes to remove the effect of device motions on sensing and prototype Mobi2Sense using commodity UWB hardware. Real-world applications demonstrate that even in the presence of device motions, fine-grained Mobi2Sense is able to capture subtle target motions to "hear" music, "see" human respiration, and "recognize" multi-target gestures at a high accuracy.
    </div>
  </details>

- [Experience: Pushing Indoor Localization from Laboratory to the Wild.](https://dl.acm.org/doi/10.1145/3495243.3560546) <font color=red font-weight=bold>(Best Community Paper Award Runner-up)</font>\
  *Jiazhi Ni, Fusang Zhang, Jie Xiong, Qiang Huang, **Zhaoxin Chang**, Junqi Ma, Binbin Xie, Pengsen Wang, Guangyu Bian, Xin Li, Chang Liu.*\
  **ACM MobiCom 2022** (Acceptance rate: 56/314=17.8%)
  <details>
    <summary>Abstract</summary>
     <p align="center">
        <img src="/files/wifi.png" alt="图片描述" width="600px">
      </p>
    <div style="font-size: smaller;">
    While GPS-based outdoor localization has become a norm, very few indoor localization systems have been deployed and used. In this paper, we share our 5-year experience on the design, development and evaluation of a large-scale WiFi indoor localization system. We address practical challenges encountered to bridge the gap between indoor localization research in the laboratory and system deployment in the wild. The system is currently used in 1469 shopping malls, 393 office buildings and 35 hospitals across 35 cities to provide location service to millions of users on a daily basis. We hope the shared experience can benefit the design of real-world indoor localization systems and the practical problems identified can change the focus of indoor localization research. We released our dataset that contains fingerprints collected from 1469 shopping malls and one office building.
      </div>
  </details>

- [Sensor-free Soil Moisture Sensing Using LoRa Signals.](https://dl.acm.org/doi/10.1145/3534608)\
  *<strong>Zhaoxin Chang</strong>, Fusang Zhang, Jie Xiong, Junqi Ma, Beihong Jin, Daqing Zhang.* \
  **ACM IMWUT Vol. 6/UbiComp 2022**
  <details>
    <summary>Abstract</summary>
      <p align="center">
        <img src="/files/soil.png" alt="图片描述" width="500px">
      </p>
    <div style="font-size: smaller;">
    Soil moisture sensing is one of the most important components in smart agriculture. It plays a critical role in increasing crop yields and reducing water waste. However, existing commercial soil moisture sensors are either expensive or inaccurate, limiting their real-world deployment. In this paper, we utilize wide-area LoRa signals to sense soil moisture without a need of dedicated soil moisture sensors. Different from traditional usage of LoRa in smart agriculture which is only for sensor data transmission, we leverage LoRa signal itself as a powerful sensing tool. The key insight is that the dielectric permittivity of soil which is closely related to soil moisture can be obtained from phase readings of LoRa signals. Therefore, antennas of a LoRa node can be placed in the soil to capture signal phase readings for soil moisture measurements. Though promising, it is non-trivial to extract accurate phase information due to unsynchronization of LoRa transmitter and receiver. In this work, we propose to include a low-cost switch to equip the LoRa node with two antennas to address the issue. We develop a delicate chirp ratio approach to cancel out the phase offset caused by transceiver unsynchronization to extract accurate phase information. The proposed system design has multiple unique advantages including high accuracy, robustness against motion interference and large sensing range for large-scale deployment in smart agriculture. Experiments with commodity LoRa nodes show that our system can accurately estimate soil moisture at an average error of 3.1%, achieving a performance comparable to high-end commodity soil moisture sensors. Field studies show that the proposed system can accurately sense soil moisture even when the LoRa gateway is 100 m away from the LoRa node, enabling wide-area soil moisture sensing for the first time.
    </div>
  </details>
  
- [Unlocking the Beamforming Potential of LoRa for Long-range Multi-target Respiration Sensing.](https://dl.acm.org/doi/abs/10.1145/3463526)\
  *Fusang Zhang, **Zhaoxin Chang**, Jie Xiong, Rong Zheng, Junqi Ma, Kai Niu, Beihong Jin, Daqing Zhang.*\
  **ACM IMWUT Vol. 5/UbiComp 2021**
  <details>
    <summary>Abstract</summary>
      <p align="center">
        <img src="/files/beamforming.png" alt="图片描述" width="200px">
      </p>
    <div style="font-size: smaller;">
    Despite extensive research effort in contact-free sensing using RF signals in the last few years, there still exist significant barriers preventing their wide adoptions. One key issue is the inability to sense multiple targets due to the intrinsic nature of relying on reflection signals for sensing: the reflections from multiple targets get mixed at the receiver and it is extremely difficult to separate these signals to sense each individual. This problem becomes even more severe in long-range LoRa sensing because the sensing range is much larger compared to WiFi and acoustic based sensing. In this work, we address the challenging multi-target sensing issue, moving LoRa sensing one big step towards practical adoption. The key idea is to effectively utilize multiple antennas at the LoRa gateway to enable spatial beamforming to support multi-target sensing. While traditional beamforming methods adopted in WiFi and Radar systems rely on accurate channel information or transmitter-receiver synchronization, these requirements can not be satisfied in LoRa systems: the transmitter and receiver are not synchronized and no channel state information can be obtained from the cheap LoRa nodes. Another interesting observation is that while beamforming helps to increase signal strength, the phase/amplitude information which is critical for sensing can get corrupted during the beamforming process, eventually compromising the sensing capability. In this paper, we propose novel signal processing methods to address the issues above to enable long-range multi-target reparation sensing with LoRa. Extensive experiments show that our system can monitor the respiration rates of five human targets simultaneously at an average accuracy of 98.1%.
    </div>
  </details>
  
- [Exploring LoRa for Long-range Through-wall Sensing.](https://dl.acm.org/doi/abs/10.1145/3397326) <font color=red font-weight=bold>(Distinguished Paper Award)</font>\
  *Fusang Zhang, **Zhaoxin Chang**, Kai Niu, Jie Xiong, Beihong Jin, Qin Lv, Daqing Zhang.*\
  **ACM IMWUT Vol. 4/UbiComp 2020**
  <details>
    <summary>Abstract</summary>
     <p align="center">
        <img src="/files/lora.png" alt="图片描述" width="500px">
      </p>
    <div style="font-size: smaller;">
    Wireless signals have been extensively utilized for contactless sensing in the past few years. Due to the intrinsic nature of employing the weak target-reflected signal for sensing, the sensing range is limited. For instance, WiFi and RFID can achieve 3-6 meter sensing range while acoustic-based sensing is limited to less than one meter. In this work, we identify exciting sensing opportunities with LoRa, which is the new long-range communication technology designed for IoT communication. We explore the sensing capability of LoRa, both theoretically and experimentally. We develop the sensing model to characterize the relationship between target movement and signal variation, and propose novel techniques to increase LoRa sensing range to over 25 meters for human respiration sensing. We further build a prototype system which is capable of sensing both coarse-grained and fine-grained human activities. Experimental results show that (1) human respiration can still be sensed when the target is 25 meters away from the LoRa devices, and 15 meters away with a wall in between; and (2) human walking (both displacement and direction) can be tracked accurately even when the target is 30 meters away from the LoRa transceiver pair.
    </div>
  </details>

Professional Service
======

- **Technical Program Committee** AIoTSys, 2025
- **Artifacts Evaluation Committee** ACM MobiCom, 2025, 2024
- **Reviewer** ICA3PP 2025, 2025
- **Reviewer** ACM TOSN, 2025
- **Reviewer** ACM IMWUT, 2025, 2024, 2023
- **Reviewer** IEEE TMC, 2025, 2024
- **Technical Program Committee** IEEE ICC Workshop - PSoWN, 2025
- **Reviewer** ACM CHI, 2025, 2024
- **Technical Program Committee** IEEE UIC, 2024
- **Artifacts Evaluation Committee** ACM MobiSys, 2024
- **Reviewer** IEEE JSAC, 2024
- **Reviewer** ACM TIOT, 2023

Teaching Assistant
======

- **Fall 2018** Introduction to Computer Systems (Computer Systems: A Programmer's Perspective), Peking University
