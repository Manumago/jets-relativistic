# Simulación de radiación sincrotrón y beaming relativista en jets astrofísicos

Este repositorio contiene una simulación numérica del movimiento de un electrón relativista en un campo magnético compuesto (poloidal y toroidal), con el objetivo de estudiar los efectos de **beaming relativista** y la **emisión sincrotrón** en jets astrofísicos.

El proyecto forma parte de un estudio sobre cómo la geometría del campo magnético y la relatividad especial determinan la direccionalidad y la intensidad de la radiación emitida por partículas cargadas en movimiento.

---

## Contenido

- `Jets_relativistasgit.ipynb` — Notebook principal con:
  - Integración numérica de las ecuaciones de movimiento relativistas.
  - Cálculo del factor Doppler y la intensidad aparente del beaming.
  - Visualización de trayectorias helicoidales y curvas de luz.
  - Análisis de la dependencia angular de la emisión.

---

## Metodología

El modelo considera un electrón relativista que se mueve bajo la acción de un campo magnético:
\[
\mathbf{B} = B_0 \hat{z} + B_\phi(r)\, \hat{\phi}, \quad \text{con} \quad B_\phi \propto \frac{1}{r}
\]

Las ecuaciones del movimiento se integran en el marco del laboratorio utilizando unidades naturales o del SI, con una condición inicial determinada por el factor de Lorentz \(\gamma_0\).  
Se analiza la **direccionalidad de la radiación** mediante el factor Doppler:
\[
D = \frac{1}{\gamma (1 - \boldsymbol{\beta} \cdot \hat{n})}
\]
y la intensidad observada, proporcional a \(D^p\), con \(p \simeq 3\) para emisión sincrotrón.

---

## Resultados esperados

- Trayectorias helicoidales del electrón alrededor del eje del jet.  
- Curvas de luz que muestran la modulación del beaming con el ángulo del observador.  
- Comparación entre distintos factores de Lorentz \(\gamma_0\).  
- Visualización de los conos de emisión y zonas de máxima intensidad.

---

## Autora

**Manuela Marín Gómez**  
Estudiante de Astronomía — Universidad de Antioquia  

---

## Licencia

Este proyecto se publica con fines académicos y de divulgación científica.  
Puedes usar el código y las simulaciones con el debido crédito a la autora.

