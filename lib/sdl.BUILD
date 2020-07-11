package(
  default_visibility= ["//visibility:public"],
)

cc_library(
  name = "sdl",
  srcs = glob(
    include = [
      "src/**/*.c",
      "src/**/*.h",
    ],
    exclude = [
      "src/haptic/windows/**",
      "src/locale/android/**",
      "src/locale/dummy/**",
      "src/locale/emscripten/**",
      "src/locale/haiku/**",
      "src/locale/macosx/**",
      "src/locale/windows/**",
      "src/locale/winrt/**",
      "src/video/qnx/**",
      "src/core/linux/SDL_fcitx.c",
    ],
  ),
  hdrs = glob(["include/*.h"]),
  includes = ["include"],
)
