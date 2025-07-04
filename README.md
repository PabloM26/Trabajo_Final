# ParkFlow
## Parqueadero Luxury Parking
<img src="https://github.com/user-attachments/assets/a0630a60-2c60-4575-96a7-292056b21bda" alt="Imagen subida" width="300px">

El presente proyecto consiste en la creación de un sistema de gestión para el parqueadero Luxury Parking, ubicado en la Universidad de Antioquia, el cual presta sus servicios únicamente a automóviles. Mediante el uso del programa Python, se busca desarrollar un proceso de registro de vehículos, asignación de celdas de parqueo, control de ingresos y salidas, cálculo de tarifas por tiempo de permanencia, y generación de reportes administrativos exportados en archivos CSV. El sistema es amigable para el usuario y permite la gestión eficiente de hasta 50 espacios disponibles, garantizando la continuidad del servicio en una jornada continua de 6:00 a.m. a 12:00 p.m. 

### Equipo desarrollador
Juan Pablo Marín Duque

David Fernando Báez Coronado

Santiago Osorio Perez

Ingeniería Industrial

### Habilidades y fortalezas
David es una persona responsable y perseverante, estas cualidades le permiten adaptarse con facilidad a los cambios y a nuevos entornos. Además, posee habilidades en el manejo de herramientas digitales y en la resolución de problemas, especialmente cuando trabaja en equipo, lo que le facilita alcanzar objetivos de manera eficiente y colaborativa.

Pablo es apasionado en sus labores, junto con su responsabilidad y las ganas de aprendizaje, le permiten el cumplimiento de objetivos. Facilitándose esta tarea al trabajar en colaboración con otros.

Santiago, es una persona responsable y disciplinada, estás habilidades ayudan a potenciar las habilidades de sus compañeros y las de el en pro del equipo, además tiene la ventaja de tener un pensamiento crítico y detallado lo cual le ayuda a identificar problemas y soluciones.

### Responsabilidades
Primero nos encontramos con unas responsabilidades grupales: El planteamiento del proyecto, que consiste en la participación en la definición de objetivos, la planificación y elaboración de la documentación acerca del proyecto. También nos reuniremos a revisar el proyecto, cada uno dirá lo que hizo y los demás van a colaborar con su retroalimentación. 
En cuanto a las responsabilidades individuales, Juan Pablo se encargará del módulo de registro de usuarios y el módulo de la administración y cierre de día más que todo en la lógica. Santiago, hará el módulo de registro de ingreso del vehículo y la parte de datos de administración y cierre de día. Finalmente, David se encargará de generar el código para el retiro de un vehículo y el módulo que va a calcular el cobro de la tarifa por la estancia en el parqueadero. 

## Informe de primera entrega del proyecto de Algoritmos y Programación

### Reporte de visión
El presente proyecto tiene como objetivo encontrar una solución de software que permita la aplicación de conceptos básicos de algoritmos y programación mediante la plataforma Google Colab. Esta herramienta nos facilita el trabajo en equipo ya que al ser una plataforma interactiva, podemos trabajar simultáneamente. Con este proyecto buscamos gestionar el registro de usuarios, la entrada y salida de sus vehículos, lo que implica desarrollar un sistema que almacene datos como la información personal de los usuarios, la placa de los vehículos, la hora de ingreso y salida, y el cálculo de tiempo de permanencia que dará el valor a cobrar a dicho usuario.

### Especificación de requisitos
➢ Requisitos funcionales son los que definen las acciones que vamos a utilizar de manera específica, los comportamientos y operaciones que deseamos que tenga nuestro programa ○ Registro de usuario: Vamos a solicitar a cada persona que nos de los siguientes datos: nombre y apellido, número de documento y la placa. Lo anterior debe incluir las restricciones previamente establecidas para estos parámetros. 
 
 ○ Registro de vehículo: Para el ingreso del vehículo tenemos que verificar que los datos estén de acuerdo a lo que registramos antes. Posteriormente, haremos que nuestro programa 
 verifique si hay espacios de parqueo libres y mostrar dónde se encuentra este espacio. Luego de haber validado lo anterior, mostraremos una factura que notifique el ingreso 
 satisfactorio al sistema.

 ○ Retiro de vehículos y gestión de tarifas: Para que una persona pueda retirar su vehículo, el software se encargará de calcular el valor de la estancia respecto al tiempo de uso, esto 
 es: Se multiplica el número de horas enteras parqueadas por el valor de la hora que corresponde a 7000 pesos. El número de cuartos de hora se multiplicará por 1500. El total a pagar es 
 la suma del cobro por hora y el cobro por cuartos de hora. Si el total calculado es menor que el valor de una hora completa, entonces el pago mínimo será el valor de una hora completa 
 (7000).
 
 ○ Administración: Se deben crear ciertos usuarios especiales que tendrán acceso a los siguientes datos de nuestro programa: Total de vehículos registrados, total de vehículos retirados, 
 total de vehículos sin retirar, el pago total de los vehículos retirados, el tiempo promedio de estancia de un vehículo en el parqueadero, la lista de usuarios, vehículo con mayor y 
 menor tiempo de parqueo y la ocupación de celdas de parqueo.
 
 ○ Salida del programa: Al finalizar la gestión de nuestro parqueadero, añadiremos la opción de dar el día por terminado lo que entregará dos opciones: Cerrar el sistema o generar un 
 archivo CSV con los resultados, esto depende de lo que el usuario desee.

➢ Requisitos no funcionales hacen referencia a la operación del sistema, o sea, el rendimiento, la facilidad de uso, seguridad y fiabilidad, y la compatibilidad.

  ○ Rendimiento: El software a desarrollar va a tener la capacidad de manejar las transacciones por hora para la entrada y salida de los vehículos, el registro de los mismos, la 
  capacidad 
 de almacenaje de todo esto, sin generar retrasos significativos en su funcionamiento.

 ○ Usabilidad: Vamos a crear una interfaz simple y amigable con el usuario, ya que al facilitarle el acceso solicitando únicamente sus datos evita retrasos en el ingreso de las otras 
 personas y no es necesario capacitarse con anticipación para la ejecución del programa.

 ○ Seguridad y fiabilidad: Nuestro software será totalmente privado de acuerdo a las políticas de protección de datos vigentes, y es de acceso restringido a la información personal de 
 las personas que hagan uso de nuestro sistema.

 ○ Compatibilidad: Para que nuestro programa se adapte a distintos conjuntos de poblaciones dependiendo del espacio del sistema de parqueo a implementar, vamos a facilitar la 
 adaptabilidad de nuestro software a casos como ese.

### Librerías
Definir este apartado al inicio es un poco complejo ya que a medida que vayamos avanzando en el trabajo nos surgirán necesidades, y por ende, tendremos que recurrir a otras librerías. Dicho lo anterior, para comenzar tenemos pensado utilizar las siguientes:

➢ Gestión del tiempo y fechas: necesitamos una librería que nos permita la hora de entrada y salida, calcular el tiempo de permanencia, etc.

➢ Cálculos y operaciones: Esta librería se utilizará solo si llegamos a requerir una ayuda en alguna operación matemática compleja.

➢ Estructuras de datos: Vamos a necesitar una librería que nos permita manejar fácil las listas de datos y que también nos permita guardarlos.

➢ Exportación de datos: Es de fundamental importancia esta librería ya que nos permitirá exportar nuestro reporte de datos en un archivo CSV.

### Visual
A corde a lo visual, tenemos que proyectar una interfaz fácil e intuitiva y aunque esta imagen se vea como una aplicación de escritorio, es importante aclarar que esta primera etapa del proyecto la vamos a elaborar en google colab, donde las interacciones se hacen básicamente en entradas y salidas. Por tanto este diseño que presentamos se podría implementar a futuro cuando el proyecto evolucione a una aplicación más completa o a una página web.


### Algoritmos
#### 1.Registrar usuario
```
INICIO Registrar Usuario
  MOSTRAR mensaje: "BIENVENIDO AL SISTEMA DE PARQUEO"
    LEER Nombre
    LEER Apellido
    LEER Documento
    LEER Placa
    CREAR Usuario CON [Nombre, Apellido, Documento, Placa]
    AÑADIR Usuario a la lista Usuarios
    MOSTRAR mensaje: "Usuarios registrados: ", Usuarios
FIN Registrar Usuario
```

#### 2.Ingresar vehículo
```
INICIO Ingresar Vehículo
  LEER placa_ingresar
  usuario_encontrado = NULO
  PARA CADA usuario EN Usuarios HACER
    SI usuario[3] ES IGUAL A placa_ingresar ENTONCES
      usuario_encontrado = usuario
      SALIR_DEL_CICLO
    FIN_SI
  FIN_PARA
  SI usuario_encontrado NO ES NULO ENTONCES
    SI el tamaño de Vehiculos_en_parqueo ES MENOR QUE 10 ENTONCES
      CREAR Vehiculo CON [usuario_encontrado[0], usuario_encontrado[3]]
      AÑADIR Vehiculo a la lista Vehiculos_en_parqueo
      MOSTRAR mensaje: "El vehículo se ha ingresado correctamente."
    SINO
      MOSTRAR mensaje: "No hay espacios de parqueo disponibles."
    FIN_SI
  SINO
    MOSTRAR mensaje: "La placa no se ha registrado aún."
  FIN_SI
FIN Ingresar Vehículo
```
#### 3.Registrar vehículo
```
INICIO Retirar Vehículo
  LEER placa_retirar
  vehiculo_encontrado = NULO
  PARA CADA vehiculo EN Vehiculos_en_parqueo HACER
    SI vehiculo[1] ES IGUAL A placa_retirar ENTONCES
      vehiculo_encontrado = vehiculo
      SALIR_DEL_CICLO
    FIN_SI
  FIN_PARA
  SI vehiculo_encontrado NO ES NULO ENTONCES
    MOSTRAR mensaje: "Ingrese la hora de ingreso y la hora de salida en formato de 24 horas (solo horas y minutos separados)."
    LEER hora_ingreso (entero)
    LEER minutos_ingreso (entero)
    LEER hora_salida (entero)
    LEER minutos_salida (entero)
    tiempo_ingreso = hora_ingreso * 60 + minutos_ingreso
    tiempo_salida = hora_salida * 60 + minutos_salida
    tiempo_total = tiempo_salida - tiempo_ingreso
    SI tiempo_total ES MENOR O IGUAL A 0 ENTONCES
      MOSTRAR mensaje: "Error: la hora de salida debe ser mayor que la de ingreso."
    SINO
      horas = tiempo_total DIV 60
      minutos_restantes = tiempo_total MOD 60
      cuartos_hora = minutos_restantes DIV 15
      cobro_horas = horas * 7000
      cobro_cuartos = cuartos_hora * 1500
      total_pagar = cobro_horas + cobro_cuartos
      SI total_pagar ES MENOR QUE 7000 ENTONCES
        total_pagar = 7000
      FIN_SI
      MOSTRAR mensaje: "Tiempo total:", horas, " horas y", minutos_restantes, "minutos."
      MOSTRAR mensaje: "Cobro por horas: $", cobro_horas
      MOSTRAR mensaje: "Cobro por cuartos de hora: $", cobro_cuartos
      MOSTRAR mensaje: "Total a pagar: $", total_pagar
      ELIMINAR vehiculo_encontrado DE Vehiculos_en_parqueo
      MOSTRAR mensaje: "Vehículo retirado correctamente."
    FIN_SI
  SINO
    MOSTRAR mensaje: "Vehículo no encontrado en el parqueadero."
  FIN_SI
FIN Retirar Vehículo
```
#### 4.Ingresar al administrador
```
INICIO Ingresar al Administrador
  contraseña_admin = "admin123"
  LEER entrada_contraseña
  SI entrada_contraseña ES IGUAL A contraseña_admin ENTONCES
    MOSTRAR mensaje: "Bienvenido Administrador."
    MOSTRAR mensaje: "Total de usuarios registrados:", el tamaño de
    Usuarios
    MOSTRAR mensaje: "Total de vehículos en el parqueadero:", el tamaño de
    Vehiculos_en_parqueo
  SINO
    MOSTRAR mensaje: "Acceso denegado."
  FIN_SI
FIN Ingresar al Administrador
```
Es importante aclarar que en este pseudocódigo hay muchas cosas que faltan tal como el menú inicial en el que desplegamos al usuario una lista similar al que mostramos en el apartado de visual. Además usaremos librerías que nos permitan por ejemplo, gestionar mejor el tiempo ya que acá le pedimos al usuario ingresar la hora de entrada y salida exactas, lo que se puede prestar para malentendidos y pérdidas, entonces en ese apartado solo queríamos que se apreciará más que todo el sistema de cobro con las restricciones impuestas. También agregaremos las
restricciones que hay para el registro de usuario, como la longitud de los nombres y el número de documento, entre otras.

### Estructuras de datos
Para el almacenamiento de la información principal se dará uso de diccionarios, listas y tuplas como estructuras de datos. Los diccionarios permitirán almacenar organizadamente la información de los usuarios y de los vehículos. Las tuplas tendrán los datos fijos que no van a tener que cambiarse como las tarifas. Finalmente, las listas llevarán registro de las celdas de parqueadero que se encuentren disponibles u ocupadas y de los vehículos que han entrado.

### Presentación de resultados
Para este módulo, primero mostramos un usuario predefinido en el sistema, pero esto no es muy efectivo, entonces mediante el desarrollo de nuestro software vamos a mejorar este aspecto: Permitiremos registrar administradores nuevos, esto sin perder la idea original de usar un usuario de administración global con una contraseña predefinida para que no cualquiera se pueda convertir en administrador. Posteriormente desplegamos el menú que mostrará a detalle en un reporte ordenado todos los datos importantes de la organización del parqueadero. Para la visualización incluimos la opción de ver en pantalla o de generar el archivo CSV dependiendo de las necesidades del usuario.
