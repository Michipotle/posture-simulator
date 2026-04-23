# 🎯 Guía de Contribución

¡Gracias por tu interés en contribuir a este proyecto! Aquí te mostraremos cómo hacerlo.

## 📋 Pasos para Contribuir

### 1. Fork del Repositorio
```bash
# Haz un fork del proyecto en GitHub
# Botón "Fork" en la esquina superior derecha
```

### 2. Clonar tu Fork
```bash
git clone https://github.com/TU_USUARIO/posture-simulator.git
cd posture-simulator
```

### 3. Crear una Rama
```bash
git checkout -b feature/tu-mejora
# Ejemplos:
# feature/nuevo-nivel
# fix/corregir-barra-salud
# improvement/mejorar-feedback
```

### 4. Hacer Cambios
Edita los archivos según tu contribución.

### 5. Commit y Push
```bash
git add .
git commit -m "Descripción clara del cambio"
git push origin feature/tu-mejora
```

### 6. Pull Request
1. Ve a tu fork en GitHub
2. Haz clic en "New Pull Request"
3. Compara con la rama `main` del repositorio original
4. Describe tus cambios claramente

## 🐛 Tipos de Contribuciones

### Reportar Bugs
Si encuentras un error:
1. Abre un Issue con el título: `[BUG] Descripción del problema`
2. Describe los pasos para reproducirlo
3. Incluye capturas de pantalla si es posible
4. Especifica tu navegador y versión

**Ejemplo:**
```
[BUG] Las imágenes no cargan en Firefox

Pasos para reproducir:
1. Abre el juego en Firefox
2. Llega al nivel 2
3. Las imágenes no aparecen

Navegador: Firefox 120.0
Sistema: Windows 10
```

### Sugerir Mejoras
Abre un Issue con el título: `[FEATURE] Descripción de la idea`

**Ejemplo:**
```
[FEATURE] Agregar sistema de estadísticas guardadas

Descripción:
Sería útil que el simulador guardara:
- Historico de puntuaciones
- Fecha de juego
- Niveles completados
```

### Mejorar Documentación
- Errores en README.md
- Instrucciones poco claras
- Agregar ejemplos

### Agregar Nuevos Niveles
Si quieres agregar un nivel educativo:

1. **Estructura del nivel:**
```javascript
{
    titulo: "Nivel 8: Tu Escenario",
    contexto: "Descripción del contexto",
    pregunta: "Pregunta clara",
    imagen: "URL-de-imagen",
    opciones: [
        {
            texto: "Opción 1",
            correcta: true/false,
            daño: 0-30,
            feedback: "Explicación detallada"
        },
        // ... más opciones
    ]
}
```

2. **Requisitos:**
   - Mínimo 3 opciones (1 correcta, 2 incorrectas)
   - Feedback detallado con términos médicos
   - Daño entre 0-30 puntos
   - Imagen representativa

3. **Enviar como Pull Request**

## 🎨 Mejoras de Diseño

### Cambios CSS
- Mantén la estructura actual
- Usa colores consistentes
- Asegúrate de que sea responsive
- Prueba en móvil

### Cambios HTML
- Mantén la semántica
- No agregues dependencias externas
- Sigue el mismo estilo de código

### Cambios JavaScript
- Sin librerías externas (vanilla JS)
- Código limpio y comentado
- Mantén la lógica actual

## ✅ Lista de Verificación antes de hacer PR

- [ ] El código funciona correctamente
- [ ] Probé en múltiples navegadores
- [ ] Probé en móvil
- [ ] No hay errores en consola
- [ ] Comenté el código si es necesario
- [ ] Actualicé README.md si es necesario
- [ ] El commit tiene un mensaje claro

## 🧪 Pruebas

### Probar Localmente
```bash
# Opción 1: Abrir index.html directamente
open index.html

# Opción 2: Con Python
python -m http.server 8000
# Luego: http://localhost:8000
```

### Checklist de Pruebas
- [ ] Todos los niveles se cargan correctamente
- [ ] Las imágenes aparecen
- [ ] Los botones funcionan
- [ ] La barra de salud se actualiza
- [ ] El feedback es correcto
- [ ] La puntuación final es exacta
- [ ] El reinicio funciona
- [ ] Responsive en móvil

## 💬 Código de Conducta

- Se respetuoso con los demás colaboradores
- Acepta críticas constructivas
- Ayuda a otros en sus PRs
- Sigue estándares de código

## 📞 Contacto

- **Mantenedor:** Michipotle
- **Email:** mhs8397@gmail.com
- **GitHub:** @Michipotle

## 🙏 ¡Gracias por Contribuir!

Cada contribución, por pequeña que sea, ayuda a mejorar la educación sobre ergonomía y prevención de lesiones.

---

**¿Primera contribución?** No te preocupes, ¡todos empezamos así! 🚀
