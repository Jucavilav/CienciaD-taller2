## Ciencia de Datos
* Taller 2
* Juan Carlos Avila Villalba
* Ciencia de Datos Aplicada
* Universidad de los Andes

### Entendimiento de los datos

Para entrenar el modelo de regresión, se verifico que todas las entradas son numéricas y se denominan dentro del conjunto como (Features).

![Imagen 1](https://github.com/Jucavilav/CienciaD-taller2/assets/127565867/85105068-1125-4b0b-a025-5881ba99a82a)

Las variables de entrada como la variable objetivo [incomeperperson] no contienen valores vacíos. (Como decisión de ajuste, se han eliminado los registros null y duplicados)

![Imagen 2](https://github.com/Jucavilav/CienciaD-taller2/assets/127565867/1c0cc75a-e8d1-4fac-9ec2-a17847b49061)

![Imagen 3](https://github.com/Jucavilav/CienciaD-taller2/assets/127565867/5328191a-1aa5-4167-a823-318153f0e1c7)

### Interpretación del modelo.

En el modelo inicial, están muy dispersos y no se ve una correlación fuerte ente el PIB y las variables Co2, Femaleemploy, employ, y algo de relación a mayor PIB, mayor internetuser.

![Imagen 4](https://github.com/Jucavilav/CienciaD-taller2/assets/127565867/16788487-c414-4a16-9f0d-1c74157dcff7)

#### Métricas de error

* Las métricas de error para el dataset de entrenamiento y prueba son muy similares.

![Imagen 5](https://github.com/Jucavilav/CienciaD-taller2/assets/127565867/2b70a981-b3a4-4745-b02e-67a2f7140259)


* Para el conjunto de prueba los valores de la variable objetivo están centrados en 6.531 y 8.820, mientras que el 75% de los errores de estimación del modelo se encuentran por debajo de 6.328, muy por debajo de la desviación estándar.

![Imagen 6](https://github.com/Jucavilav/CienciaD-taller2/assets/127565867/95c9d09f-24c5-4f81-81ed-fa12c3efe6e9)

![Imagen 7](https://github.com/Jucavilav/CienciaD-taller2/assets/127565867/f76aad42-74dd-4c47-a043-f904c2219d9a)

![Imagen 8](https://github.com/Jucavilav/CienciaD-taller2/assets/127565867/bd0eb403-d48d-42ba-92ee-454d0a5fb2ab)

### ¿Qué conjunto de políticas públicas recomendaría implementar, a partir de la premisa de que la mejora en estas áreas indicaría al Banco Mundial que el país es estable, está en una trayectoria de desarrollo sostenible y tiene la capacidad de administrar y reembolsar préstamos de manera efectiva?

Como vimos los resultados anteriormente co2emissions, employrate y internetuserdate, tienen relación lineal positiva, razón por la cual es importante que en un país se trabaje en estos aspectos para demostrar que es un país estable, sostenible y preocupado por su desarrollo.

#### Recomendaciones como país:

1.	Fomentar la conectividad de internet del país para lograr que todas las personas tengan el acceso a la misma, ya que esto hace que se pueda expandir el comercio tanto interno como con otros países, fomentando la competencia, la facilidad de presentar productos y obtención de crecimiento rápido en los negocios.

2.	Aumentar los empleos del país, reduce la pobreza y garantiza prosperidad y estabilidad en el país, este aumento se apalanca con la inclusión de las mujeres al trabajo, con la capacitación de profesionales y apoyo a las empresas y emprendimientos del sector público y privado.  
