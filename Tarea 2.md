# Investigación sobre Arquitecturas de Computación Avanzadas

**Autor:** Yossed Mauricio Riaño Paez  
**Universidad:** Universidad Santo Tomás  

---

## 1. Computación Cuántica

### ¿Qué es?
La computación cuántica es un modelo de cómputo basado en los principios de la mecánica cuántica. A diferencia de los computadores clásicos que utilizan **bits** (0 o 1), los computadores cuánticos utilizan **qubits**, que pueden estar en **superposición** de estados.

<img width="475" height="633" alt="image" src="https://github.com/user-attachments/assets/4fb36a19-9113-46d1-9cfd-6dc7606b8b1e" />


### Arquitectura de un computador cuántico
- **Qubits:** unidades fundamentales de información.
- **Compuertas cuánticas:** manipulan el estado de los qubits.
- **Memoria cuántica:** almacenamiento temporal de estados cuánticos.
- **Procesador cuántico (QPU):** núcleo de cómputo cuántico.
- **Sistema de control clásico:** coordina la interacción entre hardware cuántico y programas clásicos.
- **Sistemas de enfriamiento:** los qubits requieren temperaturas cercanas al cero absoluto para mantener su estabilidad.

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/5ae223d8-52b5-4be1-b3b0-2f19aa88cff9" />

### Historia
- 1980s: Richard Feynman y David Deutsch plantean la idea de simuladores cuánticos.
- 1994: Peter Shor desarrolla un algoritmo cuántico para factorizar números.
- 2000s: aparecen prototipos de empresas como IBM, Google y D-Wave.
- Actualidad: en fase experimental, con avances hacia la **supremacía cuántica**.

### Ventajas
- Resolución de problemas imposibles para computadoras clásicas.
- Alta velocidad en algoritmos de optimización y criptografía.
- Simulación de sistemas moleculares y físicos.

### Desventajas
- Difícil de escalar (requiere condiciones extremas).
- Vulnerabilidad a la **decoherencia cuántica**.
- Caro y poco accesible.

### Conceptos fundamentales
- **Superposición:** un qubit puede estar en 0 y 1 al mismo tiempo.
- **Entrelazamiento:** estados de dos qubits se correlacionan aunque estén separados.
- **Interferencia cuántica:** permite amplificar resultados correctos y cancelar errores.
- **Medición probabilística:** el resultado depende de probabilidades, no es determinista.
- **Desafío de decoherencia:** pérdida de información por interacción con el entorno.
- **Comunicación cuántica:** incluye teletransporte cuántico y distribución de claves cuánticas.
- **Compuertas cuánticas:** operaciones como Hadamard, CNOT, Pauli-X, Z.

---

## 2. Computador Neuromórfico

### ¿Qué es?
Es un tipo de computador inspirado en el funcionamiento del cerebro humano. Utiliza **redes de neuronas artificiales** en hardware para procesar información de manera similar a como lo hace el sistema nervioso.

<img width="236" height="214" alt="image" src="https://github.com/user-attachments/assets/e45d14b2-7b0b-49f6-b5f3-5aa9fd7b9e07" />


### Arquitectura y funcionamiento
- **Neuronas artificiales:** unidades de procesamiento que simulan las biológicas.
- **Sinapsis electrónicas:** conexiones que ajustan pesos según el aprendizaje.
- **Procesamiento paralelo:** múltiples nodos trabajan al mismo tiempo.
- **Señales analógicas y digitales:** para imitar los impulsos neuronales.

### Ventajas
- Bajo consumo energético.
- Alta capacidad de procesamiento paralelo.
- Ideal para aplicaciones de inteligencia artificial.

### Desventajas
- Tecnología emergente, aún limitada.
- Difícil de programar y entrenar.
- Costos elevados de investigación y fabricación.

### Hardware utilizado
- **Memristores** (memoria + resistencia).
- Chips especializados como **Loihi** (Intel) y **TrueNorth** (IBM).
- Dispositivos híbridos digitales/analógicos.

### Tipos de computación neuromórfica
- **Basada en hardware digital:** usa chips programables.
- **Basada en hardware analógico:** más cercana al cerebro real.
- **Sistemas híbridos:** combinación de ambos enfoques.

---

## 3. Ordenador Biológico

### ¿Qué es?
Un ordenador biológico utiliza **materiales vivos** (como ADN, proteínas o células) para realizar procesos computacionales.

<img width="236" height="213" alt="image" src="https://github.com/user-attachments/assets/0903ce5c-f59a-4e69-8216-59c8d6094034" />


### Arquitectura
- **Biomoléculas como información:** ADN y ARN representan datos.
- **Reacciones químicas:** actúan como operaciones lógicas.
- **Procesamiento paralelo masivo:** millones de moléculas interactúan simultáneamente.

### Tipos
- **Computación con ADN.**
- **Computación molecular.**
- **Computación celular (con bacterias o células vivas).**

### Principales hitos
- 1994: Leonard Adleman resolvió un problema matemático con ADN.
- Avances en biocomputación sintética y almacenamiento de datos en ADN.
- Uso potencial en medicina personalizada y biología sintética.

---

## 4. Computación Heterogénea

### ¿Qué es?
Es una arquitectura que combina distintos tipos de procesadores (CPU, GPU, FPGA, ASICs) en un mismo sistema para aprovechar sus fortalezas.

<img width="600" height="580" alt="image" src="https://github.com/user-attachments/assets/b72e0673-3269-42d5-8843-16b35827e95c" />


### Historia
- Surge con la necesidad de acelerar cálculos científicos y gráficos (años 2000).
- Impulsada por **CUDA de NVIDIA** y arquitecturas paralelas.

### Ventajas
- Mejor aprovechamiento de recursos.
- Alta eficiencia en tareas específicas.
- Rendimiento optimizado para IA y Big Data.

### Desventajas
- Mayor complejidad en programación.
- Dificultad en compatibilidad y estandarización.
- Costos de implementación más altos.

---

## 5. Computación de Borde (Edge Computing)

### ¿Qué es?
Es un modelo de computación que acerca el procesamiento de datos al lugar donde se generan (dispositivos IoT, sensores, routers), reduciendo la necesidad de enviar todo a la nube.

<img width="1909" height="1129" alt="image" src="https://github.com/user-attachments/assets/b391d6dd-c910-4614-b83a-78ac52ce79a6" />


### Historia
- Surge con el crecimiento del **Internet de las Cosas (IoT)**.
- Adoptado por grandes empresas en la década de 2010 (Cisco, Amazon, Microsoft).

### Ventajas
- Baja latencia (respuestas rápidas).
- Menor consumo de ancho de banda.
- Mayor privacidad al procesar datos localmente.

### Desventajas
- Menor capacidad que la nube.
- Gestión y mantenimiento más complejos.
- Requiere infraestructura distribuida.

---

