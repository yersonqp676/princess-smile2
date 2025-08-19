# 👑 Princess Smile - Tienda Online

Bienvenido a **Princess Smile**, tu tienda online de ropa femenina en Perú.
Este proyecto incluye:
- 🛍️ Catálogo con productos (polo, vestidos, casacas, etc.)
- 🛒 Carrito de compras con descuentos automáticos
- 💸 Métodos de pago: Yape, Plin, BCP
- 📲 Integración con WhatsApp para confirmar pedidos y enviar comprobantes
- 📱 Diseño responsive (celular, tablet, laptop, PC)

---

## 🚀 Instrucciones de uso

### 1. Subir a GitHub
1. Crea un repositorio en GitHub (ejemplo: `princess-smile`).
2. Descarga este ZIP y descomprímelo en tu PC.
3. Copia todos los archivos dentro de la carpeta del repositorio.
4. Haz commit y push a GitHub.

```bash
git init
git add .
git commit -m "Versión inicial Princess Smile"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/princess-smile.git
git push -u origin main
```

---

### 2. Publicar en Netlify
1. Entra a [Netlify](https://www.netlify.com/).
2. Conecta tu cuenta de GitHub.
3. Selecciona tu repositorio `princess-smile`.
4. Haz deploy (Netlify lo subirá automáticamente).

---

### 3. Personalización
- Edita `catalogo.html` para agregar o quitar productos.
- Modifica `carrito.js` para ajustar descuentos o métodos de pago.
- Cambia las imágenes en `/assets/img/`.

---

### 4. Flujo de compra
1. El cliente agrega productos al carrito.
2. Se calculan descuentos automáticos según la cantidad:
   - 1–2 unidades → precio normal
   - 3–5 unidades → -1 sol por prenda
   - 6–11 unidades → -2 soles por prenda
   - 12+ unidades → -3 soles por prenda
3. El cliente confirma en WhatsApp → recibe boleta y da captura de pago.

---

👑 Desarrollado para **Princess Smile**  
📍 Perú, 2025
