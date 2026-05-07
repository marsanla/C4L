# Coding for Lawyers

> **Python para profesionales del derecho — sin requisitos previos.**
> Aprende a automatizar tareas repetitivas, manejar grandes volúmenes de información y trabajar con herramientas de IA con criterio profesional.

---

## ¿Qué es Coding for Lawyers?

Coding for Lawyers es un curso introductorio que enseña **Python aplicado al ámbito jurídico**. No vas a convertirte en programador profesional: el objetivo es que **entiendas el lenguaje**, puedas **automatizar tareas** que hoy haces a mano y te comuniques con eficacia con los equipos técnicos de tu despacho o empresa.

### ¿Por qué un abogado debería aprender Python?

| Tarea típica del despacho | Lo que automatizarás aprendiendo Python |
| --- | --- |
| Revisar 200 contratos buscando una cláusula | Leer y filtrar documentos en segundos |
| Calcular intereses de demora caso por caso | Crear una calculadora reutilizable |
| Generar informes mensuales de facturación | Producir CSV / Excel / PDF automáticamente |
| Detectar fechas de prescripción próximas | Sistema de alertas con fechas |
| Resumir sentencias largas | Aplicar herramientas de resumen automático |
| Trabajar con IA (Claude, ChatGPT...) | Diseñar prompts profesionales y combinarlos con scripts |

---

## ¿Para quién es este curso?

- **Abogados, juristas y profesionales del derecho** que sienten curiosidad por la tecnología.
- **Equipos *legal ops* y compliance** que quieren empezar a automatizar.
- **Estudiantes de derecho** que quieren un perfil diferenciado.
- **Profesionales no técnicos** en general que quieran entender cómo funciona la programación.

> **Requisitos previos:** ninguno. Solo necesitas un navegador y una cuenta de Google (para usar Google Colab).

---

## Estructura del curso

El curso está organizado en **seis módulos progresivos**. Se pueden impartir en distintos formatos (intensivo de varios días, sesiones semanales, autoaprendizaje...) según las necesidades del grupo.

| Módulo | Notebook | Contenido principal |
| :---: | --- | --- |
| **1** | [C4L_1 — Introducción y conceptos básicos](C4L_1_Introducción_a_la_programación,_Python_y_conceptos_básicos.ipynb) | Variables, tipos de datos, fechas (`datetime`), métodos de los tipos, listas, diccionarios |
| **2** | [C4L_2 — Control de flujo](C4L_2_Estructuras_de_control,_expresiones,_operadores_y_control_de_flujo.ipynb) | Operadores, condicionales (`if`/`elif`/`else`), bucles (`for`/`while`) |
| **3** | [C4L_3 — Funciones, archivos y datos](C4L_3_Funciones,_manejo_de_archivos,_bibliotecas_utiles_y_manejo_de_datos.ipynb) | Funciones, lectura/escritura de archivos (CSV, JSON), `pandas`, `numpy`, `matplotlib` |
| **4** | [C4L_4 — IA y prompt engineering](C4L_4_IA,_LLMs_y_prompt_engineering.ipynb) | Mini-introducción: cómo trabajar con LLMs (Claude, ChatGPT) desde la perspectiva de un abogado |
| **5** | [C4L_5 — Ejercicios consolidados](C4L_5_Ejercicios.ipynb) | Casos prácticos que combinan lo aprendido en módulos 1-3 |
| **6** | [C4L_6 — Proyecto final integrador](C4L_6_Ejercicio_final.ipynb) | Sistema de gestión legal: alertas, informes, visualización |

> **Nota sobre el módulo 4:** es **introductorio**. Se centra en dar una buena foto de conjunto sobre IA, LLMs y prompt engineering aplicados al ámbito jurídico, con bases sólidas para empezar a usar estas herramientas con criterio.

---

## Filosofía pedagógica

- **Aprender haciendo.** Cada concepto se introduce con un caso real del ámbito jurídico.
- **Mejor profundo que amplio.** Preferimos que entiendas bien los fundamentos a cubrir muchos temas superficialmente.
- **Sin jerga innecesaria.** Cuando aparece un término técnico, se explica en lenguaje llano.
- **Apoyo visual constante.** Tablas comparativas, esquemas y ejemplos paralelos en cada sección.
- **Glosario en cada módulo.** Para que siempre tengas a mano una traducción de los conceptos.

---

## Cómo usar este repositorio

Tienes **tres formas** de seguir el curso. Elige la que más te convenga:

### Opción 1 — Google Colab *(recomendada)*

Es la forma **más sencilla**: no requiere instalar nada en tu ordenador.

1. Pulsa el botón **"Open in Colab"** que aparece al inicio de cada notebook.
2. Inicia sesión con tu cuenta de Google.
3. Ya puedes leer las celdas de texto y **ejecutar el código** pulsando ▶ (o `Mayús + Enter`).

### Opción 2 — Clonar el repositorio en local

Si prefieres tener los archivos en tu ordenador:

```bash
git clone https://github.com/marsanla/C4L.git
cd C4L
```

Después puedes abrir los notebooks con **Jupyter** (`pip install jupyter && jupyter notebook`) o con **VS Code**.

### Opción 3 — Descargar archivos sueltos

Pulsa en cualquier notebook del listado de arriba, después en **"Raw"** o usa el botón "Download" de GitHub.

---

## Estructura típica de un notebook

Cada notebook sigue siempre la misma estructura para que sea fácil orientarse:

1. **Bienvenida y objetivos** — qué vas a aprender y por qué importa.
2. **Sección de teoría** — conceptte explicados con tablas, ejemplos y analogías legales.
3. **Sección de ejercicios prácticos** — de menos a más, todos sobre escenarios jurídicos reales.
4. **Glosario rápido** — todos los términos técnicos del módulo en lenguaje llano.

---

## Recursos adicionales

- **Documentación oficial de Python (en español):** <https://docs.python.org/es/3/>
- **Tutorial de pandas:** <https://pandas.pydata.org/docs/user_guide/index.html>
- **Tutorial de NumPy:** <https://numpy.org/doc/stable/user/index.html>
- **Tutorial de Matplotlib:** <https://matplotlib.org/stable/users/index.html>
- **Documentación de la API de Claude (Anthropic):** <https://docs.anthropic.com/>

---

## Preguntas frecuentes

<details>
<summary><strong>No tengo formación técnica. ¿Es para mí?</strong></summary>

Sí. El curso está diseñado **específicamente** para profesionales del derecho **sin formación previa en programación**. Todo se explica en lenguaje llano y con ejemplos jurídicos.
</details>

<details>
<summary><strong>¿Necesito instalar Python o algún programa?</strong></summary>

No. Usamos **Google Colab**, que funciona enteramente en el navegador. Solo necesitas una cuenta de Google.
</details>

<details>
<summary><strong>¿En qué idioma están los notebooks?</strong></summary>

En **castellano de España**. Los términos técnicos en inglés (los que se usan tal cual en el sector) se mantienen en inglés y se explican.
</details>

<details>
<summary><strong>¿Puedo usar el material para impartir mi propia formación?</strong></summary>

El material es de uso libre con atribución.
</details>

<details>
<summary><strong>¿Cuánto tiempo lleva completar el curso?</strong></summary>

Depende del ritmo. Como referencia: cada módulo está pensado para una sesión de **3-4 horas** entre teoría y ejercicios. Los seis módulos en total: aproximadamente **20-25 horas de trabajo**.
</details>

<details>
<summary><strong>¿Qué hago si me atasco?</strong></summary>

1. Lee el mensaje de error con calma — Python casi siempre dice **exactamente** dónde está el problema.
2. Revisa el glosario del módulo.
3. Pega el error en Claude o ChatGPT y pídele que te lo explica.
4. Si nada funciona, abre un *issue* en este repositorio.
</details>


---

## Licencia y contacto

- **Autor**: Marcos Sanz Latorre.
- **Email**: [marcossanzlatorre@gmail.com](mailto:marcossanzlatorre@gmail.com).

> Si este curso te ha resultado útil, **dale una ⭐ al repositorio** y compártelo con compañer@s del sector.
