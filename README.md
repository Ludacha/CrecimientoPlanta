## ⚙️ Métodos Aplicados

### 🔹 Interpolación

- **Newton**
- **Lagrange**
- **Splines cúbicos**

### 🔸 Ajuste de Curva (Modelo Sigmoide)

Se utilizó la siguiente fórmula:

\[
y(t) = \frac{H}{1 + e^{-(a + bt)}}
\]

Donde:
- \( y(t) \): altura de la planta
- \( t \): tiempo en días
- \( H = 102 \): altura máxima estimada
- \( a, b \): parámetros obtenidos por ajuste numérico

---

## ✅ Resultados

- **Parámetro a**: `-2.6882`
- **Parámetro b**: `0.1271`
- 📍 **Altura estimada al día 40**: `93.49 pulgadas` (usando el modelo sigmoide)
- !Gráfico de modelos en el documento pdf

referencia
- Chapra, S. C., & Canale, R. P. (2015). *Métodos numéricos para ingenieros* (7ª ed.). McGraw-Hill Education.
- Modelo sigmoide provisto en el enunciado del proyecto.
