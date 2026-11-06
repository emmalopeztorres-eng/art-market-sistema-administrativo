# ART MARKET — Sistema administrativo

Plataforma de gestión comercial para una tienda de marcadores, materiales de dibujo y productos artísticos.

## Primera versión

- Dashboard administrativo responsive.
- Navegación por módulos.
- Catálogo de productos con alta, edición y eliminación.
- Búsqueda por nombre, SKU, marca y color.
- Filtro por categoría.
- Control visual de stock mínimo y productos sin stock.
- Cálculo del valor del inventario a costo.
- Exportación del catálogo a CSV.
- Persistencia temporal en el navegador mediante localStorage.

> Los datos de ventas que aparecen en el dashboard son ilustrativos. El catálogo inicial contiene productos de ejemplo. Esta versión todavía no está conectada a Supabase ni es multiusuario.

## Tecnología

- React
- Vite
- Lucide React
- CSS responsive

## Desarrollo local

```bash
npm install
npm run dev
```

## Publicación

En Vercel, importar este repositorio y utilizar:
- Framework preset: Vite
- Build command: `npm run build`
- Output directory: `dist`

## Próximas etapas

1. Conectar Supabase y crear autenticación.
2. Persistir productos, marcas, categorías y colores en base de datos.
3. Desarrollar inventario, compras y proveedores.
4. Desarrollar ventas, clientes y finanzas.
5. Conectar tienda online y logística.

