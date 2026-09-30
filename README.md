# macoblox-aur

Paquete AUR para [MacOBlox](https://github.com/aubree-lat/MacOBlox) (`macoblox-git`).

Permite ejecutar el cliente nativo de Roblox de macOS en Linux a través de Darling.

## Instalación

Con cualquier asistente de AUR como `paru`:

```bash
paru -S macoblox-git
```

## Sincronización automática

Este repositorio cuenta con un flujo de GitHub Actions que revisa el repositorio upstream cada 6 horas, regenera `.SRCINFO` y actualiza el paquete en AUR automáticamente ante cualquier nuevo commit o ajuste de dependencias.
