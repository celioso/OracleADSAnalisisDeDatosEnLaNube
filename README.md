# Oracle ADS análisis de datos en la nube

### Para saber más: Free Tier

Oracle ofrece la opción de crear una cuenta gratuita, en la cual el usuario tendrá USD 300 (trescientos dólares) de créditos disponibles durante 30 días para la utilización de los servicios pagos.

Para poder crear una cuenta gratuita (Free Trial) necesitarás reunir los siguientes requisitos:

- Una cuenta de e-mail válida;
- Permiso para recibir un SMS para la verificación por texto (en caso de que el e-mail no sea reconocido);
- Y una tarjeta de crédito disponible para el registro (Atención: No habrá cobro de factura durante el período de Free Trial).
**Observación**: Las interfaces mostradas en las imágenes a continuación podrían ser diferentes de la interfaz que utilizarás cuando realices el curso.

1. Abre tu navegador web a través de [Oracle Cloud Free](https://www.oracle.com/cloud/free/ "Oracle Cloud Free") para poder tener acceso al formulario de registro de **Oracle Cloud**.

![web Oracle Cloud Free](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/18.jpg "web Oracle Cloud Free")

2. Digita la información solicitada, en el formulario anterior, para proseguir con la creación de tu conta:

- En el campo País/Territorio, selecciona tu país;
- En los campo Nombre y Apellido, coloca tu nombre y apellido respectivamente;
- En el campo E-mail, digita tu e-mail.
3. Con los campos llenos, Elige la opción **Soy humano** y, en seguida, haz clic en el botón **Verificar mi e-mail**.

4. Accede al buzón de entrada de tu e-mail y verifica si recibiste un e-mail de validación de la cuenta de Oracle, semejante al siguiente.

![Buzon de entrada de tu e-mail](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/19.jpg "Buzon de entrada de tu e-mail")

5. En el e-mail mostrado en el paso anterior, selecciona **Click here**. En seguida, serás redireccionado a una página donde podrás proseguir con la creación de tu cuenta.

6. En los campos presentados en esta página, digita la siguiente información:

- **Contraseña:** Escoge y digita una contraseña;
- **Nombre de la Empresa:** Coloca el nombre de la empresa donde trabajas (campo opcional);
- **Nombre de cuenta de Cloud:** Es generado automáticamente con base en tus respuestas al formulario. Es posible alterar este nombre borrándolo y digitando un nuevo nombre de usuario(a). Es importante guardar esta información, pues la vas a necesitar al momento de hacer login en **Oracle Cloud**;
- **Región Local:** Selecciona tu región de origen.

![infotrmacion de contacto](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/20.jpg "infotrmacion de contacto")

7. Con los campos debidamente diligenciados, haz clic en **Continuar**.

![Terminos de uso](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/21.jpg "Terminos de uso")

8. En el próximo formulario, debes digitar tu dirección, Número de identificación y número de teléfono. En seguida, haz clic en **Continuar**.

![informacion de direccion](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/22.jpg "informacion de direccion")

9. En la siguiente pantalla de "Verificación de pago", haz clic en la opción **Añadir método de verificación de pago**.

![direccion de contacto](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/23.jpg "direccion de contacto")

10. Seguidamente, selecciona la opción Credit Card y digita los datos de tu tarjeta de crédito.

![metodo de pago](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/24.jpg "metodo de pago")

11. Cuando la verificación de tu tarjeta se haya concluído, podrás revisar y aceptar el contrato haciendo clic en la caja de selección localizada abajo del Contrato.

![contrato](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/25.jpg "contrato")

12. Después de haber hecho esto, selecciona la opción **Iniciar mi evaluación gratuita**.

13. Recibirás un primer e-mail de Oracle notificando que la creación de tu cuenta está siendo procesada. Finalizada esta etapa, recibirás un segundo e-mail informando que el proceso fue concluído y que ya puedes acceder a tu cuenta.

### Preparando el ambiente

Ahora que accedimos al ambiente Oracle, vamos a aprender a configurarlo. Para ello, necesitamos seguir los siguientes pasos: La configuración de un *stack*, la configuración del ambiente de *Data Science* y la configuración de sesión del notebook. Entonces, te presento a continuación el paso a paso de la creación de cada etapa, recordando que es necesario que antes hayas realizado el login en tu cuenta de Oracle.

**Observación:** Las interfaces mostradas en las imágenes a continuación pueden variar con respecto a las que encontrarás cuando vayas a utilizar el ambiente Oracle.

**Configurando el Stack**

1.  Haz clic en la esquina superior izquierda de la pantalla para abrir el menú. Después, selecciona al opción **Developer Services** y, en seguida, en la sección de **Resource Manager**, haz clic sobre **Stacks**.

![Stacks](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/1.jpg "Stacks")

2. En **Stack**s, haz clic en la opción **Create Stack** que está localizada en la columna central de la pantalla.

![pantalla](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/2.jpg "pantalla")

3. Allí, selecciona la opción **Template** y, en el área de **Stack Configuration**, haz clic en **Select Template**.

![create stack](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/3.jpg "create stack")

4. Ahora, vamos a seleccionar el **Template** que queremos utilizar. Para ello, accede a la segunda pestaña de esta pantalla, llamada **Service**. En seguida, escoge la opción Data **Science** que está localizada en la mitad de la pantalla, y para finalizar, haz clic en el botón **Select Template** que se encuentra en la parte inferior de la página.

![Browse Templates](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/4.jpg "Browse Templates")

5. Para continuar con la criación del *stack*, haz clic sobre **Next**.

![next](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/5.jpg "next")

6. En la pantalla **Create Stack**, no es necesario marcar ninguna de las cajas de selección. Solamente debes hacer clic sobre **Next**.

![configure variables](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/6.jpg "configure variables")

7. En la página de Review, puedes verificar un resumen de todo el proceso de creación realizado hasta el momento. No es necesario realizar ninguna selección en esta parte. Para continuar, basta hacer clic sobre **Create**.

![review](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/7.jpg "review")

8. Con el *stack* creado, ahora es necesario accederlo. Para ello, haz clic sobre el nombre del stack. Este nombre se encuentra en la columna **Name** de la tabla presentada en el centro de la pantalla.

![stacks](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/8.jpg "stacks")

9. Ahora que el *stack* está seleccionado, es necesario aplicarle las configuraciones que se definieron hasta el momento. Para ello, debes hacer clic sobre **Apply**.

![RMS](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/9.jpg "RMS")

**Configurando el servicio**

1. Haciendo clic sobre el menú sandwich, en la esquina superior izquierda, selecciona la opción **Analytics & AI** y, en donde aparece** Machine Learning**, haz clic en **Data Science**.

![Analytics & AI](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/10.jpg "Analytics & AI")

2. En la pantalla **Projects**, haz clic en el botón **Create project**.

![proyecto](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/11.jpg "proyecto")

3. En el área de **Create Project**, puedes llenar el campo **Name** con el nombre del proyecto y el campo **Description** con la descripción del mismo. En seguida, debes hacer clic en **Create**.

![create proyect](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/12.jpg "create proyect")

4. Con el proyecto creado, ahora es necesario accederlo. Para ello, basta hacer clic sobre el nombre del proyecto. El mismo se encuentra en la columna **Name** de la tabla presentada en la mitad de la pantalla.

![proyect 2](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/13.jpg "proyect 2")

**Configurando la sección del Notebook**

**Observación:** La creación del notebook, puede demorar más de lo que se espera. En caso de ser así, no te preocupes, es completamente normal.

1. Con el proyecto seleccionado, vamos a avanzar a la última parte del proceso de configuración que es la creación de una sección del notebook. Para comenzar, debes hacer clic sobre el botón **Create notebook session**, localizado en la columna central de la pantalla.

![Curso Oracle ADS](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/14.jpg "Curso Oracle ADS")

2. En la pantalla de **Create notebook** session, debes seleccionar el notebook que deseas utilizar. En **Compute shape**, hacia el centro de la pantalla, nota que ya contamos con un notebook seleccionado por defecto. Pero, para visualizar las otras opciones de notebook, debes hacer clic sobre el botón gris de **Select** que se encuentra al lado derecho de la página.

![Create notebook session](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/15.jpg "Create notebook session")

3. En la página de **Select compute**, enccontrarás máquinas con diferentes características pre-configuradas. Para seleccionar la misma máquina utilizada en el curso, haz clic en la opción **Intel**, localizada hacia la derecha de tu pantalla. En seguida, selecciona la tercera caja de selección denominada **VM Standard 2.4** y haz clic en el botón **Select**, en la esquina inferior izquierda de la pantalla.

![select compute](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/16.jpg "select compute")

4. Con la máquina seleccionada, ahora debes establecer el espacio de almacenamiento para ella. Para hacer esto, en el campo Block storage size (in GB) puedes digitar 50, que es el valor mínimo de almacenamiento que puedes utilizar. Posteriormente, en los dos campos de la sección de **Network resources** puedes hacer clic sobre las flechas localizadas en las esquinas de los campos y seleccionar las redes por defecto que aparecen (normalmente los nombres de ellas son algo semejante a **Data Science VCN** y **Data Science - Private**, respectivamente). Para finalizar la creación de la sección de notebook basta hacer clic sobre "Create" localizado en la esquina inferior izquierda de la pantalla.

![final](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/17.jpg "final")

### Haga lo que hicimos en aula

Llegó la hora de que sigas todos los pasos realizados por mí durante esta aula. En caso de que ya lo hayas hecho, excelente. Si aún no lo hiciste, es importante que ejecutes lo que vimos en los videos para poder continuar con nuestra próxima aula.

### Lo que aprendimos

Lo que aprendimos en esta aula:

- Crear y configurar un ambiente **Data Science** para trabajar dentro del ecosistema Oracle;
- Realizar la configuración de un **Stack** en Oracle;
- Crear y configurar un proyecto en Oracle;
- Crear y configurar un notebook en Oracle; y
- Preparar el ambiente dentro del notebook Oracle.

### Proyecto del aula anterior
¿Comenzando en esta etapa? Aquí puedes descargar los archivos del proyecto que hemos avanzado hasta el aula anterior. (Recuerda que estamos trabajando en el Notebook del ecosistema de nube de Oracle )

En el siguiente enlace hallarás el [dataset](https://www.kaggle.com/datasets/dileep070/heart-disease-prediction-using-logistic-regression "dataset") que usaremos en este entrenamiento.

[Descargue los archivos en Github](https://github.com/ahcamachod/1897-oracle-ads-analisis-de-datos-en-la-nube/blob/aula-2/notebook_analisis_salud-aula_2.ipynb "Descargue los archivos en Github") o haga clic[ aquí](https://github.com/ahcamachod/1897-oracle-ads-analisis-de-datos-en-la-nube/archive/refs/heads/aula-2.zip " aquí") para descargarlos directamente.

### Para saber más: diferentes tipos de DataFrame

Existen diferentes tipos de DataFrames; el más conocido de ellos es el de la biblioteca Pandas. Pero, además de este, tenemos otros tipos pertenecientes a otras bibliotecas, como es el caso del **ADS DataFrame** que aprendimos en los últimos videos. Cada uno de estos tipos poseen sus características específicas y pueden ser utilizados en diferentes situaciones.

Vamos a aprender algunas características adicionales de estos DataFrames y también a conocer un poco sobre la biblioteca **Dask**.

 - **Pandas**
Pandas es una biblioteca escrita en Python, utilizada para el análisis y la manipulación de datos. El **Pandas DataFrame** es una estructura de datos bidimensional que puede almacenar datos de diferentes tipos (enteros, floats, datos categóricos, strings, entre otros) en columnas. Su formato es similar al de una planilla de Excel, siendo compuesto por filas y columnas.

[DataFrame](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/26.jpg "DataFrame")

Las principales características de este DataFrame son:

- Fácil aprendizaje;
- Almacena diferentes tipos de datos;
- Tratamiento flexible y simple de datos faltantes;
- Acepta algunas operaciones aritméticas;
- Fácil manipulación.

Sin embargo, el uso de esta biblioteca no es muy indicado para trabajar con un gran volumen de datos. Esto se debe a que Pandas necesita que todos los datos estén prontamente disponibles en la memoria de tu computador y ello genera una limitación de la cantidad de datos con los cuales podemos trabajar y exigiendo mucho de nuestra máquina.

 - **Dask**

Dask es una biblioteca creada para la computación paralela en Python, ella funciona bien con otras bibliotecas como **Pandas**, **Numpy**, **Scikit-learn**, entre otras. El **Dask DataFrame** se compone de muchos **Pandas DataFrames**, lo que hace que la manera como el computador trabaja con los comandos en este tipo de DataFrame sea diferente.

[Pandas DataFrames](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/27.jpg "Pandas DataFrames")

La forma diferente de trabajo de Dask se da por una característica de este en atrasar tareas, en la cual, él prepara un conjunto de transformaciones o cálculos para una ejecución posterior en paralelo. Esta estructura es diferente de otras funciones en Python que son computadas instantáneamente, al momento en que son llamadas.

De esta forma, el atraso de tareas de Dask permite que esta biblioteca lidie muy bien con un conjunto de datos muy grande o con muchos grupos en sus datos, lo cual es una ventaja sobre Pandas, que necesitaría de un poder de procesamiento muy alto para lidiar con datos como estos.

- ADS

ADS es una biblioteca Python que hace parte del servicio de Data Science de **Oracle Cloud Infrastructure (OCI)**. Esta biblioteca posee una interfaz amigable y métodos que abarcan toda la parte de análisis y de manipulación de datos. El **ADS DataFrame** es una estructura de datos basado en Pandas; de esta forma, cualquier operación que se pueda ejecutar en un **Pandas DataFrame** también puede ser aplicada en un conjunto de datos ADS.

En el ambiente Oracle, es más interesante utilizar funciones específicas de ADS debido a la mayor compatibilidad con el ambiente. Por ello, durante el curso optaremos por utilizar las funciones de ADS en vez de las de otras bibliotecas como Pandas y Dask.
deactivate
### Para saber más: relación entre diabetes y glicemia

El principal carbohidrato existente en el torrente sanguíneo es la glucosa (azúcar). Durante el día la cantidad de glucosa varía, lo cual es normal y está intimamente relacionado a nuestros hábitos de vida. El término glicemia se refiere a la cantidad de glucosa en la sangre, y en condiciones normales, los valores de referencia para la glicemia son:

- Glicemia en ayuno de 8 a 12 horas: 70 a 110 mg/dL;
- Glicemia después de comer o sobrecarga de glucosa: Hasta 200mg/dL.
Existe también un rango intermediario que debe ser considerado como señal de alerta para un cambio de hábitos alimenticios; este rango de glicemia se concentra entre 110 y 126 mg/dL en ayuno.

Cuando una persona presenta valores de glicemia por encima de estos rangos, esta persona es hiperglicémica y posee diabetes de tipo *mellitus*. Ahora bien, cuando una persona presenta valores de glicemia por debajo de estos rangos, ella es hipoglicémica y posee diabetes de tipo *insipidus*.

En caso de que desees entender más sobre la diabetes y sus tipos, te sugerimos la lectura del siguiente artículo:[ ¿Cuál es la diferencia entre la diabetes tipo 1, 2, 3 y gestacional?](https://temassobresalud.com/diferencia-diabetes/ " ¿Cuál es la diferencia entre la diabetes tipo 1, 2, 3 y gestacional?")

### Desafío: rellenar las celdas de forma selectiva

Al analizar nuestra base de datos, percibimos que existen algunos datos nulos en la columna de ‘glicemia’. Explorando más a fondo estos datos faltantes y relacionándolos con la columna de ‘diabetes’, identificamos que existem 337 datos nulos de ‘glicemia’ para las personas sin diabetes y 2 para personas con diabetes.

Considerando esto, rellena nuevamente los valores faltantes de la columna ‘glicemia’, pero esta vez, utilizando un abordaje diferente:

- Primero, reinicie el Kernel y ejecuta sus celdas de código, con excepción de la celda con el código de para rellenar las celdas con valores NaN: `ds.fillna({'glicemia': 81.8})`.

- Para las personas con diabetes, rellena los datos nulos de la columna ‘glicemia’ con el promedio de glicemia para las personas con diabetes (este valor ya fue calculado en el aula):

```python
personas_con_diabetes = ds[ds.diabetes == 1]
promedio_personas_con_diabetes = personas_con_diabetes .glicemia.mean()
```

Para las personas sin diabetes, rellena los datos nulos de la columna ‘glicemia’ con el **promedio de ‘glicemia’ para personas sin diabetes** (este valor ya fue calculado en el aula, también):

```python
personas_sin_diabetes = ds[ds.diabetes == 0]
promedio_personas_sin_diabetes = personas_sin_diabetes .glicemia.mean()
```

### Opinión del instructor

Para resolver este desafío, no vamos a utilizar la función `ads.fillna()`, sino que vamos a elaborar una función que recorre todos los registros de nuestro dataset y verifica si el dato es nulo. Cuando sea nulo, necesitamos verificar si la persona es diabética o no y sustituir el valor nulo por el promedio de la población dependiendo de la condición, y adicionarlo a una lista.

Ya cuando el valor no es nulo, simplemente vamos a añadirlo a la lista. De esta forma, al final de la función tendremos una lista con todos los valores sin registros nulos.

```python
def promedio_segun_diabetes(df, personas_con_diabetes, personas_sin_diabetes):
    nueva_glicemia = []
    for i, row in df.iterrows():
        if np.isnan(row.glicemia):
            if row.diabetes == 1:
                nueva_glicemia.append(personas_con_diabetes.glicemia.mean().round(2))
            elif row.diabetes == 0:
                nueva_glicemia.append(personas_sin_diabetes.glicemia.mean().round(2))
        else:
            nueva_glicemia.append(row.glicemia)
    return nueva_glicemia
```
Antes de aplicar la nueva lista al DataFrame, será necesario resetear los índices del DataFrame, pues el número del índice no es continuo debido a los drops que tuvieron lugar durante la ejecución de las transformaciones.

```python
nueva_glicemia = promedio_segun_diabetes(df, personas_con_diabetes, personas_sin_diabetes)
serie_glicemia = pd.Series(nueva_glicemia)
ds = ds.reset_index()
ds = ds.assign_column('glicemia_nueva', serie_glicemia)
```

### Haga lo que hicimos en aula

Llegó la hora de que sigas todos los pasos realizados por mí durante esta aula. En caso de que ya lo hayas hecho, excelente. Si aún no lo hiciste, es importante que ejecutes lo que vimos en los videos para poder continuar con nuestra próxima aula.

**Video Archivos externos**

```python
# Importando la biblioteca pandas
import pandas as pd

# Creando um objeto Pandas DataFrame
datos = pd.read_csv('framingham.csv')

# Visualizando la cantidad de filas y columnas del DataFrame
datos.shape

# Visualizando los nombres de las columnas del DataFrame
datos.columns

# Visualizando las 5 primeras filas del DataFrame
dados.head()
```
**Video Cargando el CSV**
```python
# Importando la biblioteca ADS para crear un ADS DataSet
import ads

# Utilizando DatasetFactory para crear un Dataset ADS
from ads.dataset.factory import DatasetFactory

# Creando un Dataset ADS
ds = DatasetFactory.open('framingham.csv')

# Mostrando el tipo de objeto ds
type(ds)

# Mostrando el tipo de objeto datos
type(datos)

# Mostrando el Dataset ds
ds

# Creando el diccionario que contiene el nombre de las columnas en inglés como llave y su traducción al español como valor
dict_ing_esp = {
                     'male': 'sexo',
                     'age': 'edad',
                     'education': 'escolaridad',
                     'currentSmoker': 'fumador',
                     'cigsPerDay': 'cigarrillos_por_dia',                     
                     'BPMeds': 'uso_medicamento_presion',
                     'prevalentStroke': 'acv',
                     'prevalentHyp': 'hipertension',
                     'diabetes': 'diabetes',
                     'totChol': 'colesterol_total',
                     'sysBP': 'presion_arterial_sistolica',
                     'diaBP': 'presion_arterial_diastolica',
                     'BMI': 'imc',
                     'heartRate': 'frecuencia_cardiaca',
                     'glucose': 'glicemia',
                     'TenYearCHD': 'riesgo_eac_decada'
}

# Renombrando las columnas
ds =ds.rename_columns(columns=dict_ing_esp)

# Mostrando el nombre de las columnas 
ds.columns

# Mostrando las 5 primeras filas de ds
ds.head()

# Excluyendo la columna ‘escolaridad’
ds = ds.drop_columns('escolaridad')

# Mostrando nuevamente el nombre de las columnas
ds.columns
```
**Video Creando un ADS DataFrame**
```python
# Mostrando la clasificación estadística y los tipos de valores de cada columna del DataFrame
ds.summary()

# Mostrando los valores únicos de la columna ‘cigarrillos_por_dia’
ds.cigarrillos_por_dia.unique()

# Mostrando la cantidad total de valores nulos en cada columna del DataFrame
ds.isnull().sum()

# Creando un vector booleano (True y False) que posee el valor True en las filas donde la columna ‘cigarrillos_por_dia’ no posee valores nulos
seleccion_correctos = ds.cigarrillos_por_dia.notnull()

# Aplicando la selección de la variable seleccion_correctos al DataFrame
ds = ds[seleccion_correctos]

# Realizando la selección de filas no nulas con notnull de las columnas  ‘uso_medicamento_presion’, ‘colesterol_total’, ‘imc’ y ‘frecuencia_cardiaca’
ds = ds[ds.uso_medicamento_presion.notnull()]
ds = ds[ds.colesterol_total.notnull()]
ds = ds[ds.imc.notnull()]
ds = ds[ds.frecuencia_cardiaca.notnull()]
```

**Video Tratamiento de datos faltantes**

```python
# Creando un subset solamente con las personas diabéticas
personas_con_diabetes = ds[ds.diabetes == 1]

# Creando un subset solamente con las personas no diabéticas
personas_sin_diabetes = ds[ds.diabetes == 0]

# Mostrando las 5 primeras filas de la columna ‘glicemia’ del subset                         # personas_con_diabetes  
personas_con_diabetes.glicemia.head()

# Verificando el promedio de glicemia para personas diabéticas
personas_con_diabetes.glicemia.mean()

# Verificando el promedio de glicemia para personas no diabéticas
personas_sin_diabetes.glicemia.mean()

# Exhibiendo estadísticas descriptivas de la columna 'glicemia'
ds.glicemia.describe()

# Conteo del número de valores en la columna 'diabetes'
ds.diabetes.value_counts()

# Importando la biblioteca Seaborn de visualización de datos
import seaborn as sns

# Creando una gráfica de distribución de diabetes
ax = sns.distplot(personas_con_diabetes.glicemia, norm_hist=False)

# Definiendo los valores para inicio y fin del eje x en la gráfica
ax.set_xlim(0,400)

# Creando el mismo gráfico para personas sin diabetes
ax = sns.distplot(personas_sin_diabetes.glicemia, norm_hist=False)
ax.set_xlim(0,400)

# Seleccionando solamente los datos para glicemia que son nulos.
nulos = ds.glicemia.isnull()

# Seleccionando las filas con valores nulos de glicemia en la columna ‘diabetes’ y  contando los datos
ds[nulos].diabetes.value_counts()

# Calculando el promedio de valores de la columna ‘glicemia’
ds.glicemia.mean()

# Llenando los datos faltantes en la columna ‘glicemia’ con el valor 81.8 y aplicando la sustitución directamente en el dataset
ds.fillna({'glicemia': 81.8}, inplace = True)
```

### Lo que aprendimos

Lo que aprendimos en esta aula:

- Importar la base de datos utilizando la biblioteca `pandas`;
- Importar la base de datos utilizando la biblioteca `ads`;
- Manipular **ADS DataFrames**;
- Tratar datos faltantes utilizando el método `fillna()`; y
- Identificar diferentes tipos de **DataFrame**.

### Proyecto del aula anterior

¿Comenzando en esta etapa? Aquí puedes descargar los archivos del proyecto que hemos avanzado hasta el aula anterior. (Recuerda que estamos trabajando en el Notebook del ecosistema de nube de Oracle)

[Descargue los archivos en Github](https://github.com/ahcamachod/1897-oracle-ads-analisis-de-datos-en-la-nube/blob/aula-3/notebook_analisis_salud-aula_3.ipynb "Descargue los archivos en Github") o haga clic [aquí](https://github.com/ahcamachod/1897-oracle-ads-analisis-de-datos-en-la-nube/archive/refs/heads/aula-3.zip "aquí") para descargarlos directamente.

### Para saber más: tipos de datos

En los estudios anteriores utilizamos el método `astype()` para definir los tipos de datos. Pudimos notar que además de la definición del tipo de variable hay otra definición que involucra la clasificación estadística de cada columna.

La clasificación estadística tiene que ver con la definición del tipo de dato que será trabajado con respecto al significado de lo que contiene; para entender mejor sobre la clasificación estadística y los tipos de variables puedes acceder al siguiente [enlace](https://economipedia.com/definiciones/variable-estadistica.html "enlace").

Podemos establecer una similaridad entre los conceptos citados y los parámetros formulados por la biblioteca ADS:

Cada uno de los parámetros ADS puestos en la tabla puede ser definido con el método `astype()` de acuerdo con su tipo de dato.

En las aulas anteriores, el instructor definió la columna 'cigarrillos_por_dia' como 'int64' y la columna 'uso_medicamento_presion' como 'int64' a través de la función `astype()` y la clasificación estadística solo fue repetida de la especificada por el propio ADS:

```python
ds = ds.astype(types={
    'cigarrillos_por_dia': 'int64',
    'cigarrillos_por_dia': 'ordinal',
    'uso_medicamento_presion': 'int64',
    'uso_medicamento_presion': 'categorical'
})
```
Sin embargo, notamos que la columna 'cigarrillos_por_dia' fue establecida como tipo ordinal por ADS. Pero, según las descripciones de cada tipo de clasificación estadística, es más interesante asociar los valores de esta columna como valores cuantitativos, o con ADS, valor continuous, dado que realiza un conteo discreto de valores.

Entretanto, con la columna 'uso_medicamento_presion' no tenemos este problema de asociación, ya que los datos de esta son binarios categorizando si ha habido o no (1 o 0) el uso de medicamentos para la presión.

### Para saber más: transformando datos categóricos

La función `cut()`, de la biblioteca Pandas, tiene como objetivo separar un conjunto de datos en categorías. Para que esta categorización sea realizada, esta función necesita recibir 2 atributos principales:

- x: matriz con los datos a ser categorizados;
- bins: Lista de límites o cantidade de categorías.
Esta función también posee el atributo `labels` para el cual podemos pasar los títulos de cada una de las categorías. No obstante, este atributo es opcional, o sea, no necesitamos asignar nombres a cada una de las categorías.

Esta función es muy utilizada cuando queremos categorizar datos contínuos. Para entender mejor la aplicación de esta función, considera el siguiente DataFrame:

```python
df = pd.DataFrame({'Nombre': ['Andrés', 'Catia', 'Denis', 'Beto', 'Bruna', 'Darío'], 
                        'Edad': [5, 27, 15, 16, 19, 8]},  
                        columns = ['Nombre', 'Edad'])
```

![nombre](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/28.jpg "nombre")

Supongamos que deseamos crear una tercera columna indicando si cada una de esas personas son niños, adolescentes o adultos con base en los valores presentados en la columna "Edad".

Para hacer esto, necesitamos primeramente definir una lista de límites para los valores de la edad, o sea, vamos a definir hasta qué edad la persona debe ser considerada como niño, adolescente e así sucesivamente. De esta manera, vamos a crear la lista `limites_edades`:

```python
limites_edades = [1,13,18,60]
```

Con esta lista, estamos definiendo 3 intervalos de edad, siendo ellos:

- Intervalo 1: De 1 a 13;
- Intervalo 2: De 14 a 18;
- Intervalo 3: De 19 a 60.
Ahora, vamos a crear una lista con categorías para cada uno de estos intervalos:
```python
categorias = ['Niño(a)', 'Adolescente', 'Adulto(a)']
```

Con estas dos listas creadas, podemos utilizar la función `cut()` para generar una tercera columna clasificando a las personas en niño(a), adulto(a) o adolescente de acuerdo con su edad. Para ello, colocaremos como parámetro la columna "Edad" de nuestro DataFrame para el atributo x, la lista `limites_edades` para el atributo `bins` y la lista `categorias` para el atributo labels:
```python
rango_edad = pd.cut(x = df.Edad, 
                     bins = limites_edades, 
                     labels = categorias)
```
Para finalizar, basta crear una nueva columna en el DataFrame `df` y configurar la columna `rango_edad` con el resultado de la función `cut()`:
```python
df['Rango_edad'] = rango_edad
```
El DataFrame resultante será igual a:

![DataFrame](https://caelum-online-public.s3.amazonaws.com/ESP+-+1897+-+Oracle+ADS%3A+an%C3%A1lisis+de+datos+en+la+nube/29.jpg "DataFrame")

¡Te felicito! Ahora nuestro DataFrame `df` posee también la columna "Rango_edad" con las categorías que definimos de acuerdo con la columna "Edad".

### Para saber más: análisis exploratorio

El análisis exploratorio es una parte muy importante en el desarrollo de un proyecto de datos. Esta etapa consiste en el análisis y la investigación del conjunto de datos, con la finalidad de entender y resumir sus principales características utilizando la visualización de datos y otros recursos de exploración.

**¿Por qué el análisis exploratorio es tan importante?**

Es durante esta etapa de exploración que el profesional de ciencia de datos logra identificar algunas características del conjunto de datos, como:

- errores;
- datos nulos;
- desbalanceo de datos;
- tipos de datos dispuestos en cada columna;
- relación entre las variables; y
- distribución de los valores de cada columna.

**El método ads.show_in_notebook()**

Utilizar el método `show_in_notebook()` es una excelente manera de iniciar el proceso de exploración de los datos. Esto porque, este método retorna diversas informaciones sobre nuestra base de datos, como: tipos de datos, correlación entre las variables, avisos (warnings) y gráficos de distribución de cada columna.

Sin embargo, la utilización de esta herramienta no sustituye la importancia de realizar un análisis exploratorio de forma más manual y profunda. Solo así, vas a conocer la base de datos de forma más detallada, identificar sus principales problemas y, con ello, obtener más ideas de cómo tratar y manipular tus datos de la mejor manera.

### Desafío: grafica una columna

Estudiamos como la visualización de datos es importante en el proceso de conocer mejor los datos. También observamos que la biblioteca ADS tiena algunas funciones específicas que nos ayudan a hacer esta visualización de forma eficiente.

Ahora es tu turno: realiza una gráfica de una de las columnas que aún no fue explorada con las funciones de la biblioteca ADS.

### Opinión del instructor

Para resolver este desafío, puedes emplear la función `ads.plot()` para crear la visualización ideal (según ADS):

```python
ads.plot('<nombre_de_la_coluna>')
```

### Haga lo que hicimos en aula

Llegó la hora de que sigas todos los pasos realizados por mí durante esta aula. En caso de que ya lo hayas hecho, excelente. Si aún no lo hiciste, es importante que ejecutes lo que vimos en los videos para poder continuar con nuestra próxima aula.

**Video Preparando los datos**

```python
# Verificando el tipo de datos y estadístico para cada columna
ds.summary()

# Modificando el tipo de la variable ‘cigarrillos_por_dia’
ds = ds.astype(types={'cigarrillos_por_dia':'int64'})

# Modificando el tipo de la variable ‘uso_medicamento_presion’
ds = ds.astype(types={'uso_medicamento_presion':'int64'})

# Verificando el tipo de datos y estadístico nuevamente
ds.summary()
```
**Video Ejecutando las transformaciones**
```python
# Verificando las estadísticas descriptivas de la variable ‘cigarrillos_por_dia’
ds.cigarrillos_por_dia.describe()

# Creando un gráfico de distribución de la variable ‘cigarrillos_por_dia’
ax = sns.distplot(ds.cigarrillos_por_dia, norm_hist=False)
ax.set_xlim(0,70)

# Verificando la cantidad de fumadores y de no fumadores
ds.fumador.value_counts()

# Realizando una gráfica boxplot de la variable ‘cigarrillos_por_dia’
sns.boxplot(ds.cigarrillos_por_dia)

# Verificando el promedio de ‘cigarrillos_por_dia’
ds.cigarrillos_por_dia.mean()

# Definiendo las categorías de acuerdo con la cantidad de cigarrillos consumidos por día:
#               0 - no fumador;
#               1 - fumador leve (1 a 10 cigarrillos por día);
#               2 - fumador moderado (11 a 20 cigarrillos por día);
#               3 - fumador severo (más de 20 cigarrillos por día).
categorias = [0,1,2,3]

# Definiendo los límites para categorizar a los fumadores
limites = [-1, 1, 11,21, 71]

# Creando una variable categórica basada en límites y rótulos utilizando Pandas Cut
categoria_de_fumador = pd.cut(ds.cigarrillos_por_dia, limites, labels=categorias)

# Creando una columna con los datos resultantes de categoria_de_fumador 
ds = ds.assign_column('categoria_de_fumador', categoria_de_fumador)

# Verificando las columnas del DataFrame
ds.columns
```
**Video Visualizando datos con ADS**

```python
# Función que devuelve la visualización de las estadísticas descriptivas del DataFrame, Gráficos de distribución de todas las variables, correlación y avisos sobre los datos
ds.show_in_notebook()

# Generando la gráfica ideal para la variable target del DataFrame
ds.target.show_in_notebook()
```
**Video Generando más visualizaciones**
```python
# Generando la gráfica ideal para la variable ‘glicemia’
ds.plot('glicemia')

# Generando la gráfica ideal para la variable ‘diabetes’
ds.plot('diabetes')

# Graficando las variables ‘glicemia’ y ‘diabetes’ en una misma gráfica
ds.plot('glicemia', 'diabetes')

# Graficando las variables ‘categoria_de_fumador’ y ‘acv’ en una misma gráfica
ds.plot('categoria_de_fumador', 'acv')

# Transformando el ADS DataFrame en un Pandas DataFrame
pandas_ds = ds.to_pandas()

# Graficando la distribución de los datos de variable contra variable
sns.pairplot(pandas_ds)
```

### Lo que aprendimos

Lo que aprendimos en esta aula:

- Analizar y a preparar datos en el ambiente de Oracle;
- Transformar los tipos de datos con ADS;
- Realizar el análisis exploratorio con `show_in_notebook()`;
- Representar gráficos con ADS.

### Proyecto del aula anterior

¿Comenzando en esta etapa? Aquí puedes descargar los archivos del proyecto que hemos avanzado hasta el aula anterior.(Recuerda que estamos trabajando en el Notebook del ecosistema de nube de Oracle)

[Descargue los archivos en Github](https://github.com/ahcamachod/1897-oracle-ads-analisis-de-datos-en-la-nube/blob/aula-4/notebook_analisis_salud-aula_4.ipynb "Descargue los archivos en Github") o haga clic [aquí](https://github.com/ahcamachod/1897-oracle-ads-analisis-de-datos-en-la-nube/archive/refs/heads/aula-4.zip "aquí") para descargarlos directamente.

### Para saber más: correlación

La correlación determina el grado de asociación entre dos variables, por ejemplo:

- El precio de un carro y el precio de su seguro;
- la edad y el costo de un plan de salud;
- Masa corporal y altura.
Pero no siempre esta asociación entre las variables es una relación fácil de ser identificada. De esa forma, existen los coeficientes de correlación que son los responsables por determinar el grado de "fuerza" de la correlación entre dos variables y también su dirección.

**Coeficiente de Correlación de Pearson**

También conocido como "ρ de Pearson" mide cuánto dos variables contínuas son correlacionadas. Dicho coeficiente puede variar de -1 a 1, donde estos valores indican:

- Valores de 0 a -0.3 ou 0 a 0.3: - correlación irrelevante;
- Valores de -0.3 a -0.5 ou 0.3 a 0.5: correlación debil;
- Valores de -0.5 a -0.7 ou 0.5 a 0.7: correlación moderada;
- Valores de -0.7 a -0.9 ou 0.7 a 0.9: correlación fuerte;
- Valores de -0.9 a -1 ou 0.9 a 1: correlação muy fuerte.
Para medir el grado de correlación de variables que no son contínuas existen otros coeficientes de correlación que pueden ser utilizados, como el de Spearman, Kendall, entre otros. Si deseas conocer un poco más sobre estos otros métodos, te sugiero leer más sobre [Correlación](https://www.probabilidadyestadistica.net/correlacion/ "Correlación").

### Haga lo que hicimos en aula

Llegó la hora de que sigas todos los pasos realizados por mí durante esta aula. En caso de que ya lo hayas hecho, excelente. Si aún no lo hiciste, es importante que ejecutes lo que vimos en los videos para poder continuar con nuestra próxima aula.

**Video Correlación**

```python
# Visualizando la tabla de correlaciones
ds.corr()

# Importando las bibliotecas necesarias para usar el mapa de calor
import matplotlib.pyplot as plt

# Creando el lienzo para la figura en un tamaño determinado
plt.figure(figsize=[8,6])

# Creando una paleta de colores para el mapa de calor
paleta = sns.color_palette('light:salmon', as_cmap=True)

# Creando el heatmap a partir de la tabla de correlación y de la paleta creada
sns.heatmap(ds.corr(), annot=True, cmap=paleta)
```
**Video ADS y sugerencias automáticas**
```python
# Verificando las sugerencias que ADS realiza para el Dataset
ds.suggest_recommendations()
```
**Video Aplicando sugerencias**
```python
# Creando un nuevo ADS DataFrame a partir de la base original
base_original = DatasetFactory.open('framingham.csv', target='TenYearCHD')

# Traduciendo los nombres de las columnas
base_original = base_original.rename_columns(dict_ing_esp)

# Verificando las sugerencias que ADS realiza para el dataset
base_original.suggest_recommendations()

# Transformando la base original con base en las recomendaciones
base_original = base_original.auto_transform()

# Visualizando la base pós alteraciones
base_original.show_in_notebook()
```
**Video Comparado las bases**
```python
# Visualizando la base que fue modificada manualmente
ds.show_in_notebook()
```
### Lo que aprendimos

Lo que aprendimos en esta aula:

- Encontrar la correlación de los datos con ADS;
- Verificar sugerencias de ajuste al banco de datos;
- Aplicar las sugerencias de ADS al conjunto de datos;
- Identificar qué es la correlación.

### Proyecto del aula anterior

¿Comenzando en esta etapa? Aquí puedes descargar los archivos del proyecto que hemos avanzado hasta el aula anterior. (Recuerda que estamos trabajando en el Notebook del ecosistema de nube de Oracle)

[Descargue los archivos en Github](https://github.com/ahcamachod/1897-oracle-ads-analisis-de-datos-en-la-nube/blob/aula-5/notebook_analisis_salud-aula_5.ipynb "Descargue los archivos en Github") o haga clic[ aquí](https://github.com/ahcamachod/1897-oracle-ads-analisis-de-datos-en-la-nube/archive/refs/heads/aula-5.zip " aquí") para descargarlos directamente.

### Para saber más: balanceo de datos

Los datos desbalanceados son aquellos que poseen muchos registros para una categoría y pocos para otra. Por ejemplo, imagina que estamos trabajando con datos sobre el oceano y queremos verificar las condiciones en las cuales se presenta un maremoto.

Si tenemos datos de todos los días de un año, es bastante probable que existan muchos más datos de mar normal que de maremoto. Con eso, podemos tener dificultades en localizar los datos que se refieren a esta condición específica.

De la misma forma, si nuestro interés es crear algún modelo que pueda prever, basado en los datos, si habrá un tsunami, el modelo puede tener dificultades debido a la pequeña cantidad de datos sobre maremoto.

Por ello, existen técnicas conocidas como balanceo de datos. Estas técnicas realizan precisamente un balanceo, igualando el número de registros que se refieren a días con y sin maremoto.

Estas técnicas se dividen en dos vertientes principales: upsampling o sobremuestreo y downsamping o submuestreo.

Las técnicas de sobremuestreo consisten en crear (basados en los registros existentes) nuevos registros para la clase que aparece menos, hasta que la cantidad de registros para ambas clases se iguale. Por otro lado, las técnicas de submuestreo consisten en excluir registros de la clase que más aparece hasta que se tenga la misma cantidad de registros para ambas clases.

Cada una de estas técnicas se adecúa mejor a diversas situaciones. A continuación discutiremos algunas ventajas y desventajas de cada una de estas técnicas.

**Upsampling**

- Ventajas
 - Aumenta el número de registros.
 - Facilita a criação de modelos de ML.
- Desventajas
 - Crea distorsiones al Dataframe.
 - Genera registros que no corresponden con la realidad.
**Downsampling**
- Ventajas
 - No cria distorções no Dataframe.
- Desventajas
 - Disminuye la cantidad de registros.

 ### Para saber más: documentación de datos

La documentación es una buena práctica del área de software, cuando estamos escribiendo código, es importante que hagamos comentarios explicando lo que las funciones realizan, por ejemplo.

Quando trabajamos con datos, también es importante mantener la documentación de aquello que hacemos y para ello, empleamos metadatos. Los metadatos son datos sobre los datos. Cuando creamos un texto, o cualquier otro documento que habla sobre cuales son los datos y cómo estos están distribuídos en un `.csv`, por ejemplo, estamos creando metadatos.

Estos son útiles pues les permiten a las otras personas conocer los datos de una forma eficiente, así como aclarar la información sobre cuáles transformaciones los datos sufrieron y también cuál es el contexto de los datos. Una buena documentación permite que otras personas comprendan tu trabajo y puedan continuarlo.

### Desafío: documenta tus conclusiones

¡Ahora, es tu turno de documentar los datos!

Crea una sección de conclusiones en la documentación de los datos y anota tus impresiones sobre lo que aprendiste con la exploración de los datos.

### Opinión del instructor

En la documentación es importante insertar la información que consideras más importante luego de análizar el conjunto de datos. También incluye algún aprendizaje que crees que las personas que trabajarán con estos datos deben saber, como la relación entre diabetes y glicemia.

Si lo deseas, te invito a compartir en el foro tus conclusiones y compararlas con las de tus compañeros de curso.

### Haga lo que hicimos en aula

Llegó la hora de que sigas todos los pasos realizados por mí durante esta aula. En caso de que ya lo hayas hecho, excelente. Si aún no lo hiciste, es importante que ejecutes lo que vimos en los videos para poder continuar con nuestra próxima aula.

**Video Balanceo de datos**

```python
# Verificando el balanceo de la variable target
ds.target.show_in_notebook()

# Verificando el porcentaje de valores positivos y negativos
ds.riesgo_EAC_decada.value_counts(normalize=True)
```
**Video Aplicando el balanceo**

```python
# Instalando la biblioteca imbalanced-learn
!pip install imbalanced-learn

# Importando la biblioteca imbalanced-learn
import imblearn

# Efectuando el balanceo por up_sample
ds = ds.up_sample(sampler='default')

# Visualizando la variable target balanceada
ds.target.show_in_notebook()

# Visualizando datos del DataFrame
ds.show_in_notebook()
```
**Video Documentación de datos**

```python
#Generando una descripción para el DataFrame
descripcion = """
- Información general: Esta base de datos se refiere a un estudio realizado recolectando datos sobre el estado de salud de los pacientes para tratar de clasificar el riesgo de enfermedad coronaria en los próximos 10 años. Para consultar la base original, puede acceder al siguiente [link](https://www.kaggle.com/dileep070/heart-disease-prediction-using-logistic-regression).

Los datos fueron modificados con el objetivo de corregir los problemas de la base y dejarla lista para poder realizar modelos empleando Machine Learning.

-Tipo de las Columnas:
- 'sexo': booleano,
- 'edad': numérico,
- 'cigarrillos_por_dia': categórico,                                                                   - 'uso_medicamento_presion': booleano
      - 'acv': booleano,
         - 'hipertension': booleano,
         - 'diabetes': booleano,
          - 'colesterol_total': numérico,
         - 'presion_arterial_sistolica': numérico,
          - 'presion_arterial_diastolica': numérico,
           - 'imc': numérico,
           - 'frecuencia_cardiaca': numérico,
           - 'glicemia': numérico,
           - 'riesgo_EAC_decada': booleano.

- Detalle de las Columnas:
           - 'sexo': Considera masculino como 1 y femenino como 0;
           - 'edad': Edad en años completos;
- 'cigarrillos_por_dia': Define diferentes grupos de personas de acuerdo con la cantidad de cigarrillos consumidos por día:
                0 - no fumador;
                1 - fumador leve (1 a 10 cigarrillos por día);
                2 - fumador moderado (11 a 20 cigarrillos por día);
                3 - fumador severo (más de 20 cigarrillos por día).
- 'uso_medicamento_presion': Si la persona toma o no medicamentos para la presión;
          - 'acv': Si ya tuvo Accidente Cerebro-Vascular;
           - 'hipertension': Si la persona sufre de hipertensión;
           - 'diabetes': Si la persona es diabética;
          - 'colesterol_total': Cantidad de colesterol total;
           - 'presion_arterial_sistolica': Presión arterial sistólica medida;
           - 'presion_arterial_diastolica': Presión arterial diastólica medida;
           - 'imc': Índice de masa corporal;
           - 'frecuencia_cardiaca': frecuencia cardíaca en pulsaciones por minuto;
            - 'glicemia': Cantidad de glicemia en la sangre,
- 'riesgo_EAC_decada': Clasificación de riesgo para enfermedad coronaria en los próximos 10 años:
               0 - No está en el grupo de riesgo;
               1 - Está en el grupo de riesgo.
"""

# Verificando la descripción actual del DataFrame
ds.description

# Atribuyendo la nueva descripción
ds.set_description(descricao)

# Visualizando datos del dataset
ds.show_in_notebook()
```

**Video Generando un CSV**

```python
#Creando un csv con los datos finales
ds.to_csv('datos_salud_final.csv', index=False)
```

### Proyecto final

Aquí puedes descargar los archivos del proyecto completo. (Recuerda que estamos trabajando en el Notebook del ecosistema de nube de Oracle)

[Descargue los archivos en Github](https://github.com/ahcamachod/1897-oracle-ads-analisis-de-datos-en-la-nube/blob/proyecto-final/notebook_analisis_salud-proyecto_final.ipynb "Descargue los archivos en Github") o haga clic [aquí](https://github.com/ahcamachod/1897-oracle-ads-analisis-de-datos-en-la-nube/archive/refs/heads/proyecto-final.zip "aquí") para descargarlos directamente.

### Lo que aprendimos
Lo que aprendimos en esta aula:

- Balancear un dataset;
- Documentar el trabajo realizado con los datos;
- Generar un archivo `.csv` con las modificaciones realizadas;
- Generar un banco de datos Oracle con el archivo `.csv` que fue generado.