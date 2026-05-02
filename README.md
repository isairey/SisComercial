# Manual del Usuario

**PRIME – Sistema Comercial**

**V.1.0.0**

## ***Visión General***
=================

**Sistema PRIME:**
----------------

El "Prime – Sistema Comercial" está compuesto por dos aplicaciones: el **"Menú General"** (software del gerente), que es responsable de gestionar todos los productos, registros, configuraciones y reportes del sistema. Es el software que realiza el intercambio o actualización de información entre la base de datos y el terminal de punto de venta, que a su vez se refiere a un sistema completo de punto de venta, responsable de realizar todas las ventas en el ECF.

**Base de Datos:**
----------------

El "Prime – Sistema Comercial" fue desarrollado con una base de datos **MySQL**. El usuario debe instalar la base de datos antes del programa para su perfecto funcionamiento. La versión utilizada es la versión [**MySQL for Windows**](http://www.baixaki.com.br/download/mysql-for-windows.htm) **5.1.56.**

**Acceso al PRIME:**
------------------

El "Prime – Sistema Comercial" cuenta con un dispositivo de seguridad para que solo las personas debidamente autorizadas tengan acceso al Menú General y puedan realizar cualquier tipo de cambio en la base de datos del sistema. El responsable superior debe liberar el acceso necesario a un empleado proporcionándole un usuario y contraseña del sistema con el permiso que mejor le corresponda.

Por defecto, el sistema trae los siguientes datos de acceso:

**Login:** Supervisor  
**Contraseña:** supervisor

## ***Instalación***
================

**Base de Datos:**
----------------

La base de datos utilizada es el servidor de base de datos SQL multi-recursos **MySQL for Windows 5.1.56**. Para acceder a la base de datos, debe instalarse el programa de interfaz del banco de datos. El utilizado en la creación fue **SQL Front 5.1 build 1.12**. Después de instalar la interfaz de la BD, debe crearse el siguiente usuario:

**Nombre:** prime  
**Servidor:** localhost  
**Puerto:** 3306  
**Tipo de Conexión:** Directo  
**Usuario:** root  
**Contraseña:** root  

![image003](https://github.com/marcosscholl/Prime-SistemaComercial/blob/master/media/image003.jpg?raw=true)  
![image005](https://github.com/marcosscholl/Prime-SistemaComercial/blob/master/media/image005.jpg?raw=true)

## ***Visión del Sistema***
======================

**Menú General:**
-------------

El "PRIME – Sistema Comercial" cuenta con un menú general (**menú del gerente**) que controla todo el inventario, registro de empleados, proveedores, clientes, productos, unidades, tarjetas, etc.

A continuación conoceremos mejor cada uno de estos menús.

### *- Pantalla de Login:*

Es la pantalla de acceso al sistema, donde se debe informar el login y contraseña del usuario para que tenga el debido acceso al sistema. Recordando que solo el gerente, o quien tenga el recurso correspondiente, tendrá acceso total al sistema, quedando a los demás algunas áreas con acceso restringido.

![image007](https://github.com/marcosscholl/Prime-SistemaComercial/blob/master/media/image007.jpg?raw=true)

Si los datos informados para el login son correctos, el usuario recibirá el mensaje mostrado en la imagen de abajo. De lo contrario, tendrá hasta **3 intentos** para corregir sus datos. Pasados los intentos, el programa se cerrará automáticamente y deberá reabrirlo para iniciar un nuevo intento.

![image009](https://github.com/marcosscholl/Prime-SistemaComercial/blob/master/media/image009.jpg?raw=true)

Una vez realizado el login exitosamente, se presentará la pantalla del **Menú General**.

![image011](https://github.com/marcosscholl/Prime-SistemaComercial/blob/master/media/image011.jpg?raw=true)

### *- Ítems del Menú:*

El Menú General se divide en los siguientes menús y submenús:

- **REGISTRO:**
  - Clientes
  - Proveedores
  - Cuentas Bancarias
  - Unidades
  - Productos
  - Departamentos
  - Empleados
  - Tarjetas
  - Plan de Cuentas
  - Tipo de pago y cobro
  - Salir

- **MOVIMIENTO:**
  - Cuentas por Pagar
  - Cuentas por Cobrar
  - Ventas
  - Presupuestos
  - Control de Inventario
    - Entrada de NF
    - Actualización de Precios
  - Compras
    - Solicitud
    - Cotización
    - Confirmar Cotización
    - Pedido
  - Tesorería y Banco
    - Emisión de Cheques
    - Conciliación de Cheques
    - Movimiento de Banco

- **UTILITARIOS:**
  - Calculadora
  - Calendario
  - Sistema de Seguridad
    - Cambiar Contraseña de Acceso
    - Definir Nivel de Acceso

- **AYUDA:**
  - Contenido
  - Acerca del Sistema

**Imágenes de Acceso Directo y sus Significados:**

![](https://github.com/isairey/SisComercial/main/media/image013.jpg?raw=true)**= Cadastrar um Novo Cliente;**

![](https://github.com/isairey/SisComercial/main/media/image015.jpg?raw=true) **= Cadastrar um novo Produto;**

![](https://github.com/isairey/SisComercial/main/media/image017.jpg?raw=true) **= Realizar Orçamento;**

![](https://github.com/isairey/SisComercial/main/media/image019.jpg?raw=true) **= Iniciar Frente de Caixa;**

![](https://github.com/isairey/SisComercial/main/media/image021.jpg?raw=true) **= Consultar / Cadastrar um
Fornecedor;**

![](https://github.com/isairey/SisComercial/main/media/image023.jpg?raw=true) **= Abrir Calculadora;**

![](https://github.com/isairey/SisComercial/main/media/image025.jpg?raw=true)**= Sair.**
