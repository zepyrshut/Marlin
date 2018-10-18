24/09/2018 - 1.1.9 v0.5 Beta.

 - Salida inicial. Ajustes iniciales para el primer encendido.
 - Arreglos en README.md.
 - Ajustado desfase del sensor de espuma.
 - Añadido control de temperaturas altas HIGH_TEMP.
 - Ajustes PID para temperaturas normales y temperaturas altas.
 
 25/09/2018 - 1.1.9 v0.6 Beta.
 
 - Ajustes PID de la base caliente con Ultrabase.
 
 19/10/2018 - 1.1.9 v0.7 Beta.
 
 - Reajuste PID en versión temperaturas normales y temperaturas altas.
 - Subido el máximo en temperaturas normales de 250ºC a 260ºC, y en temperaturas altas de 280ºC a 300ºC.
 - Reducido el máximo de la cama caliente en temperaturas normnales de 120ºC a 100ºC.
 - Cambios en `#define THERMAL_PROTECTION_PERIOD` y `#define THERMAL_PROTECTION_HYSTERESIS` para evitar falsos positivos en variaciones de temperaturas durante la impresión.