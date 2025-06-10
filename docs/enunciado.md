# 📄 Enunciado del Proyecto: Sistema de Facturación de Energía en COBOL

## Descripción General

Desarrollar un sistema en COBOL que procese el consumo de energía eléctrica de clientes, genere facturas en archivos `.txt` bajo demanda y mantenga un historial de consumos en un archivo `.csv`. Se debe permitir actualizar nuevos consumos y generar informes individuales o por rango de fechas.

---

## Archivos involucrados

- `clientes.csv`: contiene los datos básicos de los clientes.
- `historial_consumo.csv`: almacena los consumos registrados por cada cliente.
- `factura_<id_cliente>_<anio>_<mes>.txt`: se genera cuando se solicita una factura.

---

## Funcionalidades Requeridas

1. Leer y validar los datos de `clientes.csv`.
2. Registrar consumos nuevos en `historial_consumo.csv`.
3. Calcular el total a pagar por cliente según tarifas.
4. Generar una factura TXT al momento de la solicitud.
5. Permitir consultar historial de consumos de un cliente.
6. Evitar duplicados de cliente+mes.
7. Permitir actualizar y agregar nuevos clientes si es necesario.

---

## Reglas de Negocio

- Tarifa base por tipo de usuario:
  - Residencial: $500/kWh
  - Comercial: $700/kWh
  - Industrial: $900/kWh
- Consumo > 500 kWh → recargo del 10%
- IVA opcional: 19%
