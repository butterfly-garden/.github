# Butterfly Garden

This is where we are growing Butterfly 🦋 A graphical environment created with [Flutter](https://flutter.dev/) and [Dart](https://dart.dev/) for Desktop Linux and *maybe* Android.

At least, that is the vague plan 😄

## Why? 🤔

We want to have fun 🤡 and make something new ✨

We want to try new ideas, learn new skills, make new mistakes and hopefully create a new way to interface with desktop Linux in the process. This is a project by us, for all us, based on the things we like.

**And you are most welcome to join the fun and help make something beautiful** 🦋

## The Plan 🗺

*There is no plan.*

In fact, at the time of writing there is no code just ideas. But we do have an overabundance of optimism, enthusiasm and potential.

What we've discussed so far is this:

 - Have fun, learn new skills, try new things and make new friends.
 - Make a graphical shell using Flutter and Dart. *How hard can it be?* 😜
 - Adhere to [freedesktop.org specifications](https://www.freedesktop.org/wiki/Specifications/).
 - Use the Yaru [theme](https://pub.dev/packages/yaru), [icons](https://pub.dev/packages/yaru_icons) and [widgets](https://pub.dev/packages/yaru_widgets) for visual consistency.
 - Build an operating system based on Ubuntu called Ubuntu Butterfly (*remix*)
 - Collaborate with Flutter developers to bring beautiful cotemporary applications to Butterfly and Ubuntu Butterfly.
 - See if we can get Butterfly running on Android devices too.
 - Try and become an official Ubuntu flavour by the 24.10 release.

## Participate!

Join [Wimpy's World Discord server](https://discord.butterfly-garden.org) where we have a 🦋`#Butterfly` channel for project collaboration.

Before opening an issue, please see the [issue policy](https://github.com/butterfly-garden/.github/blob/main/CONTRIBUTING.md#issue-policy).

A general guide for contributing can be found in [`CONTRIBUTING.md`](CONTRIBUTING.md).

## Technologies 🧑‍💻

While we'd like to implement as much as possible in Flutter and Dart, we need to
be pragmatic as we bootstrap the project and make good use of existing projects.

 - A display manager/greeter, perhaps [`greetd`](https://git.sr.ht/~kennylevinsen/greetd) or [`lightdm`](https://github.com/canonical/lightdm).
   - Maybe a daemon manager such as [`pebble`](https://github.com/canonical/pebble).
 - A Wayland compositor, perhaps [`wayfire`](https://wayfire.org/) or [`Miriway`](https://github.com/Miriway/Miriway).
 - A session manager and settings daemon, perhaps `gnome-session-manager` and `gnome-settings-daemon`.

## Milestones 🪨

We are still figuring things out.

### One

 - Automated builds for development/testing.
 - A terminal emulator implemented using Flutter, [`xterm`](https://pub.dev/packages/xterm) and [Yaru Widgets](https://pub.dev/packages/yaru_widgets).
 - A browser, perhaps `chromium`.

### Two

 - A launcher.
 - **E-v-e-r-y-t-h-i-n-g** else 😁

## License

Butterfly components are typically licensed under the MPL-2.0 with artwork using
CC BY-SA 4.0.
