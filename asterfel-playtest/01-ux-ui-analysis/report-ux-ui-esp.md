# Analisis QA: Probé recientemente la playtest de Asterfel (Mysteria Studio) en Steam, y luego de 2 minutos identifique fallos que afectan directamente la jugabilidad y experiencia del usuario.
Tester: Manuel Nuñez Date: May 2026 Hardware: Ryzen 7 5700X3D | RTX 2070 Super | 24GB RAM | LEXAR NM790 1TB

Asterfel es un RPG en tercera persona inspirado en los clasicos RPGs de los 2000, cuenta con 5 años de desarrollo, y me sorprendió lo que comentare:

## 1. Ausencia del menú Settings en inicio: 
Creo que lo primero que hace un jugador antes de iniciar una partida, es verificar las opciones de video, audio,  etc, y configurarlas acorde a sus especificaciones. Iniciar el juego en una configuración automática es un riesgo de estabilidad.
<div align="center">
  <img src="01-menu-inicio.png" alt="Settings Menu" width="700px">
</div>

## 2. Tutorial y HUD:
2.1. Tutorial: El prompt de movimiento solo indica "WAD", omitiendo la "S". Un error de documentación básico que confunde en el primer contacto.<br>
2.2. HUD: Es demasiado invasivo en la esquina superior izquierda, restando visión al entorno. Se podría pulir ese diseño y hacerlo una interfaz mas limpia.
<div align="center">
  <img src="02-tutorial.png" alt="Settings Menu" width="700px">
</div>

## 3. Video Settings: 
Encuentro que faltan opciones importantes a la hora de configurar las opciones de vídeo como: el limite de FPS, Motion Blur, Camera Shake que son fundamentales para personas que sufren de cinetosis(mareos) al jugar. Además, en Unreal Engine 5, la ausencia de DLSS/FSR es un descuido importante en optimización.
<div align="center">
  <img src="03-video-settings.png" alt="Settings Menu" width="700px">
</div>

<br><br>
Esas fueron mis primeras impresiones con solo abrir el juego, pueden parecer básicas, pero para un juego que lleva 5 años en desarrollo, me parece que no deberian omitir este tipo de detalles que definen la calidad de la First Time User Experience (FTUE). 

No abordaré aún la jugabilidad, misiones o el rendimiento profundo... Ya que me dio mareos con hacer el tutorial 😅 (se nota la ausencia de esas opciones de vídeo) , asi que planeo dedicarle más horas para un reporte técnico completo.
