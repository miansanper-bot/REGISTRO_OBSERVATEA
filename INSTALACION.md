# ObservaTEA — Guía de Instalación

## ¿Qué es ObservaTEA?

Sistema de observación pedagógica para alumnas con TEA. Funciona como una app instalada en la tablet, sin necesidad de tiendas de aplicaciones ni conexión a internet.

---

## INSTALACIÓN EN ANDROID (Chrome)

1. Abre **Google Chrome** en la tablet
2. Abre el archivo `index.html` (o si está en un servidor, escribe la dirección)
3. Espera a que cargue completamente
4. Pulsa los **tres puntos** (⋮) arriba a la derecha
5. Selecciona **"Añadir a pantalla de inicio"** o **"Instalar aplicación"**
6. Pulsa **Instalar** en el diálogo
7. La app aparecerá en el escritorio como cualquier otra aplicación

---

## INSTALACIÓN EN IPAD / IPHONE (Safari)

1. Abre **Safari** (no Chrome, debe ser Safari)
2. Abre el archivo `index.html`
3. Pulsa el botón **Compartir** (□↑) en la barra inferior
4. Desplázate y pulsa **"Añadir a inicio"**
5. Pulsa **Añadir** arriba a la derecha
6. La app aparecerá en el escritorio

---

## OPCIÓN MÁS SENCILLA: Servidor local en la red del colegio

Si el colegio tiene un ordenador siempre encendido, se puede servir la app en la red local:

```bash
# En el ordenador del colegio (solo una vez):
cd carpeta-donde-está-observatea
python3 -m http.server 8080

# Desde la tablet, abrir Chrome/Safari y escribir:
# http://[IP-del-ordenador]:8080
```

Esto permite que varias tablets accedan a la misma dirección.

---

## ALMACENAMIENTO DE DATOS

- Los datos se guardan **en el dispositivo** (localStorage del navegador)
- **No se sincronizan** entre dispositivos automáticamente
- Usa la función **"Copia de seguridad"** en Ajustes para exportar los datos a un archivo JSON
- Ese archivo se puede abrir en otro dispositivo con **"Restaurar copia"**

---

## FUNCIONALIDADES

- ✅ Registro de observaciones por áreas (Regulación, Lectoescritura, Matemáticas, Arts, Proyectos)
- ✅ Fecha y hora automáticas (modificables)
- ✅ Todos los campos con desplegables configurables
- ✅ Historial con búsqueda y filtros
- ✅ Estadísticas y gráficas
- ✅ Mantenimiento de opciones de cada desplegable
- ✅ Creación de nuevas áreas
- ✅ Exportación a PDF A4 (imprimible)
- ✅ Exportación a CSV/Excel
- ✅ Copia de seguridad y restauración
- ✅ Funciona sin internet (offline) tras la primera carga
- ✅ Adaptada a pantallas de 7" y 10"
- ✅ Compatible con Android e iOS

---

## VERSIÓN

ObservaTEA v1.0 — Metodología TEACCH  
Diseñada para uso educativo con alumnas con TEA
