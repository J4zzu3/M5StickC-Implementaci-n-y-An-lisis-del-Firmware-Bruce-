# M5StickC M2 + Bruce = Hacking de bolsillo

![](https://github.com/J4zzu3/M5StickC-Implementaci-n-y-An-lisis-del-Firmware-Bruce-/blob/main/Captura%20de%20pantalla%202025-11-28%20212133.png)

### 📋 Descripción

Este proyecto documenta el uso del M5StickC ejecutando el firmware Bruce de codigo abierto, un firmware orientado a pruebas de seguridad e investigación en dispositivos IoT/BLE. 

### El M5StickC, basado en ESP32, permite interactuar con diferentes protocolos inalámbricos y sensores internos, haciendo posible realizar análisis, auditorías en entornos controlados y experimentación educativa. ++++

---

### 🎯 Propósito Educativo

El objetivo es:

[+] Aprender sobre firmware alternativo en dispositivos ESP32

[+] Comprender el funcionamiento interno del M5StickC

[+] Realizar experimentos con  de BLE, NFC  y funciones integradas

[+] Practicar métodos de investigación en seguridad IoT

[+] Documentar el proceso de instalación, uso y limitaciones del firmware Bruce

### Y APROVECHAR EL ECOSISTEMA DEL HARDWARE HACKING............

---

### ✨ Características del Proyecto

📟 Pantalla IPS integrada

[+] Navegación mediante botones laterales, interfaz clara del firmware Bruce.

📡 Análisis BLE

[+] Escaneo y lectura de dispositivos BLE cercanos (según versión del firmware).

🧭 Sensores internos del M5StickC Plus2

[+] IMU, acelerómetro, RTC, micrófono, botones físicos.

🔌 Compatibilidad con NRF24L01

Comunicación RF en bandas de 2.4 GHz para:

[+] pruebas de laboratorio

[+] análisis de paquetes

[+] detección de actividad RF

[+] mediciones comparativas basicas.


🔋 Portabilidad total

[+] Batería interna 

[+] tamaño compacto 

[+] ideal para pruebas de campo controladas.

🧩 Firmware ligero y rápido

[+] Interacción inmediata y menús optimizados.

🔐 Enfoque ético de investigación


---


### 🛠️ Hardware Requerido

| Componente | Especificación |
| :--- | :--- |
| Dispositivo principal | M5StickC Plus2 (M5Stick M2) |
| MCU | ESP32-PICO-V3-02 |
| Módulo RF opcional | NRF24L01  |
| Cable | USB-C |
| Alimentación | 5V / 500mA |

---

### 📥 Instalación (Firmware Bruce)

# Preparar entorno

Instalar M5Burner

[Intalacion de M5Burner](https://docs.m5stack.com/en/uiflow/m5burner/intro)

Descargar el firmware Bruce para ESP32/M5StickC


# Conectar el M5StickC Plus2

Conectar USB-C

Abrir M5Burner

Seleccionar dispositivos

# Flashear

Elegir “Bruce”

Burn

Reiniciar

# Inicio

Debes ver en pantalla el menú principal de Bruce.

---

 ### 🚀 Uso 
 
# La interacción estándar incluye:

# 🔵 BLUETOOTH / BLE

🎯 BLE Beacon Flood

Generación masiva de anuncios BLE para pruebas de carga, ruido y resistencia de escáneres.

🎯 Random MAC Advertising

Anuncios BLE con direcciones MAC aleatorias.

🎯 BLE scan

Nos muestra en tiempo real las MAC de los dispositicos en nuestro radio de alcance

---

# 🌐 WIFI

🎯 Beacon Spam

Generación de varios SSIDs falsos para pruebas de descubrimiento en redes aisladas.

🎯 Deauth Flood

Consiste en un atacante que falsifica y envía repetidamente marcos de desconexión a los usuarios para forzarlos a desconectarse de la red Wi-Fi, logrando una Denegación de Servicio (DoS) efectiva.

🎯 Evil Portal

Bruce nos permite cargar nuestra propio codigo HTML y crear un portal cautivo.


 # 📡 RF (NRF24L01)
 
 Podemos añadir un modulo  NRF24L01 gracias a su diseño modular y a los pines GPIO que tiene el M5STICK M2 
 
 🎯 RF Traffic Burst (Controlado)
 
 Envío continuo de paquetes de datos para experimentos de congestión en entornos propios.

 🎯 Escaneo de canales NRF 2.4 GHz
 
  Nos permite ver los canales de la frecuencia 2.4 GHz ( Bluetooth - Wifi )

###  🔧 Necesitamos:

📟[Módulo NRF24L01](https://es.aliexpress.com/item/1005006943500925.html?aff_fcid=3f833e8f0238416da24b430a58b968e2-1764384462253-07797-_ooVOKwt&tt=CPS_NORMAL&aff_fsk=_ooVOKwt&aff_platform=shareComponent-detail&sk=_ooVOKwt&aff_trace_key=3f833e8f0238416da24b430a58b968e2-1764384462253-07797-_ooVOKwt&terminal_id=1ce0501773ca465db250af5e16392115&afSmartRedirect=y)

➿[Cables Jumper](https://es.aliexpress.com/item/1005007967664210.html?aff_fcid=99ac26813ca949e1aa23080269841f1a-1764384694146-09514-_oEV9OdB&tt=CPS_NORMAL&aff_fsk=_oEV9OdB&aff_platform=shareComponent-detail&sk=_oEV9OdB&aff_trace_key=99ac26813ca949e1aa23080269841f1a-1764384694146-09514-_oEV9OdB&terminal_id=1ce0501773ca465db250af5e16392115&afSmartRedirect=y)

📡[Antena](https://es.aliexpress.com/item/1005005576170270.html?aff_fcid=889172db1a31468ea02acd6c642dc8f2-1764384726507-09700-_o2EPXFf&tt=CPS_NORMAL&aff_fsk=_o2EPXFf&aff_platform=shareComponent-detail&sk=_o2EPXFf&aff_trace_key=889172db1a31468ea02acd6c642dc8f2-1764384726507-09700-_o2EPXFf&terminal_id=1ce0501773ca465db250af5e16392115&afSmartRedirect=y)

### ⚙️ Seguimos:

![](https://github.com/J4zzu3/M5StickC-Implementaci-n-y-An-lisis-del-Firmware-Bruce-/blob/main/pineshss.png)


#  🚨 ADVERTENCIA:

### ⚠️ USO EXCLUSIVAMENTE EDUCATIVO Y AUTORIZADO

✅ Permitido:

Investigación en entornos controlados

Análisis de señales BLE propias

Laboratorios de RF con hardware autorizado

Auditorías y pentesting con permiso explícito

❌ Prohibido:

Interferencia en el espectro

Monitorización de dispositivos ajenos

Acceso no autorizado

Alteración de sistemas de terceros


# Estare actualizando el repo y probando diferentes ataques que brinda el bruce en mi laboratorio


```text


⠀  ⠀   (\__/)
        (•ㅅ•)      GRACIAS BROOO!!!
     ＿ノヽ ノ＼＿      
 `/　`/ ⌒Ｙ⌒ Ｙ  ヽ      THANK YOU!!!
 (  (三ヽ人　 /　  |
 |　ﾉ⌒＼ ￣￣ヽ   ノ
 ヽ＿ ＿ ＿＞､＿_／
       ｜( 王 ﾉ〈   (\__/)
       /ﾐ`ー―彡\   (•ㅅ•)
      / ╰    ╯ \  /    \>
mafer<3


