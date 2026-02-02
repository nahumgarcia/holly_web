# Proyecto: Web para Profesora de Inglés

## 👤 Información básica
- **Nombre:** Holly Richmond
- **Especialidad:** Conversación en inglés
- **Público objetivo:** 
  - Profesionales/empresas (versión formal)
  - Jóvenes/estudiantes (versión divertida)

---

## 🎯 Objetivo del proyecto
Crear un sitio web profesional con dos "skins" diferentes (formal y divertida) 
para poder enviar URLs distintas según el perfil del potencial alumno. El contenido será tal cual el que tenemos en un Notion que hemos exportado en la carpeta del proyecto. Al final de cada web habrá un formulario donde los interesados podrán escribir a Holly para obtener más información o solicitar clases. 

**Tecnología:**
- Jekyll + GitHub Pages
- Dominio personalizado: por definir, lo compraremos cuando esté hecha la web con los dos skins
- Responsive (móvil friendly)

---

## 🎨 Dos versiones del sitio

### Versión FORMAL (Profesional)
**URL:** `dominiopordefinir.com` 

**Público:** Empresas, profesionales del sector tech, marketing... 

**Estilo visual:**
- Nos gustaría algo parecido a esta web: https://clinicaduran.es Pero en vez de usar ese color marrón y verde de fondo, un solo color de fondo, quizás un azul marino

**Elementos clave a destacar:**
- Coger tal cual los contenidos del Notion y llevarlos a la web
---

### Versión FUN (Divertida)
**URL:** `fun.dominiopordefinir.com` (o subdominio por definir)

**Público:** Gente moderna, que esté al día de las modas actuales y pasadas, que entienda la ironía y el sarcasmo de usar un estilo geocities hoy en día

**Estilo visual:**
- Algo como esta web https://geocities.restorativland.org/Area51/Capsule/1695/ con textos que se mueven, gifs animados, idealmente muchos de gatitos y cosas monas. fondo negro está bien.

**Elementos clave a destacar:**
- Mismo contenido que la otra web, ya lo cambiaremos nosotros si queremos después 

---

## 📄 Contenidos (exportados de Notion)

**Ver carpeta:** `/contenido-notion/`

El contenido incluye:
- [X] Descripción de servicios
- [X] Sobre mí / biografía
- [X] Metodología de enseñanza
- [X] Testimonios de alumnos
- [X] Precios y paquetes
- [ ] Horarios / disponibilidad
- [X] Información de contacto

**Nota:** El contenido base es el mismo para ambas versiones, 
pero el tono/presentación debe adaptarse a cada skin.

---

## 🎯 Páginas del sitio

### Estructura propuesta:
1. **Home** - Presentación impactante con CTA claro
2. **Sobre mí** - Biografía, experiencia, enfoque
3. **Servicios** - Qué ofrezco, cómo trabajo
4. **Testimonios** - Casos de éxito (filtrados por perfil si es posible)
5. **Precios** - Paquetes claros y transparentes
6. **Contacto** - Formulario + info de contacto

### Página de entrada (opcional):
- **URL raíz:** `tudominio.com`
- Con dos botones grandes:
  - "Clases para empresas/profesionales" → versión formal
  - "Aprende conversando de forma divertida" → versión fun

---

## 🔧 Funcionalidades técnicas

### Esenciales:
- [x] Responsive design (móvil primero)
- [x] Dos skins completamente diferentes
- [x] Formulario de contacto funcional
- [x] Enlaces a redes sociales (solo Linkedin)
- [x] Optimización SEO básica

### Formulario de contacto:
**Integración preferida:** [Marca una]
- [X] Google Forms: https://docs.google.com/forms/d/e/1FAIpQLScBNAAxEX5PgtMPvNdirFNmH7P3UJQtoKWr2np6XM6tscVaaA/viewform
- [ ] Formspree (gratis hasta 50/mes)
- [ ] Netlify Forms
- [ ] Otra: _____________

**Campos del formulario:**
- Name
- Email
- What type of classes are you interested in?
	- Individual
	- Group
	- I'm not sure
- What's your current level?
	- Beginner (A1-A2)
	- Intermediate (B1-B2)
	- Advanced (C1)
- Availability / additional comments
- [Campo oculto: versión del sitio visitada]

### Tracking (opcional):
- [X] Google Analytics
- [X] Campo en formulario que indique qué versión usó el visitante

---

## 🌐 Configuración de dominio

**Dominio:** [pordefinir.com]
**Proveedor:** [GoDaddy / Namecheap / Google Domains / otro]
**Estado:** 
- [ ] Ya comprado (proveedor: _______)
- [X] Por comprar

**Subdominios necesarios:**
- `formal.tudominio.com`
- `fun.tudominio.com`
- (Opcional) `www.tudominio.com` → redirige a landing page

---

## 📱 Información de contacto

Todo lo que viene en el export de Notion

---

## 🎨 Referencias visuales

### Webs de inspiración (formal):
- https://clinicaduran.es

### Webs de inspiración (fun):
- https://geocities.restorativland.org/Area51/Capsule/1695/

**Nota:** Si tienes screenshots o ejemplos de lo que te gusta/no te gusta, 
añádelos en `/recursos/referencias/`

---

## 🚀 Prioridades

**MUST HAVE (imprescindible):**
1. Ambos skins funcionando correctamente
2. Contenido migrado de Notion
3. Formulario de contacto operativo
4. Responsive en móvil
5. Configuración de dominio (posterior)

**NICE TO HAVE (si hay tiempo):**
1. Animaciones sutiles
2. Galería de fotos
3. Sistema de reserva online integrado, para clases sueltas o llamadas introductorias, sincronizado con el calendario de google de holly para saber disponibilidad
---

## 📝 Notas adicionales

### Preferencias de diseño:
- Tipografías elegantes y sobrias pero a la vez bonitas y modernas, nada hortera, de sitios top hechos por diseñadores profesionales. 
- Sin fotos, todo texto, y como mucho algún icono para separar contenidos


### Dudas por resolver:
- [X] ¿Nombre exacto del dominio?
- [ ] ¿Colores corporativos específicos?
- [ ] ¿Logo existente o hay que crearlo?
- [ ] ¿Fotos profesionales disponibles?

---

## ✅ Checklist de preparación

Antes de empezar con Claude Code, confirma:
- [x] Contenido de Notion exportado en `/contenido-notion/`
- [X] requisitos.md completado con toda la info
- [ ] Recursos visuales recopilados (logos, fotos)
- [X] Info de contacto verificada
- [ ] Decisión tomada sobre subdominios vs rutas
- [X] Proveedor de formularios elegido

---

## 🎬 Instrucción inicial para Claude Code

Cuando esté todo listo:
```
Lee el archivo requisitos.md y revisa el contenido exportado 
de Notion en /contenido-notion/.

Vamos a crear una web Jekyll con DOS SKINS completamente 
diferentes (formal y divertida) para una profesora de inglés. 
Usaremos subdominios para cada versión.

PLAN:
1. Analiza el contenido y propón estructura del sitio
2. Diseña arquitectura técnica para dual-skin con Jekyll
3. Crea la estructura base del proyecto
4. Migra y adapta el contenido de Notion
5. Implementa ambos diseños
6. Configura para testing local
7. Prepara para GitHub Pages + dominio custom

Empecemos paso a paso. Primero, revisa todo y dame tu 
análisis y propuesta de estructura.
```