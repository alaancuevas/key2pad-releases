# Política de Seguridad

## Versiones Soportadas

| Versión | Soportada |
|---------|-----------|
| 1.0.x   | ✅ Sí      |

## Verificación de Integridad (Hashes)

Para garantizar que el instalador de Key2Pad no ha sido alterado, publicamos el **Hash SHA-256** de cada archivo `.exe` en las notas de cada release.

Puedes verificar la legitimidad del archivo abriendo una terminal (PowerShell) en la carpeta donde descargaste el instalador y ejecutando:

```powershell
Get-FileHash .\Key2Pad-Setup.exe
```

Compara el resultado con el hash proporcionado en la página de [Releases](https://github.com/alaancuevas/key2pad-releases/releases). Si no coincide, **NO ejecutes el archivo** y repórtalo inmediatamente a nuestro correo de contacto.

## Reportar una Vulnerabilidad

Si encuentras un problema de seguridad en Key2Pad, por favor **NO** abras un issue público.

Contacta directamente a: **key2pad.contact@gmail.com**

Incluye:
- Descripción de la vulnerabilidad.
- Pasos para reproducirla.
- Impacto potencial en la arquitectura del sistema.

Recibirás una respuesta en un plazo de 72 horas.

## Notas sobre ViGEmBus

Key2Pad utiliza el driver virtual Open-Source **ViGEmBus** de Nefarius Software Solutions.  

Actualmente, ViGEmBus se encuentra en estado *End-of-Life* (EOL), lo que significa que su creador ya no proporciona actualizaciones activas. Sin embargo, sigue siendo el driver más estable y funcional en Windows 10/11.
Los problemas de seguridad a nivel kernel o driver relacionados con ViGEmBus escapan a nuestro control directo, pero monitoreamos activamente cualquier parche comunitario, mitigación o fork seguro disponible en:  
https://github.com/nefarius/ViGEmBus
