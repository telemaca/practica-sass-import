# Practica Sass

![Ejemplo](https://cdn.dribbble.com/users/164393/screenshots/2528482/attachments/499046/direct-messaging-lg.jpg)

## Consignas

1. Forkear el repositorio y clonarlo
2. Maquetar el ejemplo de la imagen (usar de referencia no tiene que ser exactamente igual) usando `sass`
3. Utilizar la arquitectura de archivos vista en clase:

```
practica-sass-import
├── styles
│    ├── abstract
│    │   └── _variables.scss     # Archivo parcial donde se guardan las variables
│    ├── components              # Carpeta con archivos parciales por componentes
│    │   ├── _icons.scss         
│    │   ├── _dialog.scss        
│    │   └── ...  
│    ├── layout                  # Carpeta con archivos parciales por layouts
│    │   ├── _searchbar.scss         
│    │   ├── _contacts.scss        
│    │   └── ...
│    ├── page
│    │   └── _variables.scss     # Archivo parcial donde se guardan las variables    
│    └── main.scss               # Archivo principal donde se importan los demás archivos parciales
└── index.html
```

4. **No hacer como card**, hacer a pantalla completa (es decir, sin bordes redondeados y sin fondo, el borde debería coincider con el de la pantalla) 
5. Hacer responsive, para lo cual:
   - Ocultar la barra de contactos
   - Ocultar el panel de llamado
   - Fijar la barra de búsqueda
   - Fijar la barra de escritura 
  
### Recursos  

- [Paleta de colores](https://aco-viewer.appspot.com/443c197f088b593e6546405a271169b0)
- [Fuente](https://fonts.google.com/specimen/Varela+Round)
- [Imágenes de perfil randoms](https://randomuser.me/photos)
