# TOEFL Trainer (Android)

Entrenador para el TOEFL iBT 2026: Reading, Listening, Writing y Speaking con el formato nuevo, plan diario con metas, vocabulario con repetición espaciada y simulacros.

## Descargar el APK
Cada cambio en `main` compila el APK automáticamente con GitHub Actions y lo publica en **Releases**:
`https://github.com/jheosoriogal/Toelf-trainer/releases/latest`

## Funciones en el teléfono
- Audio de Listening y Speaking con la voz en inglés del teléfono (motor de texto a voz de Google).
- Dictado por voz con el reconocimiento de Android (pide permiso de micrófono la primera vez).
- Recordatorio diario (Plan de hoy › Ajustes).
- Corrección con IA opcional: pega tu clave de API de Anthropic en Plan de hoy › Ajustes. La clave se guarda solo en el teléfono.
- El progreso se guarda en el teléfono; usa Inicio › Datos y respaldo para copiarlo o pasarlo a otro dispositivo.

## Estructura
- `www/index.html`: la app web (la misma del entrenador en Claude).
- `android/`: proyecto Android generado con Capacitor 8.
- `.github/workflows/android.yml`: compilación del APK.

Si el teléfono no tiene voz en inglés: Ajustes › Sistema › Idiomas › Salida de texto a voz › instalar datos de voz en inglés.
