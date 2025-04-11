## Problemas de Caída Libre

### Problema 1: Tiempo de Caída
Un objeto se deja caer desde lo alto de un edificio de **80 metros** de altura.  
**Calcular**:  
a) El tiempo que tarda en llegar al suelo.  
b) La velocidad con la que impacta.  

**Datos**:  
- Altura inicial $h_0$ = 80 m  
- Velocidad inicial $v_0$ = 0 m/s  
- Aceleración $g$ = 9.81 m/s²  

**Solución**:  
a) Usando $h = h_0 + v_0 t + \dfrac{1}{2} g t^2$:  
```math
\displaystyle 0 = 80 + 0 \cdot t + \dfrac{1}{2} (-9.81) t^2 \implies t = \sqrt{\frac{2 \cdot 80}{9.81}} \approx 4.04 \quad \text{s}
```
b) Usando $v = v_0 + g t$:  
$v = 0 + (-9.81) \cdot 4.04 \approx -39.6 \quad \text{m/s}$
> [!NOTE]
> *(El signo negativo indica dirección hacia abajo)*  

---

### Problema 2: Altura desde la que cae  
Un objeto tarda **3 segundos** en caer libremente hasta el suelo.  
**Calcular**:  
a) La altura desde la que fue soltado.  
b) Su velocidad al llegar al suelo.  

**Datos**:  
- Tiempo $t = 3 0 s$  
- $v_0 = 0 \quad \text{m/s}$  
- $g = 9.81 \quad \text{m/s}^2$  

**Solución**:  
a) $h = \dfrac{1}{2} g t^2 = \dfrac{1}{2} \cdot 9.81 \cdot (3)^2 \approx 44.1 \quad \text{m}$  
b) $v = g \cdot t = 9.81 \cdot 3 \approx 29.4 \quad \text{m/s}$

---

### Problema 3: Velocidad inicial hacia abajo  
Se lanza una piedra **hacia abajo** desde un puente a **12 m/s** y tarda **2 s** en llegar al agua.  
**Calcular**:  
a) La altura del puente.  
b) La velocidad final al tocar el agua.  

**Datos**:  
- $v_0 = 12 \quad \text{m/s}$ (hacia abajo)  
- $t = 2 \quad \text{s}$  
- $g = 9.81 \quad \text{m/s}^2$  

**Solución**:  
a) $h = v_0 t + \dfrac{1}{2} g t^2 = 12 \cdot 2 + \dfrac{1}{2} \cdot 9.81 \cdot (2)^2 \approx 24 + 19.62 = 43.62 \quad \text{m}$  
b) $v = v_0 + g t = 12 + 9.81 \cdot 2 \approx 31.62 \quad \text{m/s}$  

---
> [!NOTE]  
> Se considera $g = 9.81 \quad \text{m/s}^2$ (positivo si el eje apunta hacia abajo).  
> En el **Problema 1**, el signo negativo en la velocidad indica dirección descendente.  

## Problemas de Tiro Vertical

### Problema 1: Altura máxima y tiempo de vuelo
Se lanza una pelota verticalmente hacia arriba con una velocidad inicial de **25 m/s**.  
**Calcular**:  
a) La altura máxima alcanzada.  
b) El tiempo total de vuelo hasta regresar al punto de lanzamiento.  

**Datos**:  
- $v_0 = 25 \, \text{m/s}$ (hacia arriba)  
- $g = 9.81 \, \text{m/s}^2$ (hacia abajo)  
- $v_f = 0 \, \text{m/s}$ (en altura máxima)  

**Solución**:  
a) $h_{max} = \dfrac{v_0^2}{2g} = \dfrac{(25)^2}{2 \times 9.81} \approx 31.86 \, \text{m}$  
b) $t_{total} = \dfrac{2v_0}{g} = \dfrac{2 \times 25}{9.81} \approx 5.10 \, \text{s}$  

---

### Problema 2: Velocidad inicial desde altura conocida  
Un cohete de juguete alcanza una altura máxima de **45 metros** al ser lanzado verticalmente.  
**Calcular**:  
a) La velocidad inicial de lanzamiento.  
b) El tiempo que tarda en alcanzar la altura máxima.  

**Datos**:  
- $h_{max} = 45 \, \text{m}$  
- $g = 9.81 \, \text{m/s}^2$  

**Solución**:  
a) $v_0 = \sqrt{2gh_{max}} = \sqrt{2 \times 9.81 \times 45} \approx 29.71 \, \text{m/s}$  
b) $t_{subida} = \dfrac{v_0}{g} = \dfrac{29.71}{9.81} \approx 3.03 \, \text{s}$  

---

### Problema 3: Lanzamiento con velocidad inicial hacia abajo  
Desde un edificio de **60 m** de altura, se lanza una piedra hacia abajo con $v_0 = 8 \, \text{m/s}$.  
**Calcular**:  
a) El tiempo que tarda en llegar al suelo.  
b) La velocidad con la que impacta.  

**Datos**:  
- $h_0 = 60 \, \text{m}$  
- $v_0 = 8 \, \text{m/s}$ (hacia abajo)  
- $g = 9.81 \, \text{m/s}^2$  

**Solución**:  
a) $h = h_0 + v_0 t + \dfrac{1}{2}gt^2$  
$0 = 60 + 8t + 4.905t^2$  
Resolviendo la ecuación cuadrática: $t \approx 2.96 \, \text{s}$  
> [!TIP]
> Es un procedimiento de fórmula general o factorización.

b) $v_f = v_0 + gt = 8 + (9.81 \times 2.96) \approx 37.04 \, \text{m/s}$  

---
> [!NOTE]
> En todos los problemas se desprecia la resistencia del aire.  
> En el **Problema 3**, se considera positivo el sentido hacia abajo.  
> $g$ se toma como $9.81 \, \text{m/s}^2$ (valor estándar).  