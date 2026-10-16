# Fonts Workout — .NET MAUI assignment

The completed MAUI assignment is in [FontsWorkoutAssignment](FontsWorkoutAssignment). The original ConsoleApp1 files are preserved in the root.

## Open in Visual Studio

1. Choose **Code → Download ZIP**, then extract the ZIP (or clone this repository).
2. Open `FontsWorkoutAssignment/First Muai project.slnx` in Visual Studio with .NET 10 SDK and the .NET MAUI workload installed.
3. Choose the Windows target and run. `FontsWorkout` is the first page.

The page contains `Hello from my first APP` using Open Sans from Google Fonts and a Home icon button using Material Icons. Font files are included and registered in MauiProgram.cs.

## Verification

- Original Windows build succeeded on 2026-10-16 with zero errors; existing CS8618 warnings in Models/appuser.cs remain.
- The user confirmed the page displays.
- A GitHub ZIP was downloaded and its 45 project files matched the local project byte-for-byte.
- A fresh build of that downloaded copy was blocked by this verification environment's permissions to the installed SDK directory; no fresh build success is claimed.
- Android/iOS builds have not been verified.
- No bin/obj folders, personal Visual Studio settings, AI conversation logs or detected credential assignments are included in the source package.
