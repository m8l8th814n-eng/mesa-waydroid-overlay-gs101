To do this by yourself. You will need
* NDK r30 clang: aarch64-linux-android33-clang (clang 21.0.0, for Android), target API 33. (in /opt/android-ndk/toolchains/llvm/prebuilt/linux-x86_64/bin/)
* the patched mesa with panfrost (https://github.com/m8l8th814n-eng/mesa-gs101)
* your regular clang
* time (two separate mesa builds)

Other supported mali (my precompiled .so files)
* Midgard: T600, T620, T720, T760, T820, T830, T860, T880
* Bifrost: G31, G51, G52, G52 r1, G71, G72, G76
* Valhall: G57, G78 ← din, G610, G310 (v1–v5)
* 5th gen: G720, G725
