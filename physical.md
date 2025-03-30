---
title: Physical kit
nav_order: 30
---


# Physical Kit  

Protobject has been primarily designed to work on smartphones **without the need for additional hardware**. However, we have developed a **physical kit** for Protobject that allows you to use the platform with an **Arduino** or a **simple robot** for those who wish to experiment with these components.  
{: .fs-6 .fw-300 }

---

## **ProtoArduino**  

Protobject features a device called **ProtoArduino** that allows you to use an **Arduino Leonardo** as input and/or output by connecting it to the smartphone’s USB port. To use this device, it is necessary to **program an Arduino Leonardo** with our firmware. Once programmed, it can be used without the need to install any application on the smartphone or computer; everything works through the **Protobject web interface**.  

The **ProtoArduino** device offers blocks to:  
- Read **three analog inputs** and **three digital inputs** from Arduino (on pins A1, A2, A3 and D7, D8, D9).  
- Control up to **two servos** (D5 and D6).  
- Control **three PWM digital pins** (D3, D11, and D13).  

This allows you to **virtually extend Protobject** with dozens of sensors and actuators compatible with Arduino.  

The following video demonstrates how to control a **servo** using a **potentiometer** and shows the set of blocks used to program this example.  

{% include video_embed.html video_id="rfaN7I_fsaQ" %}

{% raw %}
<iframe loading="lazy" src="https://app.protobject.com/generate?zz-arduinoservo&amp;en&amp;dynamic&amp;-0" width="100%" height="250px" scrolling="yes" class="iframe-class" frameborder="0"></iframe>
{% endraw %}

## **ProtoRobot**  

Another device within Protobject is called **ProtoRobot**. This device allows you to control a **3D-printed robot**, and, like everything in Protobject, it operates through a smartphone installed directly on the robot. ProtoRobot utilizes an **Arduino Leonardo** to control two servos that enable its movement.  

To use ProtoRobot, it is connected to the smartphone through its **USB port**. Similar to ProtoArduino, once it’s programmed with our firmware, there’s no need to install any applications on the smartphone or computer. Everything operates through the same **Protobject web interface**.  

Below, there’s a video and the code for an example of using ProtoRobot, which can be controlled by tilting the smartphone. (For this purpose, the device that detects smartphone tilts is used).  


{% include video_embed.html video_id="dmJY-3cZqfU" %}

{% raw %}
<iframe loading="lazy" src="https://app.protobject.com/generate?zz-robot2&amp;en&amp;dynamic&amp;-0" width="100%" height="550px" scrolling="yes" class="iframe-class" frameborder="0"></iframe>
{% endraw %}



## **Components**  

The [firmware](https://framework.protobject.com/components/arduino.html) required for the operation of **ProtoArduino** is the same as that used for **ProtoRobot**. In other words, once an **Arduino Leonardo** is programmed with this firmware, the device can be used as both:  
- A controller for Arduino inputs and outputs  
- To control ProtoRobot  

The **physical kit** of Protobject is composed of the following components:  

### **General Components:**  
- 1 **Arduino Leonardo**  
- 1 **USB-C to USB Nano** cable (or another for connecting the smartphone to Arduino)  
- **Firmware** for Arduino Leonardo  

### **Specific Components for ProtoArduino:**  
- 1 **Arduino support** (optional, for added convenience during development)  

### **Specific Components for ProtoRobot:**  
- **Robot base**  
- 2 **front wheels**  
- 2 **rear wheels**  
- 2 **nuts for the wheels**  
- 1 **smartphone holder**  
- 2 **smartphone clamps**  
- 2 **nuts for the smartphone**  
- 2 **continuous servos FS90R**  
- 1 **female-female cable**  
- 3 **male-male cables**  
- 4 **small elastics**  
- 2 **medium-sized elastics** (optional, for the robot to function on uneven surfaces)  
