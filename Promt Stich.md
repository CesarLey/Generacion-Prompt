Te comparto el sistema de diseño para generar una aplicación móvil, de momento analiza la información y guardala en tu memoria para la construcción de las interfaces que te voy a solicitar: 

---

La información proporcionada es esencial para definir la arquitectura de diseño con precisión y cumplir con los requisitos de **alta fidelidad** [Query, 382] y el **Javerage Electoral Design System (JEDS)** [Query, 385, 491].

Hemos confirmado tres puntos clave que ahora se integran en el *prompt* final:

1. **Fidelidad y Tema:** Se prioriza un prototipo de **Alta Fidelidad** bajo el **Tema Oscuro** [Query].
2. **Logo:** El **Logo de Javerage Electoral** debe ser prominente en el encabezado para fidelizar la marca [Query].
3. **Componente "Recordarme":** Se utilizará un **Toggle Switch** (interruptor deslizante) [Query] posicionado debajo del campo de contraseña, alineado con las mejores prácticas de UI móvil.

A continuación, se presenta la descripción de la UI en un solo párrafo y el *prompt* estructurado con el detalle final de los componentes.

---

### Descripción de la UI (Párrafo Único)

La pantalla de autenticación será un **prototipo de alta fidelidad** adherido estrictamente al **Tema Oscuro** de JEDS [Query, 390], diseñado bajo principios de **minimalismo digital** para garantizar seguridad, claridad y reducir la carga cognitiva. El diseño priorizará el formato *mobile-first*, comenzando con la visualización del **logotipo de la marca** en el encabezado para el reconocimiento y fidelización [Query]. El contenido se centrará en la autenticación, presentando un título de bienvenida y dos campos de entrada delineados (`textField.outlined`) para el Usuario (correo electrónico o ID) y la Contraseña [Query, 493]. Inmediatamente debajo del campo de contraseña, se incluirá el **Toggle Switch** para la función "Recordarme", alineado con los controles del formulario para una interacción eficiente y cumpliendo con el tamaño de objetivo táctil mínimo de **48x48dp**. La acción de acceso se finalizará con un **botón principal de relleno** (`button.filled`) con forma de píldora (`shape.corner.full`), ubicado cerca del borde inferior para facilitar el alcance táctil, y un enlace de soporte para la recuperación de la cuenta [Query, 493].