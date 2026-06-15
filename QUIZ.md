# Quiz Teórico — Fundamentos (20 puntos)

> **Primeros 20 minutos de la sesión.** Individual, a libro cerrado. Repasa los
> fundamentos vistos en el primer mes (Intro, Circuitos Digitales y Arquitecturas
> Programables) antes de pasar a la parte práctica.

Responde de forma breve y precisa. Cada pregunta vale **4 puntos**.

1. **Chips.** Define y diferencia *procesador*, *CPU*, *MCU* y *SoC*.

2. **Arquitecturas.** ¿Qué distingue a las arquitecturas **RISC** y **CISC**?
   Da un ejemplo de cada una e indica dónde recae la complejidad (hardware vs.
   compilador) y su implicación en consumo de energía.

3. **Abstracción digital.** El mundo real es ruidoso. Explica cómo la abstracción
   digital permite representar información de forma confiable usando niveles de
   voltaje.

4. **Lógica combinacional.** ¿Qué es un dispositivo combinacional y por qué sus
   elementos deben ser estáticos? Da un ejemplo.

5. **Periféricos.** Enumera los tres pasos para inicializar y usar un periférico
   en el STM32. ¿Por qué hay que habilitar primero su reloj, y por qué se usan
   operaciones a nivel de bits (*bitwise*)?

---

## Banco para rotación

Preguntas equivalentes para alternar entre semestres (mismo nivel, 4 puntos):

- **Arquitecturas.** Diferencia las arquitecturas **Von Neumann** y **Harvard**.
  ¿Qué consecuencia tiene cada una sobre los buses de instrucción y datos?
- **Toolchain.** Describe las cuatro etapas que convierten un programa en C a un
  ejecutable binario (preprocesado, compilación, ensamblado, enlazado).
- **Buses.** ¿Qué es el *ancho del bus de datos* y cómo se relaciona con la
  cantidad de información que un MCU procesa por vez?
- **Cortex-M.** ¿Por qué se dice que el Cortex-M es una máquina *load/store*?
  ¿Qué dos categorías de instrucciones acceden a memoria?
- **Reloj.** ¿Qué papel cumple el reloj del sistema (*system clock*) y por qué su
  frecuencia condiciona el comportamiento de los periféricos?
