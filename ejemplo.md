# Ejemplos 

## ¿Cómo descargar una pagina web?

Para descargar recomiendo este comando PERO MUCHO CUIDADO puede llenar el disco duro entero
```
wget -H -r -l3 -k -E -p http://miblog.sitiodeblogs.com
```
La opción H (span hosts) expande la recursividad a los sitios desde donde se enlace el original. Este comando descargará el sitio 
con una recursividad de 3 niveles (-r -l3), conviertiendo los enlaces a locales para examinarlo off line (-k), 
convierte todo a extensiones .html (-E), descarga completamente imágenes y demás elementos de cada página (-p)
y además descarga la página externa de los enlaces que apunten fuera del sitio (-H).
