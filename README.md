RIMEX — Landing Page
Gestión inteligente de turnos para salones de belleza. Diseñada para dueñas que quieren organizar su negocio sin complicaciones.

RIMEX Preview

🌸 Sobre el proyecto
Landing page de presentación de RIMEX, un sistema SaaS de gestión de reservas diseñado exclusivamente para salones de belleza. La página fue pensada para conectar emocionalmente con el público femenino dueño de salones, transmitiendo profesionalidad, elegancia y simplicidad.

No es solo informativa: cada sección está estructurada como un flujo de conversión que lleva a la usuaria desde el descubrimiento hasta el contacto por WhatsApp.

✨ Secciones
Sección	Objetivo
Hero	Primer impacto: propuesta de valor clara + CTA directo + mockup del sistema
Funcionalidades	6 features clave con iconos y descripciones concretas
Testimonios	3 testimonios de dueñas de salones reales (prueba social)
Por qué RIMEX	Diferenciadores SaaS: sin instalación, backups, soporte humano
Planes	Pricing simple, sin letras chicas, CTA a WhatsApp
FAQ	5 objeciones frecuentes resueltas en tono cercano
CTA Final	Cierre emocional con botón de WhatsApp
🎨 Diseño
Paleta: Crema cálido (#faf8f5) + Negro profundo (#1a1412) + Dorado (#c9a96e) + Blush terracota (#c9928e)
Tipografías: Playfair Display (títulos, elegancia) + DM Sans (cuerpo, legibilidad)
Iconos: Boxicons v2.1.4
Enfoque visual: Suave, premium, sin esquinas agresivas. Botones pill-shaped, gradientes dorado→blush, textura de ruido sutil.
Principios de diseño
Cero dependencias de frameworks CSS — Todo escrito a mano para control total
Mobile-first responsive — Funciona perfecto en celular, tablet y desktop
Accesible — Buen contraste, texto legible, semántica HTML correcta
Rápido — Sin JS innecesario, sin librerías pesadas, solo lo esencial
🛠️ Tech Stack
Tecnología	Uso
HTML5	Estructura semántica
CSS3	Estilos, animaciones, layout con Grid/Flexbox
JavaScript (Vanilla)	Scroll reveal, FAQ accordion, menú mobile, parallax sutil
Google Fonts	Playfair Display + DM Sans
Boxicons	Iconografía
No se usó: React, Tailwind, Bootstrap, ni ninguna librería CSS/JS externa.

📁 Estructura del proyecto
rimex-landing/
├── index.html # Página principal
├── img/
│ └── image.png # Mockup del sistema (hero)
├── README.md # Este archivo
└── .gitignore # Archivos ignorados por Git

text


---

## 🚀 Cómo usar

### Opción rápida

Abrir `index.html` directamente en el navegador. No necesita servidor.

### Opción recomendada (con Live Server)

```bash
# Clonar el repo
git clone https://github.com/tu-usuario/rimex-landing.git
cd rimex-landing

# Si tenés Node.js instalado
npx serve .

# O usar la extensión "Live Server" en VS Code
📱 Responsive Breakpoints
Breakpoint
Comportamiento
> 960px	Grid completo, nav con links, 3 columnas en features y testimonios
600px – 960px	Grid de 2 columnas, menú hamburguesa, testimonios en 1 columna
< 600px	Todo en 1 columna, tipografía reducida, stats apilados

⚡ Funcionalidades JS
Scroll reveal — Elementos aparecen con fade-up al entrar al viewport (IntersectionObserver)
FAQ accordion — Abre/cierra con animación suave, solo uno abierto a la vez
Menú mobile — Overlay a pantalla completa con links centrados
Nav con blur — Se vuelve translúcida al hacer scroll
Parallax sutil — El mockup del hero se mueve levemente con el mouse
Smooth scroll — Navegación interna con offset para el nav fijo
Floating animation — El mockup del hero tiene un levitamiento suave y continuo
🔗 Links importantes
WhatsApp de contacto: wa.me/+595984715050
Todos los CTAs apuntan a WhatsApp con mensajes pre-cargados según la intención (prueba gratis, plan profesional, consulta general)
📝 Notas
La imagen del mockup (img/image.png) no está incluida en el repo por tamaño. Reemplazar con la captura real del sistema.
Los testimonios son placeholders con nombres ficticios. Reemplazar con testimonios reales de clientas.
El número de WhatsApp está hardcodeado. Si cambia, buscar y reemplazar +595984715050 en todo el archivo.
Los colores están centralizados en CSS custom properties (:root) — fácil de re-tematizar.
📄 Licencia
Uso privado — INNER TECH. Todos los derechos reservados.

<p align="center">
<strong>RIMEX</strong> · Tu salón, organizado con elegancia.<br>
<sub>Desarrollado por INNER TECH</sub>
</p>
```