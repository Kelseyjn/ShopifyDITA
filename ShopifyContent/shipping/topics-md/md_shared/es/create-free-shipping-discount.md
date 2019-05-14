## Crear un descuento de envío gratis

Si deseas ofrecer envío gratuito, puedes crear un descuento de envío gratis.

Los descuentos de envío gratis nunca se aplicarán automáticamente a un pedido. Tus clientes deben introducir el código durante la compra para recibir el descuento. Para ofrecer automáticamente a tus clientes el envío gratuito según el precio de su pedido, debes [establecer una tarifa de envío gratuita](/manual/shipping/rates-and-methods/examples/#free-shipping-over-a-set-dollar-amount).

> Nota: Configura una [tarifa de envío gratis](/manual/shipping/rates-and-methods/examples/#free-shipping-over-a-set-dollar-amount) en la página [**Envío**](//www.shopify.com/admin/settings/shipping) en tu panel de control de Shopify. Esto se aplicará a todos los pedidos que cumplan con los criterios de envío gratis que hayas establecido.

{{ 'xh4DEZVkNuA' | youtube }}

{% include link-to-more-videos.md %}

#### Pasos

{% sections "Desktop, iPhone, Android" %}

{% comment %} Sección de escritorio {% endcomment %}

{% include admin_sidebar/discounts.md %}

1. En la página **Descuentos**, haz clic en **Crear descuento**.

2. En la sección **Código de descuento**, introduce un nombre para el nuevo código de descuento (por ejemplo, `freeshipping4smallorders`). Para generar un código de descuento aleatorio, haz clic en **Generar código**.

3. En la sección **Opciones**, selecciona el tipo de descuento **Envío gratis**.

4. En la sección **Países**, deja **Todos los países** seleccionados o elige los países a los que deseas aplicar el descuento.

    Si deseas excluir el envío gratuito en las tarifas de envío por encima de un cierto monto, marca la casilla **Excluir tarifas de envío a partir de un monto determinado** e introduce el monto en el campo. Este descuento se aplica únicamente a las tarifas de envío y no está relacionado con los montos del pedido.

5. En la sección **Elegibilidad del cliente**, selecciona a quién se aplicará este descuento: **Todos**, **Grupos específicos de clientes** o **Clientes específicos**.

    Usa el campo de búsqueda para elegir las personas o grupos que deseas que reciban el descuento. Los listados de clientes muestran el correo electrónico que se utilizó para registrarse en tu tienda. Si no se proporcionó un correo electrónico, la lista mostrará el número de teléfono del cliente.

    Para eliminar un cliente individual o un grupo de clientes de la elegibilidad para un descuento, haz clic en la **X** al lado del nombre del cliente o del grupo.

    Para leer más acerca de cómo crear grupos de clientes, consulta [_Gestión de clientes_](/manual/customers/manage-customers#create-customer-groups).

6. Por defecto, el uso de descuento es ilimitado. Si deseas limitar el uso del descuento, selecciona una de las opciones en la sección **Límites de uso**:

    - **Limitar el número de veces que este descuento se puede usar en total** te permite establecer el número total de veces que se puede usar un descuento. Por ejemplo, establecer un límite de 200 permite que el código de descuento se use 200 veces entre las personas de tu base de clientes. Si eliges esta configuración, los clientes pueden usar el descuento varias veces.
    - El **Límite de uno por cliente** rastrea los correos electrónicos de los clientes para limitar el uso del descuento a uno por cliente.

7. Usa el calendario en la sección **Fechas activas** para establecer la fecha de inicio del descuento. Si deseas establecer una fecha de finalización para el descuento, haz clic en **Configurar fecha de finalización** y usa el calendario para elegir cuándo finalizará el descuento:

    ![Fechas de descuento](/manual/discounts/discount-active-dates.png)

    Si no eliges una fecha de finalización para tu descuento, no tendrá vencimiento. Si deseas que el descuento sea válido solo por un día, selecciona el mismo día calendario para la fecha de inicio y la fecha de finalización.

> Nota: El momento en que el descuento comienza y termina depende de la [zona horaria que seleccionaste en tu panel de control de Shopify](/manual/intro-to-shopify/initial-setup/setup-business-settings/#set-or-change-your-store-timezone). Por ejemplo, si la zona horaria de tu tienda es Hora del este de E.E. U.U. y seleccionas una fecha de inicio el 26 de noviembre, tu descuento comenzará a las 12 a.m. ESTE del 26 de noviembre.

8. Cuando hayas terminado, haz clic en **Guardar descuento**.

Tu nuevo descuento aparecerá ahora en la página [**Descuentos**](//www.shopify.com/admin/discounts) en tu panel de control de Shopify. Para distribuir este descuento, puedes enviar el código a tus clientes por correo electrónico o mostrarlo en tu tienda en línea.

----

{% comment %} Sección IOS {% endcomment %}

1. Desde la [aplicación de Shopify](https://www.shopify.com/install/detect), entra a **Tienda** y luego **Configuración**.

2. Desde la página **Descuentos**, pulsa el botón `+`.

3. En la sección **Código de descuento**, introduce un nombre para el nuevo código de descuento (por ejemplo, `freeshipping4smallorders`). Para generar un código de descuento aleatorio, pulsa **Generar código**:

    ![Nombre del código de descuento envío gratis - iphone](/manual/discounts/discount-name-shipping-iphone.png)

> Nota: Evita el uso de caracteres especiales en los nombres de tus descuentos para que se agreguen correctamente a la URL de la pantalla de pagos de tu tienda.

4. Pulsa **Tipo de descuento** y selecciona **Envío gratis**.

5. Si deseas establecer un requisito mínimo para el descuento, pulsa **Requisitos mínimos** y selecciona un requisito:

    - El **Monto mínimo de compra** requiere que los clientes gasten una cantidad mínima para calificar para el descuento.
    - La **Cantidad mínima de artículos** requiere que los clientes hagan un pedido con un número mínimo de productos para calificar para el descuento.

> Nota: Si el descuento se aplica a un producto o colección específica, solo dichos artículos formarán parte de los montos mínimos de compra o cantidad.

6. Pulsa **Países** y selecciona los países a los que se aplicará este descuento: **Todos los países** o **Países específicos**.

    Para limitar el descuento a países específicos, elige **Países específicos** y pulsa **Agregar** para abrir el selector de país. Selecciona los países para los que deseas que esté disponible el descuento, luego pulsa **Guardar** para guardar tus cambios.

7. Opcional: si deseas excluir el envío gratuito de tarifas de envío a partir de un monto determinado, pulsa **Tarifas de envío** y activa **Excluir tarifas de envío a partir de un monto determinado**. Introduce la tarifa de envío máxima que deseas permitir en el campo **Monto**.

8. Pulsa **Elegibilidad del cliente**, y elige a quién se aplicará este descuento: **Todos**, **Grupos específicos de clientes** o **Clientes específicos**.

    Pulsa **Agregar** y luego selecciona los clientes o grupos de clientes a los que deseas aplicar el descuento. Pulsa **Guardar** para guardar tus cambios.

    Los listados de clientes muestran el correo electrónico que se utilizó para registrarse en tu tienda. Si no se proporcionó un correo electrónico, la lista mostrará el número de teléfono del cliente.

    Para eliminar un cliente individual o un grupo de clientes de la elegibilidad para un descuento, pulsa **Editar** y deselecciona el cliente o grupo de clientes.

    Para leer más acerca de cómo crear grupos de clientes, consulta [_Gestión de clientes_](/manual/customers/manage-customers#create-customer-groups).

9. Por defecto, el uso de descuento es ilimitado. Si deseas limitar el uso de descuento, pulsa **Límites de uso** y activa las opciones de límite de uso que deseas aplicar a tu descuento:

    - **Limitar el número de veces que este descuento se puede usar en total** te permite establecer el número total de veces que se puede usar un descuento. Por ejemplo, establecer un límite de 200 permite que el código de descuento se use 200 veces entre las personas de tu base de clientes. Si eliges esta configuración, los clientes pueden usar el descuento varias veces.
    - El **Límite de uno por cliente** rastrea los correos electrónicos de los clientes para limitar el uso del descuento a uno por cliente.

10. Pulsa **Fechas activas** para establecer la fecha de inicio del descuento. Si deseas establecer una fecha de finalización para el descuento, activa **Establecer fecha de finalización** y usa el calendario de fecha de finalización para elegir cuándo finalizará el descuento:

    ![Fechas activas de descuento - iphone](/manual/discounts/discount-dates-iphone.png)

    Si no eliges una fecha de finalización para tu descuento, no tendrá vencimiento. Si deseas que el descuento sea válido solo por un día, selecciona el mismo día calendario para la fecha de inicio y la fecha de finalización.

> Nota: El momento en que el descuento comienza y termina depende de la [zona horaria que seleccionaste en tu panel de control de Shopify](/manual/intro-to-shopify/initial-setup/setup-business-settings/#set-or-change-your-store-timezone). Por ejemplo, si la zona horaria de tu tienda es Hora del este de E.E. U.U. y seleccionas una fecha de inicio el 26 de noviembre, tu descuento comenzará a las 12 a.m. ESTE del 26 de noviembre.

11. Cuando hayas terminado, pulsa **Guardar**.

Tu nuevo descuento aparecerá ahora en la vista **Descuentos** en **Tienda** en la aplicación Shopify. Para distribuir este descuento, puedes enviar el código a tus clientes por correo electrónico o mostrarlo en tu tienda online. Tus clientes deben introducir el código durante la compra para recibir el descuento.

----

{% comment %} Sección de Android {% endcomment %}

1. Desde la [aplicación de Shopify](https://www.shopify.com/install/detect), entra a **Tienda** y luego **Configuración**.

2. Desde la página **Descuentos**, pulsa el botón `+`.

3. En la sección **Código de descuento**, introduce un nombre para el nuevo código de descuento (por ejemplo, `freeshipping4smallorders`). Para generar un código de descuento aleatorio, pulsa **Generar código**.

    ![Nombre del Código de descuento de envío - android](/manual/discounts/discount-name-free-shipping-android.png)

> Nota: Evita el uso de caracteres especiales en los nombres de tus descuentos para que se agreguen correctamente a la URL de la pantalla de pagos de tu tienda.

4. Pulsa **Tipo de descuento**, luego selecciona **Envío gratis** en el menú desplegable.

5. Pulsa **Países** y selecciona los países a los que se aplicará este descuento: **Todos los países** o **Países específicos**.

    Para limitar el descuento a países seleccionados, selecciona **Países seleccionados** en el menú desplegable. Pulsa `+` al lado de **Países** para abrir el selector de país. Selecciona los países para los que deseas que el descuento esté disponible, luego pulsa ✔ para guardar tus cambios.

6. Opcional: si deseas excluir el envío gratuito de tarifas de envío a partir de un monto determinado, pulsa **Tarifas de envío** y activa **Excluir tarifas de envío a partir de un monto determinado**. Introduce la tarifa de envío máxima que deseas permitir en el campo **Monto**.

7. Si deseas establecer un requisito mínimo para el descuento, pulsa **Requisitos mínimos** y selecciona un requisito:

    - El **Monto mínimo de compra** requiere que los clientes gasten una cantidad mínima para calificar para el descuento.
    - La **Cantidad mínima de artículos** requiere que los clientes hagan un pedido con un número mínimo de productos para calificar para el descuento.

> Nota: Si el descuento se aplica a un producto o colección específica, solo dichos artículos formarán parte de los montos mínimos de compra o cantidad.

8. Pulsa **Elegibilidad del cliente**, y elige a quién se aplicará este descuento: **Todos**, **Grupos específicos de clientes** o **Clientes específicos**.

    Pulsa `+` y luego selecciona los clientes o grupos de clientes a los que deseas aplicar el descuento. Pulsa ✔ para guardar tus cambios.

    Los listados de clientes muestran el correo electrónico que se utilizó para registrarse en tu tienda. Si no se proporcionó un correo electrónico, la lista mostrará el número de teléfono del cliente.

    Para eliminar un cliente individual o un grupo de clientes de la elegibilidad para un descuento, pulsa el ícono de lápiz y deselecciona el cliente o grupo de clientes.

    Para leer más acerca de cómo crear grupos de clientes, consulta [_Gestión de clientes_](/manual/customers/manage-customers#create-customer-groups).

9. Por defecto, el uso de descuento es ilimitado. Si deseas limitar el uso de descuento, pulsa **Límites de uso** y activa las opciones de límite de uso que deseas aplicar a tu descuento:

    - **Limitar el número de veces que este descuento se puede usar en total** te permite establecer el número total de veces que se puede usar un descuento. Por ejemplo, establecer un límite de 200 permite que el código de descuento se use 200 veces entre las personas de tu base de clientes. Si eliges esta configuración, los clientes pueden usar el descuento varias veces.
    - El **Límite de uno por cliente** rastrea los correos electrónicos de los clientes para limitar el uso del descuento a uno por cliente.

10. Pulsa **Fechas activas** para establecer la fecha de inicio del descuento. Si deseas establecer una fecha de finalización para el descuento, activa **Configurar fecha de finalización** y usa el calendario de fecha de finalización para elegir cuándo finalizará el descuento:

    ![Fechas activas de descuento - android](/manual/discounts/discount-active-dates-android.png)

    Si no eliges una fecha de finalización para tu descuento, no tendrá vencimiento. Si deseas que el descuento sea válido solo por un día, selecciona el mismo día calendario para la fecha de inicio y la fecha de finalización.

> Nota: El momento en que el descuento comienza y termina depende de la [zona horaria que seleccionaste en tu panel de control de Shopify](/manual/intro-to-shopify/initial-setup/setup-business-settings/#set-or-change-your-store-timezone). Por ejemplo, si la zona horaria de tu tienda es Hora del este de E.E. U.U. y seleccionas una fecha de inicio el 26 de noviembre, tu descuento comenzará a las 12 a.m. ESTE del 26 de noviembre.

11. Cuando hayas terminado, pulsa ✔.

Tu nuevo descuento aparecerá ahora en la vista **Descuentos** en **Tienda** en la aplicación Shopify. Para distribuir este descuento, puedes enviar el código a tus clientes por correo electrónico o mostrarlo en tu tienda online. Tus clientes deben introducir el código durante la compra para recibir el descuento.

{% endsections %}
