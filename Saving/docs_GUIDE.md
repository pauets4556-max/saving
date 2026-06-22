# 📖 Guía de Usuario - SavingSync

## 🔐 Inicio de Sesión

### Primera Vez - Crear Cuenta

1. Abre `savingsync-login.html` en tu navegador
2. Verás la pantalla de login
3. Ingresa:
   - **Usuario**: Tu nombre o usuario (ej: "Paula")
   - **Contraseña**: Tu contraseña segura (mín 4 caracteres)
4. Toca el botón **"+ CREAR CUENTA"**
5. ¡Tu cuenta está creada! Acceso automático a la app

### Inicios Posteriores

1. Ingresa tu **usuario** y **contraseña**
2. Toca **"✓ INICIAR SESIÓN"**
3. ¡Acceso a todos tus datos guardados!

### Cambiar Contraseña

1. Ve a la pestaña **→ CONFIG**
2. En la sección **"👤 Cuenta"** ingresa:
   - Contraseña actual
   - Nueva contraseña
   - Confirmación de nueva contraseña
3. Toca **"✓ CAMBIAR CONTRASEÑA"**

### Cerrar Sesión

En CONFIG, toca el botón **"🚪 CERRAR SESIÓN"**

---

## 📝 Pestaña REGISTRAR

### Registrar un Nuevo Gasto

1. **Selecciona categoría**: Toca uno de los emojis (🛒 Alimentación, 🚗 Transporte, etc.)
2. **Descripción**: Escribe qué compraste (ej: "Compra en Carrefour")
3. **Cantidad**: Ingresa el precio en euros (ej: 45.50)
4. **Fecha**: Selecciona el día (por defecto hoy)
5. Toca **"✓ REGISTRAR"**

### Ver Últimos Gastos

Debajo verás la sección **"📊 Últimos Gastos"** con:
- Los 10 últimos gastos registrados
- Categoría y emoji
- Descripción
- Cantidad

---

## 📅 Pestaña HOY

### Resumen del Día

Muestra:
- **TOTAL HOY**: Suma de todos los gastos de hoy
- **Lista detallada**: Cada gasto del día

### Ejemplo

Si gastaste:
- €15 en café ☕
- €30 en supermercado 🛒
- €20 en gasolina ⛽

Verás: **TOTAL HOY: €65.00**

---

## 📊 Pestaña MES

### Análisis del Mes Actual

**4 estadísticas principales:**
1. **SUELDO**: Tu sueldo mensual (configurable)
2. **GASTOS DEL MES**: Total gastado en el mes actual
3. **AHORRO DISPONIBLE**: Sueldo - Gastos
4. **% AHORRO**: Porcentaje del sueldo que ahorraste

### Recomendaciones Automáticas

- ✅ **Excelente**: Ahorras ≥25%
- 📊 **Aceptable**: Ahorras 15-24%
- ⚠️ **Bajo ahorro**: Ahorras 5-14%
- 🚨 **Crítico**: Ahorras <5% o nada

### Gestión de Ahorro

**💰 Total Ahorro Acumulado**

1. Verás tu **ahorro total acumulado**
2. Campo **"Añadir Ahorro de Este Mes"**:
   - Escribe cuánto ahorras este mes (ej: 500)
   - Toca **"+ AÑADIR"**
   - Se suma automáticamente al total
3. **Historial de ahorros**: Ve los últimos 6 meses que agregaste ahorro

### Ejemplo de Flujo

```
1. Tu sueldo es €2000
2. Gastas €1500 en el mes
3. Ahorro disponible = €500
4. En la sección "Ahorro Mensual", agregas €500
5. Tu ahorro total acumulado aumenta a €500 (o más si ya tenías)
```

---

## ⚙️ Pestaña CONFIG

### 👤 Cuenta

- Ver tu usuario actual
- Cambiar contraseña
- Cerrar sesión

### 💰 Datos Personales

1. **Sueldo Mensual**: Tu ingreso mensual neto
2. **Ahorro Base**: Tu ahorro inicial acumulado
3. Toca **"✓ GUARDAR"** para actualizar

### 🏷️ Categorías

**Categorías por defecto:**
- 🛒 Alimentación
- 🚗 Transporte
- 🎬 Entretenimiento
- ⚡ Servicios
- 🏥 Salud
- 🛍️ Compras
- 🍽️ Restaurante
- 🎮 Ocio
- 🏠 Gastos Fijos
- 📌 Otros

**Crear categoría personalizada:**
1. Escribe el **nombre** (ej: "Películas")
2. Elige un **emoji** (ej: 🎭)
3. Toca **"+ CREAR"**

**Eliminar categoría:**
- En la lista, toca el **"✕"** rojo

---

## 💡 Consejos y Trucos

### Gestión Eficiente

1. **Registra gastos el mismo día**: Evita olvidar gastos
2. **Crea categorías personalizadas**: Ajústalas a tu estilo de vida
3. **Revisa mensualmente**: Ve el análisis del MES para encontrar patrones
4. **Establece metas de ahorro**: Usa el análisis para mejorar

### Seguridad

- ✅ Usa una contraseña fuerte (>8 caracteres)
- ✅ No compartas tu dispositivo si usas la app
- ✅ Tus datos están en tu dispositivo, no en internet
- ❌ Si pierdes el dispositivo, podrías perder los datos

### Privacidad

- Todos tus datos se guardan **localmente**
- **No se envía nada a internet**
- Múltiples usuarios = datos completamente separados
- Cada usuario necesita su propia contraseña

---

## 🔄 Migración de Datos (Cambiar Dispositivo)

### Backup Manual

Por el momento, los datos se guardan localmente. Si cambias de dispositivo:

1. Anota tus datos principales (sueldo, ahorro total)
2. Ingresa manualmente en el nuevo dispositivo
3. Vuelve a crear las categorías personalizadas

### Futuras Mejoras

Se planea añadir:
- ☁️ Sincronización en la nube
- 📤 Exportar datos a CSV/JSON
- 📥 Importar datos de respaldo

---

## ❓ Preguntas Frecuentes

**P: ¿Dónde se guardan mis datos?**
R: En tu dispositivo, en la memoria local del navegador. Completamente privado.

**P: ¿Puedo usar la app sin internet?**
R: Sí, funciona 100% offline. No necesita conexión.

**P: ¿Puedo instalar como app en mi móvil?**
R: Sí, en iOS (Safari) y Android (Chrome): Compartir → Añadir a pantalla de inicio.

**P: ¿Qué pasa si olvido mi contraseña?**
R: No hay recuperación automática. Necesitarías crear una nueva cuenta.

**P: ¿Puedo compartir datos entre dispositivos?**
R: No automáticamente. Se planea sincronización en futuras versiones.

**P: ¿Es segura mi contraseña?**
R: Se guarda localmente en tu dispositivo. No se envía a internet.

---

## 🐛 Reportar Problemas

Si encuentras un error:

1. Describe qué pasó
2. Qué navegador usas
3. Qué sistema operativo
4. Pasos para reproducir el error

Abre un "Issue" en el repositorio de GitHub.

---

**¡Disfruta controlando tu ahorro con SavingSync!** 💰✨
