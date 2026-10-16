# Cómo contribuir

1. **Hacer un fork** del repositorio (o, si eres colaborador invitado, crear una rama desde `main`: `feature/descripcion-corta` o `fix/descripcion-corta`).
2. Para reportar errores o pedir mejoras sin programar, abre un **Issue**.
3. **Editar `HCI_Sizing_Tool.html`** y probar localmente en Chrome/Edge:
   - sin errores en la consola (F12),
   - el cálculo de ejemplo sigue dando los mismos resultados (salvo que el cambio sea justamente ese),
   - la exportación a Word se abre correctamente,
   - los textos nuevos tienen su traducción al inglés (`L2('es','en')`).
4. **Abrir un pull request** hacia `main` describiendo:
   - qué cambia y por qué (con referencia a la metodología o lista de precios, si aplica),
   - capturas antes/después cuando afecte la interfaz o el Word.
5. El responsable revisa y aprueba. **No se hace push directo a `main`.**

## Reglas
- No subir datos de clientes reales (nombres, cotizaciones, inventarios).
- Mantener el archivo único y autocontenido (sin dependencias externas nuevas).
