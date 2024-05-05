---------------------

```C
#include <stdlib.h>

int wmain(void) {
    static const wchar_t* const languages[]  = { L"C", L"C++", L"x86-64", L"Python" };
    static const wchar_t* const tools[] = { L"Visual Studio", L"Visual Studio Code", L"LLVM", L"MSYS2 UCRT64", L"NVIDIA CUDA",
                                         L"Windows SDK", L"WDK", L"WinDbg" };
    return EXIT_SUCCESS;
}
```
----------------------
