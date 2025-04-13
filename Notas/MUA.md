# Movimiento Uniformemente Acelerado (MUA)
***Indice***\
[Fórmulas](#fórmulas-del-movimiento-uniformemente-acelerado-muamrua)
## 📌 Definición
El **movimiento uniformemente acelerado (MUA)** es aquel en el que un móvil experimenta cambios **constantes** en su velocidad debido a una aceleración constante.
---
## 🔍 Características Principales 🤙
1. **Aceleración constante**:  
   - Misma magnitud, dirección y sentido en todo el movimiento.  
2. **Trayectoria rectilínea**:  
   - Si $\vec{a}$ y $\vec{v}$ son colineales (misma línea de acción).  
3. **Cambio lineal de velocidad**:  
   - La velocidad varía proporcionalmente al tiempo.  

---
## 📈 Gráficas del MUA
1. **Aceleración vs. Tiempo ($a$ vs $t$)**:  
   - Recta horizontal ($a = \text{cte}$).  
2. **Velocidad vs. Tiempo ($v$ vs $t$)**:  
   - Línea recta con pendiente $= a$.  
3. **Posición vs. Tiempo ($d$ vs $t$)**:  
   - Parábola (concavidad depende del signo de $a$).  

![Gráficas MUA](https://images.squarespace-cdn.com/content/v1/5326238be4b055350d9396f4/1504449926748-QXGSX7VRY9386DEXN6U7/mua-Gr%C3%A1ficas-Resumen.png)  
*(Ejemplo de gráficas: posición, velocidad y aceleración)*.  

---

## 🌟 Ejemplo Práctico
**Problema**:  
Un automóvil parte del reposo ($v_0 = 0$) y acelera a $2\, \text{m/s}^2$ durante $5\, \text{s}$.  
**Calcular**:  
1. Velocidad final.  
2. Distancia recorrida.  

**Solución**:  
1. $v = v_0 + a t = 0 + (2\, \text{m/s}^2)(5\, \text{s}) = 10\, \text{m/s}$.  
2. $\Delta x = v_0 t + \frac{1}{2} a t^2 = 0 + \frac{1}{2}(2)(5)^2 = 25\, \text{m}$.  

---

## ⚠️ Casos Especiales
- **Aceleración negativa (desaceleración)**:  
  - La velocidad disminuye (ej: frenado de un coche).  
- **Caída libre**:  
  - Movimiento vertical con $a = g$ ($g = 9.8\, \text{m/s}^2$).
- **Tiro Vertical**:
  - Movimiento vertical con $a = -g$ ($g = -9.8\, \text{m/s}^2$).
- **Tiro parabólico**:
  - Movimiento en dos dimensiones.

> [!NOTE]
> Los movimientos antes mencionados se verán en otro documento.

---

## 🔄 Relación con MRU
| **MRU**                     | **MUA**                      |
|------------------------------|------------------------------|
| Velocidad constante ($a=0$). | Velocidad variable ($a \neq 0$). |
| $\Delta x = v \cdot t$.      | $\Delta x = v_0 t + \dfrac{1}{2} a t^2$. |

---
# Fórmulas del Movimiento Uniformemente Acelerado (MUA/MRUA)

| Fórmula                          | Variables                                                                 | Descripción                                                                 |
|-----------------------------------|---------------------------------------------------------------------------|-----------------------------------------------------------------------------|
| $v = v_0 + a·t$                   | **v**: Velocidad final (m/s)<br>**v₀**: Velocidad inicial (m/s)<br>**a**: Aceleración (m/s²)<br>**t**: Tiempo (s) | Velocidad en función del tiempo.                                             |
| $x = x₀ + v₀·t + \dfrac{at^2}{2}$         | **x**: Posición final (m)<br>**x₀**: Posición inicial (m)                 | Desplazamiento (con posición inicial).                                      |
| $v² = v₀² + 2·a·(x - x₀)$        | **Δx**: Distancia recorrida (x - x₀)                                      | Relación entre velocidad y distancia (sin tiempo).                           |
| $Δx = v₀·t + \dfrac{at^2}{2}$             | **Δx**: Distancia recorrida (m)                                           | Versión simplificada si x₀ = 0.                                             |
| $Δx = (v + v₀)·\dfrac{t}{2}$            |                                                                           | Distancia recorrida usando velocidad promedio.                               |
| $a = \dfrac{v - v_0}{t}$               |                                                                           | Definición de aceleración (si es constante).                                 |
---

## 📊 Ecuaciones Fundamentales
| Variable       | Ecuación                          | Descripción                          |
|----------------|-----------------------------------|--------------------------------------|
| **Velocidad**  | $v = v_0 + a \cdot t$            | Velocidad final en función del tiempo. |
| **Posición**   | $x = x_0 + v_0 t + \frac{1}{2} a t^2$ | Desplazamiento (con posición inicial $x_0$). |
| **Sin tiempo** | $v^2 = v_0^2 + 2a \Delta x$      | Relación entre velocidad y distancia. |

Donde:  
- $v_0$: Velocidad inicial (m/s).  
- $a$: Aceleración (m/s²).  
- $t$: Tiempo (s).  
- $\Delta x$: Distancia recorrida (m).  
---
## 📌 Casos Especiales

| Situación                       | Fórmula Aplicable                          | Notas                                                                       |
|----------------------------------|--------------------------------------------|-----------------------------------------------------------------------------|
| **Parte del reposo** (v₀ = 0)    | $v = a·t$<br>$Δx = \dfrac{at^2}{2}$                 | Ejemplo: Caída libre inicial.                                               |
| **Se detiene** (v = 0)           | $0 = v₀² + 2·a·Δx$                         | Útil para calcular distancia de frenado.                                    |
| **Aceleración negativa**         | $a$ se reemplaza por $-a$                  | Ejemplo: Frenado ($a = -3 m/s²$).                                           |

## ⚠️ Notas Clave
1. **Unidades**: Todas las magnitudes deben estar en el **Sistema Internacional** (metros, segundos, m/s²).
2. **Trayectoria**: Las fórmulas asumen movimiento **rectilíneo**.
3. **Signos**: 
   - $a > 0$: Aceleración (aumenta velocidad).
   - $a < 0$: Desaceleración (disminuye velocidad).

## 🌟 Ejemplo Práctico
**Problema**: Un coche acelera desde 10 m/s con $a = 2 m/s²$ durante 5 s.  
**Solución**:  
- Velocidad final: $v = 10 + (2)(5) = 20 m/s$  
- Distancia: $Δx = (10)(5) + \dfrac{(2)(5)²}{2} = 50 + 25 = 75 m$  