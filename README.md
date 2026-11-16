# TVenados — mapa de recuperación

Este GitHub público es únicamente el **mapa de emergencia**. El código privado, la firma Android, la copia de Core y los scripts viven en el Recovery Pack privado de Cloudflare. Los videos viven en la USB/disco.

## Si se pierde la laptop

1. En una laptop Windows nueva inicia sesión en Gmail, Cloudflare, ChatGPT/Codex y GitHub.
2. Abre https://admin.tvenados.uk → **Backup / Restore**.
3. Confirma **LISTO**, **INTEGRIDAD SHA-256 COMPROBADA** y APK **1.5.23**.
4. Descarga **Recovery Pack**; el Backup JSON por sí solo no basta.
5. Extrae el ZIP y abre su raíz en Codex. Lee `AGENTS.md`, `CODEX_SUMMARY.md`, `README_RESTORE.md` y `RECOVERY_MANIFEST.json`.
6. Conecta la USB y restaura `D:\TVenados`. Nunca borres ni reorganices multimedia durante la recuperación.
7. Dile a Codex: “Restaura TVenados siguiendo README_RESTORE.md. No borres media. Verifica Core, Full, túnel, Sagas, 24/7 y APK”.
8. Reautoriza Cloudflare desde la cuenta del propietario.
9. No importes una copia sobre un Core sano: Core/D1 es la autoridad.
10. Termina solo al comprobar localhost, app, admin, core, APK Full y fallback Core.

## Respaldos

- **Backup JSON:** estado operativo de Core.
- **Recovery Pack privado:** estado, fuentes, scripts, documentación, APK y firma Android.
- **USB/disco:** multimedia de `D:\TVenados`.
- **GitHub:** instrucciones públicas para encontrar y usar esas piezas.

Sitios: https://tvenados.uk · https://app.tvenados.uk · https://admin.tvenados.uk · https://core.tvenados.uk

APK estable: **TVenados 1.5.23**, `com.tvenados.app`, versionCode `10572`.

SHA-256: `D61A533CF6EAB612C05CEFC21C3EBBD01217757A83EC704BBA9BC447775C86CD`

La versión 1.5.23 promociona la precarga acotada del carrusel interno de
Sagas desde LAB, sin cambiar el paquete productivo ni la firma Android.

## Seguridad

Nunca publiques aquí el Recovery ZIP, firma Android, tokens, secretos, credenciales, archivos `.env`, datos familiares ni videos.
