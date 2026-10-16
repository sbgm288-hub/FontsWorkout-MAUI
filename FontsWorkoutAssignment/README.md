# Fonts Workout — .NET MAUI

Open `First Muai project.slnx` in Visual Studio with the .NET MAUI workload and .NET 10 SDK. Select the Windows target and run.

The first page is `FontsWorkout` and contains:
- `Hello from my first APP` using Open Sans (Google Fonts).
- A Home icon button using MaterialIcons-Regular.ttf (U+E88A).
- Both font families registered in MauiProgram.cs.

Other existing pages are preserved. The original ConsoleApp1 project remains in the repository root.

Verification: Windows build succeeded on 2026-10-16 with zero errors. Existing CS8618 warnings in Models/appuser.cs remain. Android/iOS builds were not verified. The user confirmed the page is displayed.

Generated build output and Visual Studio personal settings are excluded by .gitignore.
