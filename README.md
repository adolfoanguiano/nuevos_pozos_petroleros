
Este proyecto fue elaborado en el Bootcamp de TripleTen.
# Proyecto: Selección de los mejores lugares de pozos petroleros para OilyGiant

## Introducción

La compañia de extracción de petróleo OilyGiant requiere encontrar **los mejores 200 lugares** para abrir pozos petroleros.

Este es un proyecto predictivo de Machine Learning, en dónde se creó un modelo para predecir el volumen de reservas en los pozos nuevos,  de los cuáles se podrán elegir los que tengan valores más altos y con ésto la región con el beneficio total más alto para los pozos seleccionados.

Los pasos llevado a cabo fueron:
**1. Preparación de Datos**
Se hace la limpieza de los datos para poder trabajar con ellos.
**2. Entrenamiento y validación de un módelo predictivo**
Obtenemos 3 modelos, 1 por cada región y obtenemos el **RMSE** (Raiz del Error Cuadrático Médio) que sirve para saer que tan lejos del promedio se encuentran las predicciones del modelo.
**3. Se realiza el cáluclo de ganacias**
Se obtiene el cálculo de ganacia por región
**4. Se análiza los riesgos y ganancias por región**
Se genera una función que señale los riesgos y ganancias para que se pueda aplicar a cada región.

