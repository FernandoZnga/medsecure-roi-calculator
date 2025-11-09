# 🏥 MedSecure ROI Calculator

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/FernandoZnga/medsecure-roi-calculator/graphs/commit-activity)

> **Interactive ROI calculator for hospital cybersecurity investments** | Herramienta interactiva para calcular el Retorno de Inversión (ROI) en ciberseguridad hospitalaria

**Specifically designed for healthcare institutions in Latin America, with focus on Honduras, Central America.**

[🌐 **Live Demo**](https://fernandoznga.github.io/medsecure-roi-calculator/) | [📖 Documentation](#-documentación-de-respaldo) | [🤝 Contributing](#-contributing)

---

## 🌟 Features

- ✅ **Real-world case studies** from documented hospital ransomware attacks
- ✅ **Pre-configured scenarios** (Realistic, Conservative, Pessimistic)
- ✅ **Interactive calculations** with instant results
- ✅ **Comprehensive cost analysis** (direct and indirect costs)
- ✅ **Spanish language** optimized for Latin American healthcare sector
- ✅ **Zero dependencies** - pure HTML/CSS/JavaScript
- ✅ **Responsive design** - works on all devices
- ✅ **Print-friendly** reports for presentations

---

## 🎯 Why MedSecure ROI Calculator?

Cybersecurity investments in healthcare often face skepticism. This calculator provides:

- **Evidence-based calculations** backed by real hospital breach costs
- **Transparent methodology** with documented sources
- **Adjustable parameters** to match your hospital's profile
- **Executive-ready reports** for board presentations

**Key Statistics:**
- 74% of hospitals reported cyberattacks in 2023
- Average healthcare ransomware payment: $2.1M USD
- Average downtime: 15-30 days
- Total cost per incident: $20-100M+

---

## 📁 Project Structure / Estructura del Proyecto

```
medsecure-roi-calculator/
├── index.html                    # 🖥️  Interactive calculator (START HERE)
├── justificacion-roi.md          # 📊 Complete justification with real cases & sources
├── defensa-roi-resumen.md        # 🛡️  Arguments to defend ROI to skeptics
├── README.md                     # 📖 This file
├── LICENSE                       # ⚖️  MIT License
└── .gitignore                    # 🚫 Git ignore rules
```

## 🚀 Quick Start / Inicio Rápido

### Option 1: View Online (Recommended)

👉 **[Open Live Demo](https://fernandoznga.github.io/medsecure-roi-calculator/)**

### Option 2: Run Locally

**Clone the repository:**
```bash
git clone https://github.com/FernandoZnga/medsecure-roi-calculator.git
cd medsecure-roi-calculator
```

**Open in browser:**

**Mac/Linux:**
```bash
open index.html
```

**Windows:**
```bash
start index.html
```

**Or simply:** Double-click `index.html` in your file explorer.

---

### 2. Navegación de la Calculadora

La calculadora incluye:

#### 🏥 **Casos Reales Documentados**
- Ver ejemplos de hospitales que sufrieron ataques reales
- Costos verificados de casos como Scripps Health ($112.7M) y UHS ($67M)

#### ⚙️ **Escenarios Preconfigurados**
Tres escenarios para probar:

1. **📊 Realista** - Valores por defecto basados en promedios de la industria
2. **🔒 Conservador** - Parámetros más cautelosos (45% probabilidad, 70% efectividad)
3. **📈 Pesimista** - Peor caso (85% probabilidad, costos más altos)

**💡 Recomendación:** Si alguien dice que el ROI es "demasiado alto", prueba el escenario conservador.

#### 🔧 **Parámetros Ajustables**

**Características del Hospital:**
- Número de camas
- Ingresos diarios
- Cirugías mensuales
- Registros de pacientes

**Escenario de Ataque:**
- Días de paralización (promedio: 15-30 días)
- Monto de rescate ($3-10M típico)
- % de operación durante crisis
- % de datos irrecuperables

**Costos Adicionales:**
- Recuperación de sistemas IT
- Multas y demandas
- Pérdida reputacional
- Aumento de seguros

**Inversión en Ciberseguridad:**
- Inversión inicial en tecnología
- Mantenimiento anual
- Probabilidad de ataque (sin protección)
- Efectividad de la protección

---

### 3. Interpretar Resultados

La calculadora muestra:

- **Costo Total de un Ataque** - Impacto financiero completo
- **Pérdida por Paralización** - Ingresos perdidos durante downtime
- **Rescate + Recuperación** - Costos directos del ataque
- **Inversión Total en Ciberseguridad (5 años)** - Tu inversión
- **Ahorro Esperado (5 años)** - Pérdidas evitadas por protección
- **🎯 ROI (Retorno de Inversión)** - Porcentaje de retorno
- **💡 Recomendación** - Interpretación basada en el ROI calculado
- **📋 Justificación del ROI** - Contexto y validación de los resultados

---

## 📖 Documentación de Respaldo

### Para Entender los Números: `justificacion-roi.md`

**Contenido:**
- ✅ 5 casos reales documentados con fuentes verificables
- ✅ Desglose de costos directos e indirectos
- ✅ Estadísticas de la industria (2023-2024)
- ✅ Cálculo detallado paso a paso
- ✅ Referencias a estudios de Ponemon, Sophos, IBM Security

**Cuándo usar:**
- Quieres entender cómo se calculan los números
- Necesitas fuentes y referencias para tu presentación
- Alguien pregunta "¿de dónde salen estos datos?"

---

### Para Defender el ROI: `defensa-roi-resumen.md`

**Contenido:**
- ✅ Respuesta directa a la objeción "el ROI es muy alto"
- ✅ 3 argumentos irrefutables con datos concretos
- ✅ Analogías simples para explicar el concepto
- ✅ Análisis de sensibilidad
- ✅ Errores comunes de los escépticos
- ✅ Argumentos específicos para Junta Directiva, CFO, CEO

**Cuándo usar:**
- Alguien cuestiona el ROI
- Necesitas presentar ante ejecutivos escépticos
- Quieres argumentos puntuales y contundentes

---

## 🎯 Escenarios de Uso

### Escenario 1: Presentación a la Junta Directiva

**Preparación:**
1. Abre `index.html` y usa el escenario **Conservador**
2. Toma captura de pantalla de los resultados
3. Lee `defensa-roi-resumen.md` - sección "Para la Junta Directiva"
4. Ten `justificacion-roi.md` como respaldo para preguntas

**Mensaje clave:**
> "Este no es un gasto, es una póliza de seguro con ROI positivo. Incluso en el escenario más conservador, recuperamos la inversión en X años y evitamos pérdidas de $XXM."

---

### Escenario 2: Justificación al CFO

**Preparación:**
1. Usa el escenario **Realista** primero
2. Compara con el escenario **Conservador**
3. Muestra que AMBOS tienen ROI positivo
4. Enfatiza el análisis de valor esperado

**Mensaje clave:**
> "Matemáticamente, el costo de NO invertir es 10-20x mayor que el costo de invertir. Incluso si ajustamos todos los parámetros a niveles muy conservadores, el ROI sigue siendo positivo."

---

### Escenario 3: Convencer a un Escéptico

**Preparación:**
1. Pregúntales qué parámetros consideran realistas
2. Ajusta la calculadora con SUS números
3. Muéstrales que el ROI sigue siendo positivo
4. Muéstrales los casos reales en `justificacion-roi.md`

**Mensaje clave:**
> "Entiendo tu escepticismo. Usemos TUS números para calcular el ROI. Incluso con parámetros extremadamente conservadores, la inversión se justifica. Ahora, veamos qué les pasó a Scripps Health y UHS..."

---

## 📊 Datos Clave para Memorizar

### Estadísticas de la Industria
- **74%** de hospitales reportaron ciberataques en 2023
- **25%** sufrieron ransomware específicamente
- **$2.1M** promedio de rescate en sector salud (vs $1.5M otros sectores)
- **15-30 días** promedio de paralización
- **$400/registro** costo de pérdida de datos médicos

### Casos Reales Destacados
- **Scripps Health:** $112.7M - 33 días
- **Universal Health Services:** $67M - 3 semanas
- **Hospital Clínic Barcelona:** €5-8M - 2 semanas
- **Düsseldorf University:** Primera muerte por ransomware

### Costos Típicos
- **Inversión inicial:** $1-2M
- **Mantenimiento anual:** $300-500K
- **Costo de ataque:** $20-100M+
- **ROI típico:** 200-400%

---

## 🔧 Personalización

### Ajustar para tu Hospital Específico

**Paso 1:** Obtén datos reales de tu hospital
- Ingresos diarios (pregunta a finanzas)
- Número de camas (público)
- Registros de pacientes (pregunta a IT/Records)

**Paso 2:** Consulta cotizaciones reales
- Firewall + EDR + SIEM (pide cotización)
- SOC/Monitoreo (pregunta a proveedores)
- Personal de ciberseguridad (RH)

**Paso 3:** Ajusta probabilidades según tu contexto
- ¿Han tenido incidentes antes? (aumenta probabilidad)
- ¿Tienen alguna protección básica? (ajusta efectividad)
- ¿Están en zona de alto riesgo? (aumenta probabilidad)

---

## ❓ Preguntas Frecuentes

### P1: ¿Por qué el ROI es tan alto?

**R:** Por la asimetría de costos. Un ataque puede costar $20-100M, mientras que la protección cuesta $3-5M en 5 años. Incluso con baja probabilidad, los números favorecen la inversión.

### P2: ¿Son reales estos casos documentados?

**R:** Sí. Scripps Health y Universal Health Services reportaron sus pérdidas en SEC Filings (10-Q), documentos legales auditados. Puedes buscarlos públicamente.

### P3: ¿Por qué Honduras sería diferente?

**R:** En realidad, Honduras podría tener MAYOR riesgo porque:
- Infraestructura IT menos madura
- Menos hospitales de respaldo
- Mayor impacto reputacional (mercado más pequeño)
- Potencialmente recuperación más lenta

### P4: ¿Qué pasa si nunca nos atacan?

**R:** Aún así ganas porque:
1. La protección reduce otros riesgos (malware, phishing, errores)
2. Cumplimiento regulatorio
3. Mejora eficiencia operativa
4. Tranquilidad y reputación

Es como el seguro contra incendios: el hecho de que no se queme el hospital no significa que fue mala inversión.

---

## 📞 Soporte

**Creador:** Calculadora ROI - Ciberseguridad Hospitalaria  
**Versión:** 1.0  
**Última actualización:** 2025  
**Basado en:** Casos reales documentados + Estadísticas de industria verificables

---

## 📚 Fuentes Principales

- **Ponemon Institute:** "Cost of a Data Breach Report 2023"
- **Sophos:** "State of Ransomware in Healthcare 2023"
- **IBM Security:** "X-Force Threat Intelligence Index"
- **Coveware:** Quarterly Ransomware Reports
- **HIMSS:** Healthcare Cybersecurity Survey 2023
- **SEC Filings:** Scripps Health (10-Q), UHS (10-Q)

---

## 🎓 Cómo Presentar Esto

### Estructura Sugerida de Presentación

1. **Problema** (2 mins)
   - Mostrar casos reales (Scripps, UHS)
   - Enfatizar: 74% de hospitales atacados

2. **Solución** (3 mins)
   - Presentar inversión propuesta
   - Desglosar componentes (firewall, EDR, SOC, etc.)

3. **Análisis** (5 mins)
   - Demostrar calculadora en vivo
   - Mostrar escenario realista Y conservador
   - Enfatizar que AMBOS tienen ROI positivo

4. **Justificación** (3 mins)
   - Comparar con otros sectores
   - Mostrar matemática de valor esperado
   - Analogía del seguro contra incendios

5. **Cierre** (2 mins)
   - Pregunta clave: "¿Podemos sobrevivir a un ataque sin esto?"
   - Call to action: Aprobar inversión

**Total:** 15 minutos + Q&A

---

## ✅ Checklist Pre-Presentación

- [ ] Revisé todos los archivos (index.html, justificacion-roi.md, defensa-roi-resumen.md)
- [ ] Probé la calculadora con datos reales de mi hospital
- [ ] Memoricé 3-4 casos reales clave
- [ ] Tengo las cotizaciones de proveedores de ciberseguridad
- [ ] Preparé respuestas a objeciones comunes
- [ ] Practiqué la presentación al menos 2 veces
- [ ] Tengo backup de documentación en caso de preguntas difíciles

---

**¡Buena suerte con tu presentación! Los números están de tu lado.** 💪

---

## 🤝 Contributing

Contributions are welcome! Whether you're:

- 🐛 Reporting a bug
- 💡 Suggesting a new feature
- 📝 Improving documentation
- 🌍 Adding translations
- 📊 Updating statistics with new data

**How to contribute:**

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Please read our [Contributing Guidelines](CONTRIBUTING.md) for more details.

---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

You are free to:
- ✅ Use commercially
- ✅ Modify
- ✅ Distribute
- ✅ Private use

---

## 🙏 Acknowledgments

- **Data Sources:** Ponemon Institute, Sophos, IBM Security, Coveware, HIMSS
- **Case Studies:** SEC Filings from Scripps Health, UHS, and other healthcare organizations
- **Inspiration:** Healthcare cybersecurity professionals fighting to protect patient data and lives

---

## 📧 Contact

**Project Maintainer:** [@FernandoZnga](https://github.com/FernandoZnga)

For questions, suggestions, or collaboration opportunities:
- 📫 Open an [issue](https://github.com/FernandoZnga/medsecure-roi-calculator/issues)
- 💬 Start a [discussion](https://github.com/FernandoZnga/medsecure-roi-calculator/discussions)

---

## ⭐ Support This Project

If this tool helped you justify cybersecurity investments at your hospital, please:

- ⭐ Star this repository
- 🔗 Share it with colleagues in healthcare IT/security
- 📣 Spread the word about hospital cybersecurity importance
- 🤝 Contribute improvements or translations

**Together we can make healthcare more secure!**

---

## 🔒 Disclaimer

**This calculator is for educational and planning purposes only.** Actual cybersecurity costs and risks vary significantly by institution. Consult with cybersecurity professionals and conduct proper risk assessments before making investment decisions.

The authors are not liable for any decisions made based on the calculator's output.

---

## 📊 Project Stats

![GitHub Stars](https://img.shields.io/github/stars/FernandoZnga/medsecure-roi-calculator?style=social)
![GitHub Forks](https://img.shields.io/github/forks/FernandoZnga/medsecure-roi-calculator?style=social)
![GitHub Issues](https://img.shields.io/github/issues/FernandoZnga/medsecure-roi-calculator)
![GitHub Pull Requests](https://img.shields.io/github/issues-pr/FernandoZnga/medsecure-roi-calculator)

---

<div align="center">

**Made with ❤️ for healthcare cybersecurity professionals**

[⬆ Back to Top](#-medsecure-roi-calculator)

</div>
