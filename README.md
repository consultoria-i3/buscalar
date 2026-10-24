# Buscalar · Galletas de la R

Sitio estático (un solo `index.html`) para Vercel. La sala en vivo usa Supabase (proyecto `sobrecompartir`,
tablas `buscalar_*`): el docente proyecta, los estudiantes entran con el código o el QR y votan desde el celular.

## Publicar en Vercel
1. Importar este repositorio en Vercel (Add New → Project). Framework: Other. Sin comando de build.
2. Settings → Domains → agregar `buscalar.relacion.at`.
3. En GoDaddy (DNS de relacion.at) crear el registro CNAME que Vercel indique para `buscalar`.

## Publicación
Conectado a Vercel (proyecto `buscalar-vercel`): cada push a `main` se despliega en https://buscalar.relacion.at
