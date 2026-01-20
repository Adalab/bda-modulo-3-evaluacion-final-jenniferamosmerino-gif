# Ejercicio de evaluación final
----------------------------------
## Los datos
Los datos, emplazados en la carpeta Readme consisten en dos datasets que, en conjunto, describen el comportamiento de los clientes dentro de un programa de lealtad de una aerolínea.

1. __Customer Flight Analysis.csv__
>Contiene información sobre la actividad de vuelo de los clientes. 

Se compone de:
- _Loyalty Number:_ Este atributo representa un identificador único para cada cliente dentro del programa de lealtad de la aerolínea. Cada número de lealtad corresponde a un cliente específico.
- _Year:_ Indica el año en el cual se registraron las actividades de vuelo para el cliente.
- _Month:_ Representa el mes del año (de 1 a 12) en el cual ocurrieron las actividades de vuelo.
- _Flights Booked:_ Número total de vuelos reservados por el cliente en ese mes específico.
- _Flights with Companions:_ Número de vuelos reservados en los cuales el cliente viajó con acompañantes.
- _Total Flights:_ El número total de vuelos que el cliente ha realizado, que puede incluir vuelos reservados en meses anteriores.
- _Distance:_ La distancia total (presumiblemente en millas o kilómetros) que el cliente ha volado durante el mes.
- _Points Accumulated:_ Puntos acumulados por el cliente en el programa de lealtad durante el mes, con base en la distancia volada u otros factores.
- _Points Redeemed:_ Puntos que el cliente ha redimido en el mes, posiblemente para obtener beneficios como vuelos gratis, mejoras, etc.
- _Dollar Cost Points Redeemed:_ El valor en dólares de los puntos que el cliente ha redimido durante el mes.

2. __Customer Loyalty History.csv__
>Proporciona un perfil detallado de los clientes. 

Se compone de:

- _Loyalty Number:_ Identificador único del cliente dentro del programa de lealtad. Este número permite correlacionar la información de este archivo con el archivo de actividad de vuelos
- _Country:_ País de residencia del cliente.
- _Province:_ Provincia o estado de residencia del cliente (aplicable a países con divisiones provinciales o estatales, como Canadá).
- _City:_ Ciudad de residencia del cliente.
- _Postal Code:_ Código postal del cliente.
- _Gender:_ Género del cliente (ej. Male para masculino y Female para femenino).
- _Education:_ Nivel educativo alcanzado por el cliente (ej. Bachelor para licenciatura, College para estudios universitarios o técnicos, etc.).
- _Salary:_ Ingreso anual estimado del cliente.
- _Marital Status:_ Estado civil del cliente (ej. Single para soltero, Married para casado, Divorced para divorciado, etc.).
- _Loyalty Card:_ Tipo de tarjeta de lealtad que posee el cliente. Esto podría indicar distintos niveles o categorías dentro del programa de lealtad.
- _CLV (Customer Lifetime Value):_ Valor total estimado que el cliente aporta a la empresa durante toda la relación que mantiene con ella.
- _Enrollment Type:_ Tipo de inscripción del cliente en el programa de lealtad (ej. Standard).
- _Enrollment Year:_ Año en que el cliente se inscribió en el programa de lealtad.
- _Enrollment Month:_ Mes en que el cliente se inscribió en el programa de lealtad.
- _Cancellation Year:_ Año en que el cliente canceló su membresía en el programa de lealtad, si aplica.
- _Cancellation Month:_ Mes en que el cliente canceló su membresía en el programa de lealtad, si aplica.

## Ejercicio
