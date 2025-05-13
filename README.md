## Descripción del Contenido

1. &lt;header&gt;


Encabezado central con el título principal de la factura. Utiliza fondo azul y tipografía blanca para destacarse.

![imagen](https://github.com/user-attachments/assets/a0e5181d-d407-42ac-9118-b409bfc273de)

2. &lt;div class="contenedor-factura"&gt;

Contenedor general que agrupa todas las secciones de la factura.
## Secciones Internas:

✅ Empresa (.tabla-empresa)

Incluye nombre, dirección, RUC, teléfono y correo de la empresa.

![imagen](https://github.com/user-attachments/assets/03702756-5c85-4a78-9022-bd1f0d44339d)

✅ Cliente (.tabla-cliente)

Datos personales del cliente como nombre, cédula/RUC, dirección, teléfono y email.

![imagen](https://github.com/user-attachments/assets/05b307be-120c-434d-b2b4-5545db963555)

✅ Productos (.tabla-productos)

Tabla con productos adquiridos, que muestra código, descripción, cantidad, precio unitario y subtotal. También incluye un total final calculado.

![imagen](https://github.com/user-attachments/assets/12b5ceb7-7f47-4e57-a077-b98d3d04039f)

✅ Información Adicional (.tabla-adicional)

Forma de pago y observaciones, junto con un mensaje de agradecimiento al cliente.

![imagen](https://github.com/user-attachments/assets/29e8bf8d-3473-473b-9681-5f7fa8f10f5e)

## 🎨 Diseño y Estilos CSS

    Tipografía: 'Segoe UI' para una lectura clara y moderna.

    Colores: Paleta con tonos azules, verdes y naranjas para diferenciar secciones.

    Sombras y bordes: Se aplica box-shadow y bordes laterales de color para darle estilo a cada tabla.

    Capciones y tablas: Cada tabla tiene un encabezado con íconos y colores distintivos.

## Estilos Especiales

    .tabla-empresa: Borde azul.

    .tabla-cliente: Borde verde.

    .tabla-productos: Borde naranja.

    .tabla-adicional: Borde morado.

    .total-label y .total-monto: Celdas destacadas para el total.

    .pie: Mensaje final con fondo suave y centrado.








