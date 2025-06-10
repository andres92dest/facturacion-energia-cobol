# facturacion-energia-cobol
Sistema de facturación de energía eléctrica desarrollado en COBOL con lectura y escritura en archivos CSV/TXT.
# ⚡ Sistema de Facturación de Energía en COBOL

Este proyecto consiste en el desarrollo de un sistema de facturación de energía eléctrica utilizando **COBOL**, con almacenamiento y lectura de datos mediante archivos **CSV** y **TXT**. El objetivo es simular una aplicación real de negocio como parte de un aprendizaje práctico en desarrollo de software legacy.

---

## 🎯 Objetivos de Aprendizaje

- Leer y procesar archivos CSV desde COBOL.
- Generar facturas en archivos TXT bajo demanda.
- Mantener un historial de consumo por cliente.
- Automatizar tareas comunes en sistemas de facturación eléctrica.
- Comprender la lógica de negocio aplicada en un entorno clásico empresarial.

---

## 📂 Estructura del Proyecto

```
facturacion-energia-cobol/
├── data/
│   ├── clientes.csv                # Información básica de los clientes
│   └── historial_consumo.csv       # Registros de consumo por cliente
├── docs/
│   └── enunciado.md                # Enunciado detallado del proyecto
├── src/
│   └── facturacion.cob             # Código fuente COBOL
├── output/
│   └── facturas-generadas/        # Facturas TXT generadas individualmente
├── README.md                       # Este archivo
```

---

## 🛠 Tecnologías

- Lenguaje: **COBOL** (compatible con Open COBOL / GnuCOBOL)
- Archivos: **CSV** para entradas y **TXT** para salidas
- Plataforma: multiplataforma (Windows, Linux)
- Editor recomendado: **Open COBOL IDE** o **Visual Studio Code** con extensión COBOL

---

## 🚦 Estado del Proyecto

🟢 En desarrollo – avances frecuentes.

✔️ Módulos planificados:
- [x] Lectura de clientes desde CSV
- [x] Módulo de historial de consumo
- [ ] Generación de facturas individuales TXT
- [ ] Módulo de actualización de consumo
- [ ] Generación de reportes por fechas o cliente

---

## 📋 Cómo usar este proyecto

1. Asegúrate de tener instalado GnuCOBOL u Open COBOL.
2. Coloca los archivos `clientes.csv` y `historial_consumo.csv` en la carpeta `data/`.
3. Ejecuta el programa desde `src/facturacion.cob`.
4. Revisa los resultados en la carpeta `output/facturas-generadas/`.

---

## 📈 Aplicaciones reales del proyecto

Este proyecto simula cómo se gestionan los sistemas de facturación de servicios públicos en empresas que aún utilizan COBOL como núcleo de sus operaciones. Es ideal para mostrar en tu portafolio como ejemplo de:

- Lógica de negocio en sistemas legados.
- Procesamiento de archivos planos.
- Generación automatizada de informes.
- Aplicación de reglas de tarifas y consumo.

---

## 🧑‍💻 Autor

Proyecto educativo creado por **Andrés David Mejía Zarza** como parte de un ejercicio práctico de programación en COBOL.  
📧 Contacto: andres92.dest@gmail.com  
🔗 GitHub: [https://github.com/andres92dest](https://github.com/andres92dest)  
🔗 LinkedIn: [https://linkedin.com/in/andres-mejia-z](https://linkedin.com/in/andres-mejia-z)

---

## 📝 Licencia

Este proyecto se distribuye bajo los términos de la **Licencia Pública General de GNU, versión 3 (GPLv3)**.  
Puedes usar, modificar y redistribuir este código respetando los términos de dicha licencia.

Para más información, visita: [https://www.gnu.org/licenses/gpl-3.0.html](https://www.gnu.org/licenses/gpl-3.0.html)
