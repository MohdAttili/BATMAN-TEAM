<p align="center">
<img src="v-photos/batman_logo_4k_yellow_accent.png" alt="Team Photo" style="width:300px; height:200px;">
</p>

##
----
## Vehicle Preview
<p align="center">
<img src="v-photos//Robot pictures/from the top.png" alt="Vehicle Photo" width="500"/>
</p>

##
----
An autonomous vehicle designed for the Future Engineers category of the WRO 2025 that uses computer vision and IMU sensors to navigate complex environments and avoid obstacles intelligently.

## Content Structure

📁 **t-photos** → [team photos ](https://github.com/MohdAttili/BATMAN-TEAM/tree/main/t-photos)   
📁 **v-photos** → [vehicle photos  ](https://github.com/MohdAttili/BATMAN-TEAM/tree/main/v-photos)   
📁 **video** → [video.md with demonstration link  ](https://github.com/MohdAttili/BATMAN-TEAM/tree/main/videos)   
📁 **schemes** → [schematic diagrams ](https://github.com/MohdAttili/BATMAN-TEAM/tree/main/schemes)    
📁 **src** → [control software  ](https://github.com/MohdAttili/BATMAN-TEAM/tree/main/src)   
📁 **models** → [3D printing ](https://github.com/MohdAttili/BATMAN-TEAM/tree/main/models)    
📁 **other** → [documentation and additional resources  ](https://github.com/MohdAttili/BATMAN-TEAM/tree/main/other)   
## Project Overview
This repository contains all the engineering materials, code, schematics, and models related to our self-driven vehicle, designed and built to participate in the WRO Future Engineers 2025 competition. The project aims to develop an autonomous vehicle capable of navigating a predefined course while demonstrating precision, stability, and effective control of electromechanical components.

Our vehicle is a compact, versatile model incorporating both mechanical and electronic systems. It is designed to efficiently demonstrate autonomous navigation using sensors, motor control, and a central microcontroller. The design and implementation of this project involved detailed planning, testing, and iterative improvements to meet the strict requirements of the competition.
##
----
## Why BATMAN

**Our team is called “BATMAN” — not only after the iconic hero, but after the values he stands for. Batman represents discipline, sharp thinking, resilience, and the courage to confront challenges head-on. Just as he rises above the darkness to restore order, our team rises above obstacles to achieve success. 🦇💪**

##
----
## Who We Are

<table border="1">
  <tr>
    <td align="center">
      <img src="/t-photos/osama669_1080x1080.png" alt="From the right" width="240"height="250"/><br>
      Osama Jadbah<br>
      Planning <br>
      Research<br>
      Documentation
    </td>
    <td align="center">
      <img src="/t-photos/attili.jpg" alt="From the left" width="240"height="250"/><br>
      Mohammad Attili<br>
      Hardware <br>
      Software
    </td>
    <td align="center">
      <img src="/t-photos/karem1.jpg" alt="From the left" width="240"height="250"/><br>
      Kareem Amr<br>
      Mechanical Design<br>
      Algorithms
    </td>    
  </tr>
</table>

We are a team of three passionate Palestinian students from Tulkarm Industrial Secondary School, united by our love for programming, artificial intelligence, and problem-solving. Osama Jadbah, 18, focuses on lifelong learning, self-development, and has earned multiple excellence certificates for his achievements. Mohammad Attili, 18, is a competitive programmer who has excelled in national and international contests, showcasing his innovation and tech skills. Kareem Amr, also 18, is a skilled programmer and problem solver, experienced in algorithms and competitive programming, and an accomplished chess player who earned 3rd place in the Palestinian Chess Championship. Together, we strive to develop our skills, tackle challenging projects, and explore new technological horizons.
[Further Information ](https://github.com/MohdAttili/BATMAN-TEAM/blob/main/t-photos/Team%20Description.pdf)

##
----


## 🔍 Project Description
**🎯 Goals**  
1. Build a functional self-driven vehicle that can navigate a course autonomously.  
2. Integrate electronic and mechanical components seamlessly.  
3. Develop modular and maintainable code to control all vehicle components.  
4. Document all aspects of the vehicle's design, construction, and programming.  
5. Provide clear and detailed engineering materials to facilitate understanding and replication.  

 ## ⚙️ Physical Equipment  

**1. 🧠 ESP32-WROOM-32 Overview**
<!-- 1. ESP32-WROOM-32 is a microcontroller by Espressif with Wi-Fi and Bluetooth, commonly used in smart devices and robotics.
2. It features a dual-core Xtensa 32-bit LX6 processor up to 240 MHz, with 520 KB SRAM and 4 MB Flash.
3. Offers around 34 programmable GPIO pins and interfaces like SPI, I2C,  UART, PWM, and I2S, with ADC/DAC support.  
4. Supports dual connectivity, multiple protocols, and has a large  community with ready-to-use libraries.  
5. Common applications include robotics, smart home systems, remote   measurement/control devices, and IoT data collection.  -->
1. ESP32-WROOM-32 is a powerful microcontroller by Espressif with built-in Wi-Fi and Bluetooth, featuring a dual-core 32-bit Xtensa LX6 processor up to 240 MHz, 520 KB SRAM, 4 MB Flash, and around 34 programmable GPIOs with multiple interfaces (SPI, I2C, UART, PWM, ADC/DAC).

2. It is widely used in robotics, IoT, smart home systems, and remote monitoring/control applications due to its dual connectivity, protocol support, large community, and ready-to-use libraries.   

**2.🎥 Pixy 2.1 (CMUcam5) Overview**
<!-- 1. The Pixy 2.1 is a smart vision sensor that detects and tracks objects by color or shape.
2. Resolution: 320×200 pixels, frame rate up to 60 fps, with interfaces SPI, I²C, UART, and USB.
3. Built-in processor allows real-time object recognition and can track multiple objects simultaneously.
4. Sends object coordinates directly to microcontrollers like Arduino or ESP32, reducing main board load.
5. Common applications include line-following robots, object detection/sorting, interactive projects, and educational AI experiments. -->
1. Pixy 2.1 is a smart vision sensor capable of detecting and tracking objects by color or shape, featuring a 320×200 resolution, up to 60 fps, multiple interfaces (SPI, I²C, UART, USB), and a built-in processor for real-time multi-object tracking.

2. It outputs object coordinates directly to microcontrollers such as Arduino or ESP32, reducing processing load, and is commonly used in line-following robots, object detection/sorting, interactive projects, and educational AI applications.

**3. ⚡ MG996R Servo Overview**
<!-- 1. High-torque digital servo with reliable performance and precise positioning.   
2. Operating Voltage: 4.8–6.0V DC, providing ~9.4–11 kg·cm torque.     
3. Applications: Suitable for steering, robotic arms, and hobby projects.   
4. Motor & Gears: Coreless motor with durable metal gears for smooth, accurate motion.   
5. Control & Integration: Controlled via standard PWM; compatible with Arduino, Raspberry Pi, and robotics kits.   -->
1. High-torque digital servo motor operating at 4.8–6.0V DC, delivering approximately 9.4–11 kg·cm torque, featuring a coreless motor and durable metal gears for smooth and precise motion.

2. Commonly used in steering systems, robotic arms, and hobby projects, controlled via standard PWM and compatible with Arduino, Raspberry Pi, and various robotics kits.

**4. 🚗 JGA52-370 12V Motor Overview**
<!-- 1. DC geared motor designed for stable torque output and smooth rotational performance.
2. Operating Voltage: 12V DC, delivering strong torque suitable for medium-load applications.
3. Applications: Ideal for robotics, electric locks, conveyor systems, and DIY mechanical projects.
4. Motor & Gearbox: Equipped with a 370-series motor and a high-precision metal gearbox for durability and consistent speed.
5. Control & Integration: Easily driven by motor drivers (L298N, BTS7960, etc.); compatible with Arduino, microcontrollers, and automation setups. -->
1. 12V DC geared motor designed for smooth rotation and stable torque, featuring a 370-series motor with a high-precision metal gearbox that ensures durability and consistent speed under medium loads.

2. Widely used in robotics, electric locks, conveyor systems, and DIY mechanical projects, and can be easily controlled using motor drivers such as L298N or BTS7960, making it compatible with Arduino, microcontrollers, and automation systems.  




**5.⚡ AUG 22 Wires Overview**
<!-- 1. High-quality 22-AWG stranded wires designed for reliable electrical connections.
2. Specifications: Rated for low-voltage DC circuits; supports stable current flow with flexible insulation.
3. Applications: Suitable for sensors, prototyping, breadboards, and lightweight robotics wiring.
4. Build & Material: Features multi-strand copper conductors with durable PVC insulation for flexibility and longevity.
5. Integration: Easy to strip, solder, and connect; compatible with Arduino, Raspberry Pi, and general electronic modules. -->
1. 22-AWG stranded wires made of multi-strand copper with durable PVC insulation, designed for low-voltage DC circuits, offering flexible handling and stable current flow.

2. Commonly used for sensors, breadboards, prototyping, and lightweight robotics wiring, and are easy to strip, solder, and integrate with Arduino, Raspberry Pi, and general electronic modules.

**6.🤖 L298N Motor Driver Overview**
<!-- 1. Dual H-bridge motor driver designed for controlling two DC motors or one stepper motor with stable performance.
2. Operating Voltage: 5–35V DC input, providing up to 2A per channel under proper cooling.
3. Applications: Ideal for robotics, RC vehicles, CNC mechanisms, and motor-control projects.
4. Components & Features: Built-in 5V regulator, heat sink for thermal stability, and independent motor channels for precise control.
5. Control & Integration: Compatible with Arduino, Raspberry Pi, and microcontroller systems using PWM signals for speed and direction control. -->
1. Dual H-bridge motor driver capable of controlling two DC motors or one stepper motor, operating on 5–35V DC with up to 2A per channel (with proper cooling), and featuring a built-in 5V regulator and heat sink for stable performance.

2. Commonly used in robotics, RC vehicles, CNC mechanisms, and motor-control projects, and easily integrated with Arduino, Raspberry Pi, and other microcontrollers using PWM for speed and direction control. 

**7.🧩 Metal Gear Set Overview**
<!-- 1. Durable metal gear assortment designed for mechanical transmission and high-torque applications.
2. Specifications: Includes multiple gear sizes and tooth counts, ensuring compatibility with various motor shafts and gear ratios.
3. Applications: Suitable for robotics mechanisms, gearboxes, servo repairs, and custom motion-control projects.
4. Material & Build: Constructed from hardened metal for strength, wear resistance, and long operational life.
5. Integration: Easy to mount and modify; compatible with DC motors, servo upgrades, and DIY mechanical assemblies. -->
1. Durable metal gear assortment designed for high-torque mechanical transmission, featuring multiple gear sizes and tooth counts to support different motor shafts and gear ratios.

2. Commonly used in robotics mechanisms, gearboxes, servo repairs, and custom motion-control projects, made from hardened metal for long life and easy integration with DC motors, servos, and DIY mechanical assemblies.
   
**8.🔧 M3 Screws Overview**
<!-- 1. Standard M3 metric screws designed for secure fastening in mechanical and electronic assemblies.
1. Specifications: Available in various lengths with a 3mm thread diameter, offering reliable strength and compatibility.
2. Applications: Suitable for mounting motors, brackets, PCBs, 3D-printed parts, and structural frames.
3. Material & Build: Manufactured from stainless steel or hardened alloy for durability, corrosion resistance, and stable threading.
4. Integration: Compatible with nuts, washers, and standoffs; ideal for robotics kits, DIY projects, and precision hardware assemblies. -->
1. M3 metric screws with a 3 mm thread diameter, available in various lengths, made from stainless steel or hardened alloy to provide durable, corrosion-resistant, and reliable fastening.

2. Widely used for mounting motors, brackets, PCBs, 3D-printed parts, and structural frames, and fully compatible with nuts, washers, and standoffs in robotics kits, DIY projects, and precision assemblies.
   
**9 🛠 M4 Screws Overview**
<!-- 1. Robust M4 metric screws designed for strong and secure fastening in mechanical structures.
1. Specifications: 4mm thread diameter with multiple length options, providing enhanced load-bearing capacity.
2. Applications: Ideal for mounting metal brackets, motors, aluminum frames, and heavy-duty assemblies.
3. Material & Build: Made from stainless steel or alloy steel for high durability, corrosion resistance, and reliable threading.
4. Integration: Compatible with M4 nuts, washers, and structural components; suitable for robotics, machinery, and DIY mechanical projects. -->
1. M4 metric screws with a 4 mm thread diameter, available in multiple lengths, made from stainless steel or alloy steel to ensure high strength, durability, and corrosion resistance.

2. Commonly used for mounting metal brackets, motors, aluminum frames, and heavy-duty structures, and compatible with M4 nuts and washers in robotics, machinery, and DIY mechanical projects.
   
**10📏 MPU6050 Gyroscope Overview**
<!-- 1. 6-axis motion tracking sensor combining a 3-axis gyroscope and 3-axis accelerometer for precise orientation detection.
2. Operating Voltage: 3–5V DC, providing accurate angular velocity and acceleration measurements.
3. Applications: Ideal for drones, robotics, balance robots, and motion-sensing projects.
4. Components & Features: Built-in Digital Motion Processor (DMP) for real-time motion processing; I²C interface for easy communication.
5. Integration: Compatible with Arduino, Raspberry Pi, and microcontroller platforms; supports libraries for quick implementation and calibration. -->
1. 6-axis motion sensor combining a 3-axis gyroscope and 3-axis accelerometer, operating at 3–5V, with a built-in DMP for real-time motion processing, ideal for drones, robotics, and motion-sensing projects.

2. I²C interface for easy communication, compatible with Arduino, Raspberry Pi, and microcontroller platforms, with libraries available for quick implementation and calibration.
   
**11👀 TOF 200C Overview**
<!-- 1. High-precision Time-of-Flight (ToF) distance sensor designed for accurate and fast distance measurements.
1. Operating Voltage: 3.3–5V DC, capable of measuring distances with millimeter-level accuracy.
2. Applications: Ideal for obstacle detection, robotics navigation, automation systems, and gesture recognition projects.
3. Components & Features: Features a laser emitter and receiver module for precise distance calculation; compact and lightweight design.
4. Integration: Communicates via I²C interface; compatible with Arduino, Raspberry Pi, and other microcontroller platforms. -->
1. High-precision Time-of-Flight (ToF) distance sensor operating at 3.3–5V, offering millimeter-level accuracy, ideal for obstacle detection, robotics navigation, automation, and gesture recognition.

2. Features a laser emitter and receiver, compact design, with I²C communication; compatible with Arduino, Raspberry Pi, and other microcontroller platforms.
   
**12👓TOF 400C Overview**
<!-- 1. Advanced Time-of-Flight (ToF) distance sensor designed for high-accuracy and long-range measurements.
1. Operating Voltage: 3.3–5V DC, capable of detecting distances up to several meters with precise millimeter resolution.
2. Applications: Ideal for robotics, autonomous navigation, obstacle avoidance, and industrial automation projects.
3. Components & Features: Equipped with a laser emitter and receiver, offering fast response and reliable distance sensing in compact form.
4. Integration: Communicates via I²C interface; compatible with Arduino, Raspberry Pi, and microcontroller platforms.
(Quantity: 3 units) -->
1. Advanced Time-of-Flight (ToF) distance sensor operating at 3.3–5V, capable of long-range measurements with millimeter-level accuracy, ideal for robotics, autonomous navigation, obstacle avoidance, and industrial automation.

2. Features a laser emitter and receiver for fast and reliable distance sensing, compact design, with I²C communication; compatible with Arduino, Raspberry Pi, and microcontroller platforms. (Quantity: 3 units)
   
**13📐 XH Connectors Overview**
<!-- 1. Reliable XH series connectors designed for secure and consistent electrical connections.
1. Specifications: Standard pitch and pin configuration for low-voltage DC circuits; supports stable current flow.
2. Applications: Ideal for battery packs, sensors, small electronic modules, and hobby electronics projects.
3. Material & Build: Made from durable plastic housing with tin-plated metal contacts for corrosion resistance and long life.
4. Integration: Easy to plug and unplug; compatible with JST-XH wires and headers for quick assembly and prototyping. -->
1. Reliable XH series connectors with standard pitch and pin configuration, ensuring secure and stable low-voltage DC connections for battery packs, sensors, and small electronic modules.

2. Durable plastic housing with tin-plated contacts for corrosion resistance, easy to plug/unplug, compatible with JST-XH wires and headers for quick assembly and prototyping.
   
**14🖥 4.3” OLED Display Overview**
<!-- 1. Compact 4.3-inch OLED screen designed for sharp visuals and low power consumption.
1. Specifications: High-contrast display with bright colors and wide viewing angles; supports 16-bit color depth.
2. Applications: Ideal for DIY electronics, robotics interfaces, handheld devices, and monitoring panels.
3. Components & Features: Features an integrated driver for easy control, thin and lightweight for compact setups.
4. Integration: Compatible with Arduino, Raspberry Pi, and other microcontroller platforms; supports SPI/I²C communication.
(Quantity: 2 units) -->
1. Compact 4.3-inch OLED screen with high-contrast, bright colors, wide viewing angles, and low power consumption, ideal for DIY electronics, robotics interfaces, handheld devices, and monitoring panels.

2. Integrated driver for easy control, thin and lightweight design, compatible with Arduino, Raspberry Pi, and other microcontroller platforms, supporting SPI/I²C communication. (Quantity: 2 units)
 [More Details about the Components](https://github.com/MohdAttili/TSISFE2025/blob/main/other/Selected%20Components.pdf)
 
 [Comparisons with Other Components in the Market](https://github.com/MohdAttili/TSISFE2025/blob/main/other/Comparison%20with%20Other%20Components.pdf) 
  <p align="center">
   <img src="v-photos/Robot parts/ESP32-WROOM-32.png" alt="Image 1" width="90"/>
   <img src="v-photos/Robot parts/dc_geared_motor_cinematic_high_res.png" alt="Image 2" width="90"/>
   <img src="v-photos/Robot parts/esp32_breakout_board_cinematic_high_res.png" alt="Image 3" width="90"/>
   <img src="v-photos/Robot parts/mpu6050_cinematic_high_res.png" alt="Image 4" width="90"/>
   <img src="v-photos/Robot parts/oled_screen_enhanced.png" alt="Image 5" width="90"/>
   <img src="v-photos/Robot parts/tof400_enhanced.png" alt="Image 6" width="90"/>
   <img src="v-photos/Robot parts/mg996r_servo_high_res_dramatic.png" alt="Image 7" width="90"/>
   <img src="v-photos/Robot parts/pixy_camera_high_res_dramatic.png" alt="Image 8" width="90"/>
   <img src="v-photos/Robot parts/wiresawg22_enhanced.png" alt="Image 6" width="90"/>
   <img src="v-photos/Robot parts/xhconnector_enhanced.png" alt="Image 6" width="90"/>
   <img src="v-photos/Robot parts/tof200c_vl53l0x_cinematic_high_res.png" alt="Image 6" width="90"/>
  <img src="v-photos/Robot parts/gears.png" alt="Image 6" width="90"/>

  
 </p>
 
 ##
----
 ## 🎮 The Code 
 
 ## Robot Videos  
 <table border="1">
   <tr>
     <td align="center">
       <img src="/v-photos/batman_logo_4k_yellow_accent.png" alt="From the right" width="400" height="250"/><br>  
       <a href="Not ready yet" target="_blank">Open Challenge</a>
     </td>
     <td align="center">
       <img src="/v-photos/batman_logo_4k_yellow_accent.png" alt="From the left" width="400" height="250"/><br>
       <a href="Not ready yet" target="_blank">Obstacle Challenge</a>
     </td>  
   </tr>
 </table>