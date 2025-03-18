# Proyecto Amigo Secreto

Este proyecto es una simple aplicación web de **Amigo Secreto** que permite agregar nombres a una lista, sin duplicados, y luego realizar un sorteo aleatorio para seleccionar el amigo secreto. Es ideal para organizar un juego de amigo secreto en un evento.

## Funcionalidad

1. **Ingresar nombres**  
   - El usuario puede ingresar nombres en un campo de texto.
   - Los nombres no pueden repetirse en la lista.
   - La lista de amigos se actualiza dinámicamente en pantalla.

2. **Sortear un amigo secreto**  
   - Al hacer clic en el botón "Sortear amigo", se selecciona un nombre aleatorio de la lista.
   - El nombre sorteado se muestra en pantalla como el amigo secreto elegido.

## Tecnologías Utilizadas

- **HTML**: Estructura básica de la página.
- **CSS**: Estilos modernos y responsivos para una apariencia atractiva.
- **JavaScript**: Lógica para agregar amigos a la lista y seleccionar aleatoriamente un ganador.

## Estructura del Proyecto

### **HTML (Estructura)**
- **Input**: Un campo donde el usuario puede escribir el nombre de un amigo.
- **Botón "Añadir"**: Llama a la función `agregarAmigo()` para añadir el nombre a la lista.
- **Botón "Sortear amigo"**: Llama a la función `sortearAmigo()` para seleccionar aleatoriamente un nombre.
- **Listas (`<ul>`)**:
  - Una para mostrar los nombres ingresados.
  - Otra para mostrar el resultado del sorteo.

### **JavaScript (Lógica)**
- Se declara un array `listaAmigos` para almacenar los nombres ingresados.
- La función `agregarAmigo()`:
  - Obtiene el nombre del input y lo limpia de espacios innecesarios.
  - Verifica que el nombre no esté vacío ni repetido.
  - Lo agrega al array y actualiza la lista en pantalla.
- La función `sortearAmigo()`:
  - Si la lista no está vacía, selecciona un nombre al azar usando `Math.random()`.
  - Muestra el nombre sorteado en pantalla.

### **CSS (Estilo)**
- Usa colores y estilos modernos para una interfaz atractiva.
- Tiene un diseño limpio con tipografía llamativa.
- Los botones cuentan con efectos al pasar el mouse para mejorar la interacción.

## Instrucciones de Uso

1. Abre el archivo `index.html` en tu navegador.
2. Ingresa nombres en el campo de texto y haz clic en el botón "Añadir" para agregarlos a la lista.
3. Haz clic en "Sortear amigo" para seleccionar aleatoriamente un nombre de la lista y ver quién es el amigo secreto.


## He personalizado la interfaz principal
![{83FCD9DD-5696-4805-85DA-AD2CC03828C9}](https://github.com/user-attachments/assets/0edfe63f-848c-4527-97a8-74ba6371bb67)

## Evita que se agreguen datos repetidos
![{D3A04F19-E96D-4E11-8EA3-DD2D41487D31}](https://github.com/user-attachments/assets/c00bcbe1-186c-4d1a-b63e-0eda36436ac3)

## Hace el sorteo correctamente
![{9D18AFEB-ABA0-4FD8-9189-B6A42EAC843D}](https://github.com/user-attachments/assets/d00809f6-3271-4b3f-8479-b0e7ad54a029)




