# 🌐 Web Accessibility Practice - WCAG 2.2

[![WCAG 2.2](https://img.shields.io/badge/WCAG-2.2%20AA-green.svg)](https://www.w3.org/WAI/WCAG22/quickref/)
[![Accessibility](https://img.shields.io/badge/Accessibility-100%25-success.svg)](https://www.w3.org/WAI/)
[![HTML5](https://img.shields.io/badge/HTML5-Valid-orange.svg)](https://validator.w3.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## 📖 Translations / Traducciones

- **[Español](doc/readme_es.md)** - Documentación completa en español
- **[English](doc/readme_en.md)** - Complete documentation in English

---

## 🎯 About This Project / Acerca de este Proyecto

**[EN]** This project demonstrates the transformation of inaccessible HTML/CSS code into fully WCAG 2.2 Level AA compliant web pages. It serves as a practical guide for implementing web accessibility best practices.

**[ES]** Este proyecto demuestra la transformación de código HTML/CSS inaccesible en páginas web totalmente conformes con WCAG 2.2 Nivel AA. Sirve como guía práctica para implementar las mejores prácticas de accesibilidad web.

---

## ✨ Key Features / Características Principales

- ✅ **Semantic HTML5** / HTML5 Semántico
- ✅ **ARIA Attributes** / Atributos ARIA
- ✅ **Keyboard Navigation** / Navegación por Teclado
- ✅ **Screen Reader Compatible** / Compatible con Lectores de Pantalla
- ✅ **High Contrast Colors** (16.75:1) / Colores de Alto Contraste
- ✅ **Responsive Design** / Diseño Responsive
- ✅ **200% Zoom Support** / Soporte para Zoom al 200%
- ✅ **Touch Target Size** (24x24px min) / Tamaño de Objetivos Táctiles

---

## 📂 Project Structure / Estructura del Proyecto

```
Practica-Accesibilidad/
│
├── 📁 original/              # Original inaccessible code
│   ├── index.html            # Código original inaccesible
│   ├── content.html
│   ├── form-page.html
│   ├── gallery.html
│   └── data-table.html
│
├── 📁 corregido/             # Accessible WCAG 2.2 AA code
│   ├── styles.css            # Código accesible WCAG 2.2 AA
│   ├── index.html
│   ├── content.html
│   ├── form-page.html
│   ├── gallery.html
│   └── data-table.html
│
├── 📁 capturas/              # Validation screenshots
│   ├── originales/           # Capturas de validación
│   └── mejoradas/
│
└── 📁 doc/                   # Documentation / Documentación
    ├── readme_es.md          # 🇪🇸 Spanish full docs
    └── readme_en.md          # 🇬🇧 English full docs
```

---

## 🚀 Quick Start / Inicio Rápido

### View the Project / Ver el Proyecto

```bash
# Clone the repository / Clonar el repositorio
git clone https://github.com/Miguel-Angel-Laurero/Practica-Accesibilidad.git

# Navigate to project / Navegar al proyecto
cd Practica-Accesibilidad

# Open accessible version / Abrir versión accesible
cd corregido
# Open index.html in your browser / Abrir index.html en el navegador
```

### Test Accessibility / Probar Accesibilidad

**Keyboard Navigation / Navegación por Teclado:**
- `Tab` - Navigate forward / Avanzar
- `Shift + Tab` - Navigate backward / Retroceder
- `Enter` - Activate links/buttons / Activar enlaces/botones
- `Space` - Select checkboxes / Seleccionar checkboxes

**Validation Tools / Herramientas de Validación:**
- [Lighthouse](https://developers.google.com/web/tools/lighthouse) - Chrome DevTools
- [axe DevTools](https://www.deque.com/axe/devtools/) - Browser Extension
- [WAVE](https://wave.webaim.org/) - Web Accessibility Evaluation

---

## 📊 Validation Results / Resultados de Validación

| Metric / Métrica | Before / Antes | After / Después |
|-------------------|----------------|------------------|
| **Lighthouse Accessibility** | 45-60 | **95-100** ✅ |
| **axe DevTools Errors** | 15-25 | **0** ✅ |
| **WAVE Errors** | 20+ | **0** ✅ |
| **Contrast Ratio** | 2.8:1 ❌ | **16.75:1** ✅ |
| **Keyboard Navigation** | Partial / Parcial | **Complete / Completa** ✅ |
| **Screen Readers** | Difficult / Difícil | **Optimal / Óptima** ✅ |

---

## 🔍 What Was Fixed / Qué Se Corrigió

### Structural Issues / Problemas Estructurales

❌ **Before / Antes:**
- Non-semantic `<div>` tags / Etiquetas `<div>` no semánticas
- Incorrect heading hierarchy / Jerarquía de encabezados incorrecta
- No landmark regions / Sin regiones landmark

✅ **After / Después:**
- Semantic HTML5 (`<header>`, `<nav>`, `<main>`, `<footer>`)
- Logical heading structure / Estructura lógica de encabezados
- Proper ARIA landmarks / Landmarks ARIA apropiados

### Form Accessibility / Accesibilidad de Formularios

❌ **Before / Antes:**
- Inputs without labels / Inputs sin labels
- No validation messages / Sin mensajes de validación
- Missing ARIA attributes / Atributos ARIA faltantes

✅ **After / Después:**
- All inputs have associated labels / Todos los inputs tienen labels asociados
- `aria-required`, `aria-describedby` implemented / Implementado
- Contextual help messages / Mensajes de ayuda contextual

### Visual Accessibility / Accesibilidad Visual

❌ **Before / Antes:**
- Low contrast (2.8:1) / Bajo contraste
- No visible focus / Foco no visible
- Small touch targets / Objetivos táctiles pequeños

✅ **After / Después:**
- High contrast (16.75:1 - AAA) / Alto contraste
- Clear focus indicators (3px ring) / Indicadores de foco claros
- Touch targets ≥ 24x24px (AA compliant / Cumple AA)

---

## 📸 Screenshots / Capturas

### Validation Tools / Herramientas de Validación

Documentation includes screenshots of:
La documentación incluye capturas de:

- ✅ **Chrome Lighthouse** - Perfect accessibility scores
- ✅ **axe DevTools** - Zero critical errors
- ✅ **WAVE** - Clean accessibility report
- ✅ **Contrast Checker** - AAA compliance
- ✅ **HTML Validator** - Valid markup
- ✅ **Screen Readers** - NVDA testing

*Full screenshots available in* `/capturas/mejoradas/`  
*Capturas completas disponibles en* `/capturas/mejoradas/`

---

## 🎓 Learning Resources / Recursos de Aprendizaje

### Official Guidelines / Guías Oficiales
- [WCAG 2.2](https://www.w3.org/WAI/WCAG22/quickref/) - Official standards
- [WAI-ARIA](https://www.w3.org/WAI/ARIA/apg/) - Authoring Practices Guide

### Testing Tools / Herramientas de Prueba
- [WebAIM](https://webaim.org/) - Resources and tools
- [Deque University](https://dequeuniversity.com/) - Training courses
- [A11y Project](https://www.a11yproject.com/) - Community-driven checklist

### Screen Readers / Lectores de Pantalla
- [NVDA](https://www.nvaccess.org/) - Free for Windows
- [JAWS](https://www.freedomscientific.com/products/software/jaws/) - Commercial
- VoiceOver - Built into macOS/iOS

---

## 📋 WCAG 2.2 Compliance / Conformidad WCAG 2.2

### Level A ✅ (100%)
All 25 applicable Level A criteria met  
Todos los 25 criterios aplicables de Nivel A cumplidos

### Level AA ✅ (100%)
All 20 applicable Level AA criteria met  
Todos los 20 criterios aplicables de Nivel AA cumplidos

### New in WCAG 2.2 / Nuevo en WCAG 2.2
- ✅ **2.4.11** Focus Not Obscured (Minimum) / Foco No Oscurecido (Mínimo)
- ✅ **2.5.7** Dragging Movements / Movimientos de Arrastre
- ✅ **2.5.8** Target Size (Minimum) / Tamaño del Objetivo (Mínimo)
- ✅ **3.2.6** Consistent Help / Ayuda Consistente
- ✅ **3.3.7** Redundant Entry / Entrada Redundante

---

## 🤝 Contributing / Contribuir

**[EN]** Contributions are welcome! Please read the full documentation before submitting pull requests.

**[ES]** ¡Las contribuciones son bienvenidas! Por favor lee la documentación completa antes de enviar pull requests.

1. Fork the repository / Haz fork del repositorio
2. Create a feature branch / Crea una rama de características
3. Commit your changes / Confirma tus cambios
4. Push to the branch / Empuja a la rama
5. Open a Pull Request / Abre un Pull Request

---

## 📝 License / Licencia

This project is open source and available under the MIT License.  
Este proyecto es de código abierto y está disponible bajo la Licencia MIT.

---

## 👨‍💻 Author / Autor

**Miguel Ángel Laurero**

- GitHub: [@Miguel-Angel-Laurero](https://github.com/Miguel-Angel-Laurero)
- Repository / Repositorio: [Practica-Accesibilidad](https://github.com/Miguel-Angel-Laurero/Practica-Accesibilidad)

---

## 🌟 Acknowledgments / Agradecimientos

**[EN]** This project was created as a learning exercise to understand and implement WCAG 2.2 accessibility guidelines. Special thanks to the W3C WAI team for their comprehensive documentation.

**[ES]** Este proyecto fue creado como un ejercicio de aprendizaje para entender e implementar las pautas de accesibilidad WCAG 2.2. Agradecimientos especiales al equipo W3C WAI por su documentación exhaustiva.

---

## 📞 Support / Soporte

**[EN]** For questions or issues, please:
- Open an issue on GitHub
- Read the full documentation in [`/doc/`](doc/) folder

**[ES]** Para preguntas o problemas, por favor:
- Abre un issue en GitHub
- Lee la documentación completa en la carpeta [`/doc/`](doc/)

---

<div align="center">

### ⭐ Star this repository if you found it helpful! / ¡Dale estrella si te resultó útil!

**Last Updated / Última Actualización:** February 17, 2026  
**Version / Versión:** 1.0  
**Status / Estado:** ✅ Production Ready / Listo para Producción

</div>
