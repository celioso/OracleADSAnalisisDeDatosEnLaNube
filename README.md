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