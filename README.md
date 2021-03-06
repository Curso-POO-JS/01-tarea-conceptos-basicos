<img src="img/portada.jpg">

# Tarea Conceptos Básicos: Diario de gastos

En este ejemplo se ponen en práctica los siguientes conceptos básicos de la programación orientada a objetos:

- Clase
- Objeto
- Atributo
- Método
- Método Constructor
- Encapsulación

## Instrucciones

Se requiere desarrollar una aplicación para la  administración de gastos diarios con base a un presupuesto. La aplicación deberá implementar las clases que se muestra en el siguiente diagrama.

<img src="img/diagrama-uml.png">

## Descripción de clases, métodos y atributos

A continuación se describen algunas de las clases, métodos y atributos del diagrama

### La Clase Gasto

#### Atributos
- **_(Date) fecha_** Fecha en la que se realizó el gasto
- **_(String) descripción_** Descripción o motivo del gasto
- **_(Number) monto_** Monto que corresponde al gasto realizado

#### Métodos
- **_(String) getFechaConFormato()_** Regresa un String con la fecha en la que se realizó el gasto con el siguiente formato 11/Mayo/2020

### La Clase Diario

#### Atributos
- **_(String) nombre_** Nombre que identifica al presupuesto
- **_(Number) presupuesto_** Monto total del presupuesto
- **_(Gasto[]) gasto_** Gastos realizados

#### Métodos
- **_(String) getGastadoConFormato()_** Regresa la suma total de todos los gastos realizados como un String con el siguiente formato $1,234.56
- **_(String) getDisponibleConFormato()_** Regresa el total de presupuesto disponible como un String con el siguiente formato $1,234.56
- **_(String) getPresupuestoConFormato()_** Regresa el presupuesto total como un String con el siguiente formato $1,234.56
- **_(void) listarGastos()_** Imprime en consola un listado de gastos con el siguiente formato (no es necesario que sea una tabla, puede ser un listado simple)

Nun | Fecha | Descripción | Monto
--- | --- | --- | --- 
1 | 11/Mayo/2020 | Taxi | $50.00
2 | 11/Mayo/2020 | Comida| $150.00
3 | 12/Mayo/2020 | Hospedaje | $500.00
_  | _ | Total gastado | $700.00
_  | _  | Total disponible | $1,300.00
  


