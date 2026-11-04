# Cotizador EcoClean — Tema 7

Mini aplicación web académica de una sola página para **Lavandería EcoClean**.

## Problema
Una microempresa puede cometer errores al calcular cotizaciones manualmente. Esta herramienta calcula rápidamente un subtotal, un costo fijo de entrega opcional y un total.

## Funcionalidades
- Lavado y secado: $1,60 por kg.
- Planchado: $1,00 por prenda.
- Lavado de cobija: $5,00 por unidad.
- Entrega a domicilio: +$2,00 fijos.
- Validación de cantidad entre 1 y 1000 y botón para copiar el resumen.

## Cómo usar
Abrir `index.html` con doble clic en un navegador moderno. No requiere instalación ni conexión a una base de datos.

## Pruebas propuestas
1. 5 kg de lavado, sin entrega = $8,00.
2. 5 kg de lavado, con entrega = $10,00.
3. 3 prendas planchadas, con entrega = $5,00.
4. 2 cobijas, sin entrega = $10,00.
5. Cantidad 0, negativa, decimal o vacía debe mostrar una advertencia.

## Cómo publicarlo
Subir `index.html` y `README.md` (NO el archivo ZIP) a la raíz de un repositorio GitHub. Importar el repositorio desde Vercel con preset `Other`, directorio raíz `./` y sin compilación.

## Seguridad
Negocio y precios ficticios; no incluir datos de clientes, contraseñas, credenciales ni datos bancarios.
