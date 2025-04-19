# Problemas de Tiro Parabólico (con solución)

## Problema 1: Alcance y altura máxima
Un proyectil es lanzado con una velocidad inicial de **50 m/s** y un ángulo de **30°**. Calcula:  
a) La altura máxima alcanzada.  
b) El alcance horizontal.

### Solución:
**Datos:**  
$v_0 = 50 \, \text{m/s}$, $\theta = 30°$, $g = 9.8 \, \text{m/s}^2$.

**a) Altura máxima ($H$):**
``` math
v_{0y} = v_0 \sin(\theta) = 50 \cdot \sin(30°) = 25 \, \text{m/s}
```  
``` math
H = \frac{v_{0y}^2}{2g} = \frac{25^2}{2 \cdot 9.8} \approx 31.89 \, \text{m}
```

**b) Alcance ($R$):**  
``` math
R = \frac{v_0^2 \sin(2\theta)}{g} = \frac{50^2 \cdot \sin(60°)}{9.8} \approx 220.92 \, \text{m}
```

---

## Problema 2: Tiempo de vuelo
Un balón es pateado con un ángulo de **45°** y una velocidad de **20 m/s**. ¿Cuánto tiempo permanece en el aire?

### Solución:
**Datos:**  
$v_0 = 20 \, \text{m/s}$, $\theta = 45°$.  
``` math
v_{0y} = 20 \cdot \sin(45°) \approx 14.14 \, \text{m/s}
```  
``` math
t_v = \frac{2 v_{0y}}{g} = \frac{2 \cdot 14.14}{9.8} \approx 2.89 \, \text{s}
```

---

## Problema 3: Velocidad inicial desconocida
Un objeto alcanza una altura máxima de **40 m** cuando es lanzado con un ángulo de **60°**. ¿Cuál fue su velocidad inicial?

### Solución:
**Datos:**  
$H = 40 \, \text{m}$, $\theta = 60°$.  
``` math
H = \frac{v_{0y}^2}{2g} \implies v_{0y} = \sqrt{2gH} = \sqrt{2 \cdot 9.8 \cdot 40} \approx 28 \, \text{m/s}
```  
``` math
v_0 = \frac{v_{0y}}{\sin(60°)} = \frac{28}{\sin(60°)} \approx 32.33 \, \text{m/s}
```

---

## Problema 4: Ángulo óptimo para máximo alcance
¿Con qué ángulo debe lanzarse un proyectil para que su alcance sea el doble de su altura máxima?

### Solución:
Queremos $R = 2H$.  
Sabemos que:  
``` math
R = \frac{v_0^2 \sin(2\theta)}{g}, \quad H = \frac{v_0^2 \sin^2(\theta)}{2g}
```  
Igualando $R = 2H$:  
``` math
\frac{v_0^2 \sin(2\theta)}{g} = 2 \cdot \frac{v_0^2 \sin^2(\theta)}{2g}
```  
Simplificando:  
``` math
\sin(2\theta) = \sin^2(\theta) \implies 2 \sin(\theta) \cos(\theta) = \sin^2(\theta)
```  
``` math
2 \cos(\theta) = \sin(\theta) \implies \tan(\theta) = 2 \implies \theta \approx 63.43°
```

---

## Problema 5: Trayectoria y posición
Una pelota se lanza desde el suelo con $v_0 = 15 \, \text{m/s}$ y $\theta = 37°$. Determina:  
a) Su posición a los **2 segundos**.  
b) La ecuación de su trayectoria $y(x)$.

### Solución:
**Datos:**  
$v_0 = 15 \, \text{m/s}$, $\theta = 37°$, $sin(37°) \approx 0.6$, $\cos(37°) \approx 0.8$.

**a) Posición en $t = 2 \, \text{s}$:**  
``` math
x = v_{0x} \cdot t = 15 \cdot 0.8 \cdot 2 = 24 \, \text{m}
```  
``` math
y = v_{0y} \cdot t - \frac{1}{2} g t^2 = 15 \cdot 0.6 \cdot 2 - 4.9 \cdot 4 \approx 18 - 19.6 = -1.6 \, \text{m}
```  
*(La pelota está cayendo, ya que $y < 0$).*

**b) Ecuación de la trayectoria:**  
``` math
y(x) = \tan(\theta) \cdot x - \frac{g}{2 v_{0x}^2} x^2 = 0.75 \, x - 0.034 \, x^2
```

---