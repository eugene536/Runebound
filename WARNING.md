Чтобы корректно комрилилась прога (мы работаем в CLion) нужно большая пачка вещей:
1) компилятор под винду. Я устанавливал minGW через MSYS2
    https://www.freecodecamp.org/news/how-to-install-c-and-cpp-compiler-on-windows/

2) нужно скачать библиотеку SDL. Устанавливаем 2.26.3
    https://github.com/libsdl-org/SDL/releases/tag/release-2.26.3
    https://www.youtube.com/watch?v=SjH_z0x7dWU

    CMakeLists я уже собрал и отладил. Нужно просто создать у себя на компе папку с библиотеками. Предлагаю C:\cpplibs\

3) также нужно скачать дополнение SDL_image
    https://github.com/libsdl-org/SDL/releases/tag/release-2.26.3

Вроде бы всё. Есть вопросы - задавайте в чате