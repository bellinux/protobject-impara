---
title: Kit físico
nav_order: 30
---


# Kit Físico  

Protobject ha sido diseñado principalmente para funcionar en teléfonos inteligentes **sin necesidad de hardware adicional**. Sin embargo, hemos desarrollado un **kit físico** para Protobject que te permite utilizar la plataforma con un **Arduino** o un **robot simple** para aquellos que deseen experimentar con estos componentes.  
{: .fs-6 .fw-300 }

---

## **ProtoArduino**  

Protobject cuenta con un dispositivo llamado **ProtoArduino** que permite usar un **Arduino Leonardo** como entrada y/o salida al conectarlo al puerto USB del teléfono inteligente. Para utilizar este dispositivo, es necesario **programar un Arduino Leonardo** con nuestro firmware. Una vez programado, se puede utilizar sin necesidad de instalar ninguna aplicación en el teléfono o computadora; todo funciona a través de la **interfaz web de Protobject**.  

El dispositivo **ProtoArduino** ofrece bloques para:  
- Leer **tres entradas analógicas** y **tres entradas digitales** del Arduino (en los pines A1, A2, A3 y D7, D8, D9).  
- Controlar hasta **dos servos** (D5 y D6).  
- Controlar **tres pines digitales PWM** (D3, D11 y D13).  

Esto te permite **extender virtualmente Protobject** con docenas de sensores y actuadores compatibles con Arduino.  

El siguiente video muestra cómo controlar un **servo** utilizando un **potenciómetro** y muestra el conjunto de bloques utilizados para programar este ejemplo.  

{% include video_embed.html video_id="rfaN7I_fsaQ" %}

[Ver el código de ejemplo](https://app.protobject.com/generate?zz-arduinoservo&amp;es&amp;dynamic&amp;-1){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 target="_blank"}



## **ProtoRobot**  

Otro dispositivo dentro de Protobject se llama **ProtoRobot**. Este dispositivo permite controlar un **robot impreso en 3D**, y, como todo en Protobject, funciona a través de un teléfono inteligente instalado directamente en el robot. ProtoRobot utiliza un **Arduino Leonardo** para controlar dos servos que permiten su movimiento.  

Para usar ProtoRobot, se conecta al teléfono inteligente a través de su **puerto USB**. Al igual que ProtoArduino, una vez que se programa con nuestro firmware, no es necesario instalar ninguna aplicación en el teléfono o computadora. Todo opera a través de la misma **interfaz web de Protobject**.  

A continuación, se encuentra un video y el código para un ejemplo de uso de ProtoRobot, que se puede controlar inclinando el teléfono inteligente. (Para este propósito, se utiliza el dispositivo que detecta las inclinaciones del teléfono).  

{% include video_embed.html video_id="dmJY-3cZqfU" %}

[Ver el código de ejemplo](https://app.protobject.com/generate?zz-robot2&amp;es&amp;dynamic&amp;-1){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 target="_blank"}


## **Componentes**  

El [firmware](https://framework.protobject.com/components/arduino.html) requerido para el funcionamiento de **ProtoArduino** es el mismo que se utiliza para **ProtoRobot**. Es decir, una vez que un **Arduino Leonardo** se programa con este firmware, el dispositivo se puede utilizar como ambos:  
- Un controlador para las entradas y salidas de Arduino  
- Para controlar ProtoRobot  

El **kit físico** de Protobject está compuesto por los siguientes componentes:  

### **Componentes generales:**  
- 1 **Arduino Leonardo**  
- 1 **cable USB-C a USB Nano** (o otro para conectar el teléfono inteligente al Arduino)  
- **Firmware** para Arduino Leonardo  

### **Componentes específicos para ProtoArduino:**  
- 1 **soporte para Arduino** (opcional, para mayor comodidad durante el desarrollo)  

### **Componentes específicos para ProtoRobot:**  
- **Base del robot**  
- 2 **ruedas delanteras**  
- 2 **ruedas traseras**  
- 2 **tuercas para las ruedas**  
- 1 **soporte para teléfono inteligente**  
- 2 **sujeciones para teléfono inteligente**  
- 2 **tuercas para el teléfono inteligente**  
- 2 **servos continuos FS90R**  
- 1 **cable hembra-hembra**  
- 3 **cables macho-macho**  
- 4 **elásticos pequeños**  
- 2 **elásticos medianos** (opcionales, para que el robot funcione en superficies irregulares)
