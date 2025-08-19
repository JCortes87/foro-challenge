<h1>Foro Challenge</h1>
<lr></lr>
<img width="238" height="92" alt="alura_challenge" src="https://github.com/user-attachments/assets/403bd8e5-bd52-4031-af0d-712f5a8c63c3" />

<h3>Bienvenido a la aplicación de Foro</h3>

## 📖 ¿Cómo funciona?
- `Paso 1. Debes utilizar Postman o Insomnia para probar los Request de la API`: Será necesario que descargues alguna de estas dos aplicaciones para realizar las pruebas

- `Paso 2. Agregar en la base de datos un usuario a la tabla usuarios `: La contraseña debe estar encriptada con BCrypt para que la validación se lleve a cabo

- <img width="666" height="47" alt="image" src="https://github.com/user-attachments/assets/5f058414-9359-4070-a934-4c6afb5af28e" />

- `Paso 3. Tipos de Requests `:
- `Descripción`: Los tipos de Requests que puedes realizar son:<br>
                 ✔️POST con url "/topicos para crear un topico nuevo, debes agregar al body tipo Json los datos completos excepto el id ya que se genera automaticamente en la base de datos'<br>
                 <img width="336" height="207" alt="image" src="https://github.com/user-attachments/assets/e1160384-b546-41be-b45a-3030c175d391" /><br>
                 ✔️GET con url "/topicos para listar todos los topicos'<br>
                 ✔️GET con url + Id "/topicos/{id} para listar algún topico en especifico'<br>
                 ✔️PUT con url "/topicos para editar cualquier topico, recuerda que en el body tipo json debes enviar el id y el campo que deseas actualizar'<br>
                 <img width="232" height="150" alt="image" src="https://github.com/user-attachments/assets/b6abcf88-de27-447e-a5a4-d037a2cd69e0" /><br>
                 ✔️DELETE con url + Id "/topicos/{id}' para eliminar cualquier topico con de la base de datos

- `Paso 3. Iniciar Sesión`: 
- `Descripción`: Debes iniciar sesión creando una Request de tipo Post a la Url http://localhost:8080/login en la que debes agregar un body tipo Json con el usuario y la contraseña. Recibirás un Token el cual debes copiar'

  <img width="1202" height="476" alt="image" src="https://github.com/user-attachments/assets/8f9a3592-48e6-4a4f-b393-5b1a03b4049d" />

- `Paso 4. Realizar Requests`:
- - `Descripción`: Debes copiar el token que se genera en el paso anterior y luego en Auth pegar para que se lleve a cabo la validación'

  <img width="611" height="247" alt="image" src="https://github.com/user-attachments/assets/352e12a8-20ba-4dee-8887-d21c7b2bec67" />

 De esta manera podrás realizar cualquier Request

  <h4>Nota</h4> Recuerda que el token tiene una validez de 2 horas, por lo que si vence, es necesario que inicies sesión de nuevo 
  <h4>Nota</h4> Recuerda insertar topicos para poderlos visualizar en las Request de listar y listar por id 

## 💻 Tecnologías utilizadas
✔️ Java <br>
✔️ Springboot <br>
✔️ Mysql <br>

