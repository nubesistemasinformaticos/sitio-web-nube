# Sito Web Nube sistemas

## Configuracion local (Ambiente Desarrollo)

1) Descargar proyecto : git clone

2) Bajar librerias: posicionarse mediante cmd en la raiz y ejecutar: 

```bash
npm install
```

3) Run del sitio local:

```bash
ng serve
```

y te lo levanta en el localhost:4200

## Build y Deploy para ambiente Producción

Posicionarse mediante cmd en la raiz y ejecutar (en el dominio que se quiera deployar): 

```bash
ng build --prod
```

ng build --configuration=production

Lo anterior nos creará el codigo html y javascript de la página en la carpeta sitiowebfrontend\dist\ (eso mismo lo ponemos en la carpeta del servidor)
