# SierraMar

App de gestión de bares (Flutter + Firebase).

## Descarga

Última APK Android: [Releases](https://github.com/NatxoGalan/SierraMar/releases/latest)

- Entra en la última release y descarga el archivo `SierraMar-vX.Y.Z.apk`.
- Nota: la APK está firmada con claves de depuración; al instalar, permite la instalación desde "orígenes desconocidos".

## Desarrollo

```bash
flutter pub get
flutter run
```

## Build

```bash
flutter build apk --release   # APK: build/app/outputs/flutter-apk/app-release.apk
flutter build web --release   # Web: build/web (Vercel sirve esta carpeta)
```

## Nuevas versiones

1. Sube la versión en `pubspec.yaml`.
2. Commitea y crea el tag:

```bash
git tag vX.Y.Z
git push origin vX.Y.Z
```

El workflow `Release APK` compila la APK y la adjunta automáticamente a la release.
