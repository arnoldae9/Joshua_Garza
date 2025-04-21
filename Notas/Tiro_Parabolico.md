# Tiro Parabólico

## Definición 📓
El **tiro parabólico** es un movimiento realizado por un objeto que es lanzado con una velocidad inicial y sigue una trayectoria curva bajo la influencia de la gravedad. Es la combinación de:
- **Movimiento horizontal (MRU)**: Velocidad constante (sin aceleración).
- **Movimiento vertical (MRUV)**: Aceleración constante debido a la gravedad $g = 9.8 \text{m/s}^2$.
> [!CAUTION]
> El problema se puede resolver en dos "partes" pero los dos movimientos están sucediendo al mismo tiempo.

## Componentes de la Velocidad Inicial 📒
- **Velocidad horizontal** $v_{0x}$
  $$v_{0x} = v_0 \cdot \cos(\theta)$$
- **Velocidad vertical $v_{0y}$**:  
  $$v_{0y} = v_0 \cdot \sin(\theta)$$
> [!TIP]
> Aquí volvemos a utilizar el tema de [Vectores](Vectores.md).

## Ecuaciones Básicas

### Posición
- **Horizontal (x)**:  
  $x(t) = v_{0x} \cdot t$
- **Vertical (y)**:  
  $y(t) = v_{0y} \cdot t - \frac{1}{2} g t^2$

### Velocidad
- **Horizontal**: Constante $v_x = v_{0x}$.
- **Vertical**:  $v_y(t) = v_{0y} - g \cdot t$

### Tiempo de Vuelo $t_v$
Tiempo total hasta que el objeto regresa al suelo $y = 0$:  
$t_v = \frac{2 v_{0y}}{g}$
> [!WARNING]
> Hay que tener cuidado en los problemas que no son lanzados desde el suelo.

### Alcance Horizontal $R$
Distancia máxima horizontal:  
$R = v_{0x} \cdot t_v = \frac{v_0^2 \sin(2\theta)}{g}$
> [!TIP]
> Se suele usar la letra $R$, pero es cotidiano el uso de $X$.

### Altura Máxima $H$
Punto más alto de la trayectoria:  
$H = \frac{v_{0y}^2}{2g}$

## Ejemplo de Trayectoria 📝
La ecuación de la trayectoria en términos de $x$ es:  
$y(x) = \tan(\theta) \cdot x - \frac{g}{2 v_{0x}^2} x^2$
> [!NOTE]
> Este tema no es muy normal en un curso de ingreso.