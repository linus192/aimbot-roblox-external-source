
Requirements:
- Visual Studio 2022
- Windows SDK
- C++17 or newer

You may need to add/replace your own:
- project/framework headers
- math/vector classes
- engine wrappers
- rendering/input implementations

Common required setup:

#include <Windows.h>
#include <thread>
#include <random>
#include <vector>
#include <cmath>
#include <algorithm>

#pragma comment(lib, "winmm.lib")

#ifdef min
#undef min
#endif

#ifdef max
#undef max
#endif

Made by Linus

Telegram: t.me/linus1

Have fun :)
