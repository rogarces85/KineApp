# KINEAPP — Contexto general del proyecto

## Qué es KINEAPP

KINEAPP es una plataforma destinada a la elaboración de **informes kinesiológicos**:
documentos técnicos que describen la condición de un paciente a partir de los conceptos
clínicos que el kinesiólogo ingresa.

Cada informe debe ser **certero en lo técnico y entendible en su explicación**, es decir,
redactado con rigor profesional pero con un lenguaje que cualquier lector pueda comprender.
La plataforma debe comportarse como un **experto en fisioterapia** al momento de elaborarlo.

## Problema o necesidad que resuelve

La redacción de informes kinesiológicos es una tarea repetitiva, lenta y dependiente de la
disponibilidad y del criterio de cada profesional. KINEAPP busca reducir ese tiempo de
elaboración manteniendo —o aumentando— la calidad y la uniformidad de los informes, sin
perder el criterio profesional del kinesiólogo.

Además, el profesional debe consultar fuentes variables sobre el concepto ingresado.
KINEAPP reúne esa búsqueda en el propio flujo de elaboración del informe.

## Idea general de la solución

El kinesiólogo ingresa los conceptos correspondientes al paciente en un **formulario**.
A partir de esa información, KINEAPP:

- consulta en internet la información referente al concepto ingresado;
- actúa como experto en fisioterapia para interpretar esos conceptos;
- redacta el informe kinesiológico con una explicación entendible;
- propone **objetivos terapéuticos**;
- elabora un **plan de entrenamiento** cuando sea necesario para la vuelta al ejercicio.

## Usuarios / público objetivo

Usuario principal: el **kinesiólogo**, que ingresa los datos y utiliza el informe como
soporte de su trabajo profesional. El contenido generado está dirigido al ámbito de la
fisioterapia.

## Objetivo general del proyecto

Proporcionar al kinesiólogo una herramienta que, a partir de los conceptos clínicos que
ingresa en un formulario, produzca de forma consistente un informe kinesiológico técnico
y comprensible, con objetivos terapéuticos y, cuando corresponda, un plan de entrenamiento
orientado a la vuelta al ejercicio.

## Tecnologías y restricciones generales

- **Stack tecnológico: HTML5, JavaScript y CSS.** Es la base tecnológica del proyecto y
  debe respetarse.
- La plataforma se apoyará en **inteligencia artificial (modelo de lenguaje)** para generar
  y redactar el contenido, actuando con criterio de experto en fisioterapia.
- La plataforma **consultará fuentes en internet** en relación al concepto ingresado.
- **Idioma de salida: español.**
- **Codificación: UTF-8.** Aplica tanto a los archivos del proyecto como al contenido
  generado por la plataforma.
- El contenido generado es un **soporte profesional**; no reemplaza el criterio ni la
  responsabilidad clínica del kinesiólogo.

## Estado actual y alcance de este documento

Este documento establece únicamente el **contexto, propósito y alcance inicial** de KINEAPP.

Su propósito es que cualquier agente de IA o desarrollador que se incorpore al proyecto
comprenda rápidamente qué se quiere construir y por qué.

Queda **fuera de su alcance**, de forma deliberada:

- especificaciones funcionales detalladas;
- arquitectura del sistema y decisiones técnicas;
- estructura de archivos, clases, funciones o cualquier detalle de implementación;
- funcionalidades no mencionadas en esta definición.

Toda esa información se definirá en documentos posteriores.