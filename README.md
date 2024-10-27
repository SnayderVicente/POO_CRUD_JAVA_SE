# POO_CRUD_JAVA_SE
![image](https://github.com/user-attachments/assets/0f1d1c68-1f25-484d-9c8d-7d2a15f6d828)
![image](https://github.com/user-attachments/assets/86cd4746-e7e5-42b4-8ed5-9de0952bc1f0)
![image](https://github.com/user-attachments/assets/30e6fc6b-b517-4080-8563-588432462ec1)
En esta clase consultationDAO implementé las operaciones CRUD para la tabla consultation en la base de datos, usando JDBC. Primero, tengo el método obtenerConsulta, que me permite recuperar todas las consultas y devolverlas en una lista. Luego está insertarConsulta, que sirve para agregar una nueva consulta a la tabla. También añadí actualizarConsulta, que modifica una consulta existente usando su id, y finalmente, eliminarConsulta, que borra una consulta según su id. Cada método maneja los posibles errores de SQL y devuelve mensajes que indican si la operación fue exitosa o si hubo algún problema, lo cual ayuda a monitorear el funcionamiento.
----------------------------------------------------------------------
![image](https://github.com/user-attachments/assets/0d5da8d1-2152-4852-94d9-318a5041304c)
En la clase updateConsulta, estoy probando el método actualizarConsulta de consultationDAO. Primero creo una instancia de consultationDAO y luego llamo a actualizarConsulta con el id 3 para actualizar los datos de esa consulta en la tabla consultation de la base de datos. En este caso, le paso valores nuevos para los campos name, lastname, number, email, request, dateConsult y status. Así verifico que el método de actualización funciona y que los cambios se guardan correctamente en la base de datos.
----------------------------------------------------------------------
![image](https://github.com/user-attachments/assets/010e8751-2520-4a2d-9c1f-541680afa4aa)
En esta clase obtenerConsultas, estoy probando el método obtenerConsulta de consultationDAO. Lo que hago es crear una instancia de consultationDAO y llamar al método obtenerConsulta para traer todas las consultas de la tabla consultation. Luego uso un bucle for para imprimir cada consulta en la consola. Esto me ayuda a verificar que el método está trayendo bien los datos y que puedo ver los registros correctamente en la salida.
----------------------------------------------------------------------
![image](https://github.com/user-attachments/assets/dc50718e-658c-4150-866b-db8508c4350a)
En esta clase insertar, estoy probando el método insertarConsulta de la clase consultationDAO. En el método main, cree una instancia de consultationDAO y llame al método insertarConsulta, pasando los datos de una nueva consulta para agregarla a la tabla consultation de la base de datos.
----------------------------------------------------------------------
![image](https://github.com/user-attachments/assets/bb8a8afb-2811-4224-9ef4-713c530435fa)
Profe, en esta clase deleteConsulta estoy probando el método eliminarConsulta de consultationDAO. En el main, creo una instancia de consultationDAO y luego llamo a eliminarConsulta pasando el id 4, que es el de la consulta que quiero eliminar en la tabla consultation. Con esto verifico que el método de eliminación funcione bien y que el registro desaparezca de la base de datos, además de que se muestre el mensaje correspondiente en caso de éxito o de que el id no exista.
----------------------------------------------------------------------
PRUEBAS:
![image](https://github.com/user-attachments/assets/0dd9c412-340d-4f5b-99c5-ee0e7eeaa6f7)

----------------------------------------------------------------------

----------------------------------------------------------------------



