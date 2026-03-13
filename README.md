# 🚀 Tutorial del SmartClic CORE  
## 🧭 Guía rápida de uso del test

Bienvenid@ al tutorial del **SmartClic CORE**.  
Aquí aprenderás, paso a paso, cómo funciona el proceso de test y qué hace cada fase.

---

## 📝 Pasos previos
Antes de iniciar el test:

- Marca si el **módem está montado** o no.
- Pulsa el botón **Iniciar test**.

---

# 🔍 Proceso completo del test

A continuación se detalla lo que realiza el sistema automáticamente:

---

## 1️⃣ Verificación del módem  
El sistema comprueba si has marcado correctamente la opción de *módem montado*.

---

## 2️⃣ Comprobación de conexión a Internet 🌐  
Se realiza un **ping** para verificar que la placa tiene acceso a la red.

---

## 3️⃣ Intento de conexión SSH 🔐  
El sistema intenta establecer una conexión SSH con la placa para validar acceso remoto.

---

## 4️⃣ Lectura de la ID de la CPU 🧠  
Se obtiene la **ID única del microcontrolador**, necesaria para trazabilidad.

---

## 5️⃣ Test del Watchdog y reinicio 🔄  
Se comprueba el funcionamiento del **watchdog**.  
Si todo es correcto, se fuerza un reinicio controlado del sistema.

---

## 6️⃣ Comprobación de LEDs 💡  
El sistema activa los LEDs de la placa.  
Se pedirá al usuario introducir **"s"** o **"n"** según si los LEDs funcionan correctamente.

---

## 7️⃣ Verificación del RTC ⏱️  
Se comprueba el correcto funcionamiento del **reloj interno** de la placa.

---

## 8️⃣ Detección de placas externas 🔌  
El sistema verifica que las placas externas conectadas al CORE se detectan correctamente.

---

# 🎉 Fin del tutorial  
Tu SmartClic CORE estará listo para funcionar si todos los pasos se completan correctamente.
