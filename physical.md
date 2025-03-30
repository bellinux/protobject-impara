---
title: Kit fisico
nav_order: 30
---

# Kit Fisico  

Protobject è stato progettato principalmente per funzionare su smartphone **senza necessità di hardware aggiuntivo**. Tuttavia, abbiamo sviluppato un **kit fisico** per Protobject che ti consente di utilizzare la piattaforma con un **Arduino** o un **robot semplice** per coloro che desiderano sperimentare con questi componenti.  
{: .fs-6 .fw-300 }

---

## **ProtoArduino**  

Protobject dispone di un dispositivo chiamato **ProtoArduino** che permette di utilizzare un **Arduino Leonardo** come ingresso e/o uscita collegandolo alla porta USB dello smartphone. Per utilizzare questo dispositivo, è necessario **programmare un Arduino Leonardo** con il nostro firmware. Una volta programmato, può essere utilizzato senza dover installare alcuna applicazione sul telefono o sul computer; tutto funziona tramite l'**interfaccia web di Protobject**.  

Il dispositivo **ProtoArduino** offre blocchi per:  
- Leggere **tre ingressi analogici** e **tre ingressi digitali** dell'Arduino (sui pin A1, A2, A3 e D7, D8, D9).  
- Controllare fino a **due servomotori** (D5 e D6).  
- Controllare **tre pin digitali PWM** (D3, D11 e D13).  

Questo ti permette di **estendere virtualmente Protobject** con decine di sensori e attuatori compatibili con Arduino.  

Il seguente video mostra come controllare un **servomotore** utilizzando un **potenziometro** e mostra il set di blocchi utilizzati per programmare questo esempio.  

{% include video_embed.html video_id="rfaN7I_fsaQ" %}

[Visualizza il codice di esempio](https://app.protobject.com/generate?zz-arduinoservo&amp;it&amp;dynamic&amp;-1){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 target="_blank"}



## **ProtoRobot**  

Un altro dispositivo all'interno di Protobject si chiama **ProtoRobot**. Questo dispositivo permette di controllare un **robot stampato in 3D**, e, come tutto in Protobject, funziona tramite uno smartphone montato direttamente sul robot. ProtoRobot utilizza un **Arduino Leonardo** per controllare due servomotori che ne permettono il movimento.  

Per utilizzare ProtoRobot, si collega allo smartphone tramite la sua **porta USB**. Come per ProtoArduino, una volta programmato con il nostro firmware, non è necessario installare alcuna applicazione sul telefono o sul computer. Tutto funziona tramite la stessa **interfaccia web di Protobject**.  

Di seguito trovi un video e il codice per un esempio di utilizzo di ProtoRobot, che può essere controllato inclinando lo smartphone. (Per questo scopo, viene utilizzato il dispositivo che rileva le inclinazioni del telefono).  

{% include video_embed.html video_id="dmJY-3cZqfU" %}

[Visualizza il codice di esempio](https://app.protobject.com/generate?zz-robot2&amp;it&amp;dynamic&amp;-1){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 target="_blank"}


## **Componenti**  

Il [firmware](https://framework.protobject.com/components/arduino.html) necessario per il funzionamento di **ProtoArduino** è lo stesso utilizzato per **ProtoRobot**. In altre parole, una volta che un **Arduino Leonardo** è programmato con questo firmware, il dispositivo può essere utilizzato in entrambi i modi:  
- Come controller per gli ingressi e le uscite di Arduino  
- Per controllare ProtoRobot  

Il **kit fisico** di Protobject è composto dai seguenti componenti:  

### **Componenti generali:**  
- 1 **Arduino Leonardo**  
- 1 **cavo USB-C a USB Nano** (o altro per collegare lo smartphone all'Arduino)  
- **Firmware** per Arduino Leonardo  

### **Componenti specifici per ProtoArduino:**  
- 1 **supporto per Arduino** (opzionale, per maggiore comodità durante lo sviluppo)  

### **Componenti specifici per ProtoRobot:**  
- **Base del robot**  
- 2 **ruote anteriori**  
- 2 **ruote posteriori**  
- 2 **dadi per le ruote**  
- 1 **supporto per smartphone**  
- 2 **fermagli per smartphone**  
- 2 **dadi per lo smartphone**  
- 2 **servomotori continui FS90R**  
- 1 **cavo femmina-femmina**  
- 3 **cavi maschio-maschio**  
- 4 **elastici piccoli**  
- 2 **elastici medi** (opzionali, per far funzionare il robot su superfici irregolari)
