# alianza
Aplicacion de prueba
Los pasos que segui fueron los siguientes:

1. Creacion de una tabla de productos

create table PRODUCTOS
(
  ID                NUMBER(4),
  NOMBRE            VARCHAR2(50),
  DESCRIPCION       VARCHAR2(100),
  LOGO              BLOB,
  FECHA_LIBERACION  DATE,
  FECHA_REVISION    DATE
);

La tabla fue creada en una base de datos Oracle 
2. Creacion de un servicio que consulta esta tabla
3. Creacion de un front en angular que consume ese servicio y lo presenta
4. Creacion de un route que permite navegar entre cada uno de los componentes CRUD
5. Creacion de los componentes CRUD
6. Componente de creacion 

