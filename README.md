#Medidor de Frecuencia de Corriente Alterna  

Este proyecto fue desarrollado como parte de la materia **Integración Mecatrónica**. Consiste en un sistema capaz de medir la frecuencia de la corriente alterna de un conector convencional, analizar posibles alteraciones y visualizar los resultados de forma gráfica.  

Descripción  

El sistema utiliza un **Arduino** y un **módulo ACS712** para capturar la señal de corriente alterna. A través de la **Transformada Rápida de Fourier (FFT)**, se convierte la señal al dominio de la frecuencia, permitiendo detectar posibles variaciones. Los datos obtenidos son graficados para su análisis.  

Tambien cabe mencionar,que se desarrolló una implementación utilizando Python y Arduino, comunicándose a través de serial (UART). Esta integración permitió la adquisición y procesamiento de datos en tiempo real, facilitando la visualización de la frecuencia y posibles alteraciones en la señal mediante gráficos interactivos.

Además, el proyecto incluye el diseño y fabricación de una caja de **MDF**, diseñada para soportar **1000 N de fuerza aplicada directamente sobre su superficie**, equivalente al peso de una persona de aproximadamente 110 kg. Para validar su resistencia, se realizó un análisis estructural en **SolidWorks**, identificando los puntos críticos y asegurando su integridad mecánica.  

Componentes principales  

- **Microcontrolador:** Arduino  
- **Sensor de corriente:** Módulo ACS712  
- **Análisis de señal:** Transformada Rápida de Fourier (FFT)  
- **Estructura:** Caja de MDF diseñada y simulada en SolidWorks  
- **Visualización:** Gráficos para análisis de la señal en el dominio de la frecuencia  

Funcionamiento  

1. **Adquisición de datos:** Captura de la señal de corriente alterna mediante el sensor ACS712.  
2. **Procesamiento de señal:** Aplicación de la FFT para obtener la frecuencia de la señal.  
3. **Visualización:** Representación gráfica de la señal y sus variaciones.  
4. **Soporte estructural:** Caja de MDF optimizada para soportar fuerzas de hasta 1000 N.  

## Proceso de desarrollo  

1. **Diseño del sistema de medición**  
   - Selección del sensor ACS712 para capturar la señal de corriente alterna.  
   - Implementación de un circuito seguro para conectar el sensor al Arduino.  

2. **Procesamiento de la señal**  
   - Captura de datos en tiempo real mediante Arduino.
   ![image](https://github.com/user-attachments/assets/7dadae0c-5db3-4b89-b3fa-7269f09297d0)
   
   - Aplicación de la **Transformada Rápida de Fourier (FFT)** para analizar la frecuencia.  
   - Desarrollo de un sistema de visualización de datos en gráficos.

![medidor_frecuencia_ajustado](https://github.com/user-attachments/assets/a69eccfb-684b-4271-9e82-313574bcd068)


3. **Diseño y simulación estructural**  
   - Modelado de la caja en **SolidWorks** considerando los requerimientos de carga.

![Caja1](https://github.com/user-attachments/assets/9c93fd65-80f8-417f-8351-9502f8c49c18)
![Caja2](https://github.com/user-attachments/assets/58f70408-7719-4ef1-8184-631abcc7145d)
![Caja3](https://github.com/user-attachments/assets/63bfc64c-ff7a-4c6a-ab13-6e43d44b4eab)

   - Simulación estructural para evaluar resistencia y puntos débiles.  
![Sim1](https://github.com/user-attachments/assets/2d562278-1fdc-4368-8b25-18e6acbfc84d)
![Sim2](https://github.com/user-attachments/assets/3bd1fdec-e82c-44f9-a796-3cbc70708c34)
![Sim3](https://github.com/user-attachments/assets/a24b2c72-94e1-497f-afd5-c0b1148645fb)

4. **Fabricación y pruebas**  
   - Corte y ensamblaje de la caja de MDF.  
   - Pruebas de carga aplicando **1000 N** para verificar la resistencia estructural.  
   - Validación del sistema de medición y ajuste de parámetros.
![WhatsApp Image 2024-11-30 at 21 19 08_7acdb59f](https://github.com/user-attachments/assets/ccba1879-ac4d-4dba-af31-51d6c54a701f)
![CajaF2](https://github.com/user-attachments/assets/bcc0f054-ceff-4b84-96b8-7f9e0790c95a)
![CajaF1](https://github.com/user-attachments/assets/02a4bfbc-17bb-4cc5-a547-3408b1afe935)

Objetivos del proyecto  

- Implementar un sistema de medición de frecuencia de corriente alterna basado en Arduino.  
- Aplicar la Transformada Rápida de Fourier para el análisis de la señal.  
- Diseñar y validar estructuralmente una caja de MDF resistente a cargas elevadas.  

Posibles mejoras  

- Aumentar la precisión del análisis utilizando sensores de mayor resolución.  
- Integrar conectividad inalámbrica para monitoreo remoto.  
- Optimizar el diseño estructural con materiales alternativos.

Créditos  

Proyecto desarrollado por Kleber Molina para la materia **Integración Mecatrónica**.  
