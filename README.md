# Futbol Manager App

Una aplicación web open-source para la gestión de equipos de fútbol amateur. Permite crear equipos, registrar eventos (partidos, entrenamientos, etc.), organizar alineaciones y realizar citaciones de jugadores.

## Características

- Gestión de jugadores y equipos
- Creación de eventos con fecha, tipo y equipo asociado
- Alineación libre con arrastrar y soltar (drag & drop)
- Suplentes y titulares configurables
- Citaciones por evento (Citado / No citado, Estado, Asistencia)
- Autenticación con JWT
- Backend en ASP.NET Core + SQLite
- Frontend en Flutter Web

## Tecnologías

- Flutter Web (frontend)
- ASP.NET Core 8 (backend)
- SQLite (base de datos)
- AutoMapper, Entity Framework Core
- Render.com (hosting sugerido)

## Requisitos

- [.NET 8 SDK](https://dotnet.microsoft.com/en-us/download)
- [Flutter SDK (3.19+)](https://docs.flutter.dev/get-started/install)
- Editor recomendado: VS Code o Visual Studio para backend, VS Code para frontend

## Ejecución local

### Backend

```bash
cd FutbolManagerAPI
dotnet run
