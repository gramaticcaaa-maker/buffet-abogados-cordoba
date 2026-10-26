# Buffer Abogados Córdoba

Sitio estático HTML/CSS/JavaScript listo para importar en Vercel.

## Antes de publicar en producción
- Revisar el texto de demostración: actualmente la web dice “Rivas & Salinas” y menciona Monterrey, Nuevo León.
- Sustituir los nombres, cédulas profesionales, dirección, teléfono, correo, horarios y cifras ficticias por datos reales.
- Revisar el número de WhatsApp configurado en `index.html` (variable `WA`).
- Confirmar que el aviso de privacidad sea el correcto para el despacho y su jurisdicción.

## Publicar
1. Subí `index.html`, `vercel.json` y este README a la raíz del repositorio `buffer-abogados-cordoba`.
2. En Vercel, elegí **Add New → Project** y conectá GitHub.
3. Importá `gramaticcaaa-maker/buffer-abogados-cordoba`.
4. Como es HTML estático, no hace falta comando de build; dejá el directorio raíz en `./` y desplegá.
5. En Vercel, la rama de producción (normalmente `main`) quedará conectada para despliegues automáticos con cada push.
