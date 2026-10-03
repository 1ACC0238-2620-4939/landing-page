# Trakto Route Landing Page

Landing page pública de Trakto Route, una aplicación móvil para gestionar y seguir viajes de transporte de carga.

## Ejecutar localmente

No requiere compilación ni dependencias. Puede abrirse `index.html` directamente o servirse con cualquier servidor HTTP estático.

```powershell
python -m http.server 8080
```

## Validación rápida

```powershell
$links = Select-String -Path index.html -Pattern 'href="#repositorio"'
if ($links) { throw 'Quedan enlaces de repositorio sin configurar.' }
```

## Repositorios relacionados

- [Aplicación móvil](https://github.com/1ACC0238-2620-4939/mobile-app)
- [Backend](https://github.com/1ACC0238-2620-4939/backend)
- [Informe](https://github.com/1ACC0238-2620-4939/Report)
