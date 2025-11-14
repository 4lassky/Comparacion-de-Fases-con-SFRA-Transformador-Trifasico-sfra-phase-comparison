# Comparacion-de-Fases-con-SFRA-Transformador-Trifasico-sfra-phase-comparison
Este es un script de utilidad en MATLAB para cargar y comparar gráficamente dos mediciones SFRA (archivos `.s2p`). Su propósito principal es superponer las huellas de dos fases diferentes de un transformador para una inspección visual rápida.

Proyecto académico realizado por **Galindo Barbosa Israel Aldahir** y **Herrera Godoy Hazael** para **ESIME ZACATENCO - IPN**.

## 🚀 Características Principales
* **Carga de Datos:** Solicita al usuario que seleccione dos archivos `.s2p` por separado (Ej. Fase 1 y Fase 2).
* **Procesamiento:** Aplica un suavizado a ambas curvas para facilitar la comparación.
* **Visualización Comparativa:**
    * Genera una única gráfica que superpone ambas trazas (Fase 1 en azul, Fase 2 en negro).
    * Dibuja las 4 zonas de frecuencia según la norma **IEEE C57.149-2012**.
* **Exportación:** Permite guardar la gráfica comparativa en formato `.png` de alta resolución.

## ⚙️ Uso
1.  Ejecute el script en MATLAB.
2.  Seleccione el primer archivo `.s2p` (Ej. "Referencia Fase 1").
3.  Seleccione el segundo archivo `.s2p` (Ej. "Referencia Fase 2").
4.  La gráfica se mostrará automáticamente.
5.  Se le preguntará si desea guardar la figura.
