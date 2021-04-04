This is a dirty hack for GNU Binutils from homebrew running on MacosX with
an M1 CPU.

AR, ranlib and strip are broken in that distribution. Thanksfully,
Macos/Xcode command line tools include suitable commands for these
functions. These are simply shell scripts that wrap the native macos
commands.

They are dumb and dirty. They haven't been tested for all or even any edge
cases. They work well enough for me to build cross compiling toolchains.
That's all I was after.

Your mileage may vary. Don't call me if your compiler generates garbage,
your computer catches on fire or your cat runs away.
