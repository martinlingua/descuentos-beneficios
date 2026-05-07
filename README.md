# 💰 Descuentos y Beneficios - En Búsqueda del Pikey

**Gestor de descuentos y beneficios para Giuliani S.A.**

Una aplicación web para registrar, editar y analizar descuentos obtenidos en compras.

## 🚀 Características

✅ **Registro de descuentos** con proveedor, artículo, cantidades y precios  
✅ **Cálculo automático** del beneficio (ahorro) por compra  
✅ **Edición en línea** - Modifica cualquier descuento con el botón ✏️  
✅ **Búsqueda global** - Filtra por cualquier dato en tiempo real  
✅ **Sincronización en la nube** - Acceso desde cualquier dispositivo  
✅ **Estadísticas automáticas** - Total de descuentos, ahorro total y promedio  
✅ **Exportación de datos** - Descarga en JSON y CSV  
✅ **Autenticación con contraseña** - Acceso seguro  

## 🌐 Acceder a la App

**URL:** https://martinlingua.github.io/descuentos-beneficios/descuentos-pikey.html

**Contraseña:** `comprasG2026`

## 📋 Columnas de Datos

| Campo | Tipo | Obligatorio | Descripción |
|-------|------|-----------|-----------|
| Proveedor | Texto | ✓ | Nombre del proveedor |
| Artículo | Texto | ✓ | Descripción del producto |
| Cantidad | Número | ✓ | Cantidad de unidades |
| Precio Original | Decimal | ✓ | Precio sin descuento |
| Precio Final | Decimal | ✓ | Precio con descuento |
| Beneficio | Decimal | Auto | Ahorro = (Original - Final) × Cantidad |
| Observaciones | Texto | - | Notas adicionales |

## 🎯 Cómo Usar

### Agregar Descuento
1. Click en **"➕ Nuevo Descuento"**
2. Completa los campos obligatorios
3. El **Beneficio se calcula automáticamente**
4. Click en **"Guardar Descuento"**

### Editar Descuento
1. En la tabla, busca el descuento
2. Click en **"✏️"** (botón editar)
3. Modifica los campos
4. Click en **"Guardar cambios"**

### Eliminar Descuento
1. Click en **"✕"** (botón eliminar)
2. Confirma la eliminación

### Buscar
1. Escribe en la barra de búsqueda
2. Busca por: proveedor, artículo, precio, observaciones
3. Los resultados se filtran en tiempo real

### Marcar como Completado
1. Click en el **checkbox (✓)** de la fila
2. El registro se marca visualmente como completado

### Exportar Datos
- **"💾 Descargar JSON"** → Descarga respaldo en JSON
- **"📊 Exportar CSV"** → Abre en Excel/Sheets

## 🔧 Tecnología

- **Frontend:** HTML5 + CSS3 + JavaScript (Vanilla)
- **Base de Datos:** Supabase (PostgreSQL)
- **Alojamiento:** GitHub Pages
- **Autenticación:** Contraseña simple (sessionStorage)

## 💾 Base de Datos

Los datos se guardan en **Supabase** (gratis):
- Proyecto: `descuentos-beneficios`
- Tabla: `descuentos`
- Sincronización en tiempo real automática

## 📱 Dispositivos

✅ **Funciona en:**
- Computadora (Windows, Mac, Linux)
- Tablet
- Celular (versión responsive)

## 🔐 Seguridad

- ✓ Sesión con contraseña
- ✓ Datos en Supabase (encriptados en tránsito)
- ✓ Sin datos sensibles almacenados localmente

## 📊 Estadísticas

La app muestra automáticamente:
- **Total de Descuentos** - Cantidad de registros
- **Ahorro Total** - Suma de todos los beneficios
- **Promedio por Descuento** - Beneficio promedio

## 🆘 Solucionar Problemas

**P: No puedo ingresar**  
R: Verifica que escribes la contraseña exacta: `comprasG2026`

**P: Los datos no se sincronizan**  
R: Verifica conexión a internet y recarga la página

**P: ¿Dónde se guardan mis datos?**  
R: En Supabase (base de datos en la nube) y sincronizados entre dispositivos

**P: ¿Puedo cambiar la contraseña?**  
R: Sí, edita el archivo HTML y cambia `const PASSWORD = "comprasG2026";`

## 📝 Notas de Versión

### v1.0 (Actual)
- ✅ Login con contraseña
- ✅ CRUD completo (crear, leer, actualizar, eliminar)
- ✅ Búsqueda en tiempo real
- ✅ Cálculo automático de beneficios
- ✅ Estadísticas
- ✅ Exportación de datos
- ✅ Sincronización Supabase

## 📞 Contacto

Desarrollado para **Giuliani S.A.**  
"En búsqueda del Pikey" 💰

---

**Última actualización:** 2026-05-07

