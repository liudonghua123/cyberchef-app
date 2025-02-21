# cyberchef-app

This is cyberchef desktop app, running in an [Tauri](https://tauri.studio/) app.

It support windows (x86, x64, arm64), linux (amd64, i386, arm64, armhf), macos (x64, aarch64, universal) and android (apk, aab in universal). One single portable executable file or bundles/installers (msi/nsis for windows, deb/AppImage/rpm for linux, dmg for macos) are provided.

## Downloads

Current version: 10.19.4.

<table class="is-fullwidth">
</thead>
<tbody>
</tbody>
  <tr>
    <td>
      <img src="./.github/images/windows.png" width="24"><br />
      Windows
    </td>
    <td>
      <span>64-bit</span>
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-windows-10.19.4_x64.exe">
        📦 Executable
      </a> |
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-windows-10.19.4_x64.msi">
        💿 MSI Installer
      </a> |
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-windows-10.19.4_x64-setup.exe">
        💿 NSIS Installer
      </a><br />
      <span>32-bit</span>
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-windows-10.19.4_x86.exe">
        📦 Executable
      </a> |
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-windows-10.19.4_x86.msi">
        💿 MSI Installer
      </a> |
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-windows-10.19.4_x86-setup.exe">
        💿 NSIS Installer
      </a><br />
      <span>arm64</span>
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-windows-10.19.4_arm64.exe">
        📦 Executable
      </a> |
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-windows-10.19.4_arm64_en-US.msi
">
        💿 MSI Installer
      </a> |
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-windows-10.19.4_arm64-setup.exe">
        💿 NSIS Installer
      </a><br />
      <span>
        ❓ Don't know which architecture of OS you installed? Execute <code>wmic os get osarchitecture</code> or Open System by clicking the Start button, right-clicking Computer, and then clicking Properties.
      </span>
    </td>
  </tr>
  <tr>
    <td>
      <img src="./.github/images/macos.png" width="24"><br />
      macOS
    </td>
    <td>
      <span>Intel Processor</span>
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-macos-10.19.4_x64">
        📦 Executable
      </a> |
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-macos-10.19.4_x64.dmg">
        💿 DMG bundle
      </a><br />
      <span>Apple M1 Processor</span>
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-macos-10.19.4_aarch64">
        📦 Executable
      </a> |
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-macos-10.19.4_aarch64.dmg">
        💿 DMG bundle
      </a><br />
      <span><a href="https://developer.apple.com/documentation/apple-silicon/building-a-universal-macos-binary">Universal</a></span>
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-macos-10.19.4_universal">
        📦 Executable
      </a> |
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-macos-10.19.4_universal.dmg">
        💿 DMG bundle
      </a><br />
      <span>
        ❓ Don't know which architecture of OS you installed? Learn more at <a href="https://support.apple.com/en-us/HT211814">apple.com</a>.
      </span><br />
      <br />
      <i>
      While Apple silicon machines can run applications compiled for Intel-based Macs through a translation layer called <a href="https://support.apple.com/en-gb/HT211861">Rosetta</a>, this leads to a reduction in performance due to processor instruction translations. It is common practice to let the user choose the correct target when downloading the app, but you can also choose to distribute a <a href="https://developer.apple.com/documentation/apple-silicon/building-a-universal-macos-binary">Universal Binary</a>. Universal Binaries include both <b>aarch64</b> and <b>x86_64</b> executables, giving you the best experience on both architectures. Note, however, that this increases your bundle size significantly.
      </i>
    </td>
  </tr>
  <tr>
    <td>
      <img src="./.github/images/linux.png" width="24"><br />
      Linux
    </td>
    <td>
      <span>64-bit</span>
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-linux-10.19.4_amd64">
        📦 Executable
      </a> |
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-linux-10.19.4_amd64.AppImage">
        💿 AppImage bundle
      </a> |
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-linux-10.19.4_amd64.deb">
        💿 DEB bundle
      </a> |
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-linux-10.19.4.x86_64.rpm">
        💿 RPM bundle
      </a><br />
      <span>32-bit</span>
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-linux-10.19.4_i386">
        📦 Executable
      </a> |
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-linux-10.19.4_i386.AppImage">
        💿 AppImage bundle
      </a> |
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-linux-10.19.4_i386.deb">
        💿 DEB bundle
      </a> |
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-linux-10.19.4.i386.rpm">
        💿 RPM bundle
      </a><br />
      <span>arm64</span>
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-linux-10.19.4_arm64">
        📦 Executable
      </a> |
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-linux-10.19.4_arm64.deb">
        💿 DEB bundle
      </a> |
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-linux-10.19.4.aarch64.rpm">
        💿 RPM bundle
      </a><br />
      <span>armv7</span>
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-linux-10.19.4_armhf">
        📦 Executable
      </a> |
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-linux-10.19.4_armhf.deb">
        💿 DEB bundle
      </a> |
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-linux-10.19.4.armhfp.rpm">
        💿 RPM bundle
      </a><br />
      <span>
        ❓ Don't know which architecture of OS you installed? Execute <code>uname -i</code> or <code>dpkg --print-architecture</code> or <a href="https://www.man7.org/linux/man-pages/man1/arch.1.html">arch</a> command.
      </span>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="./.github/images/android.png" width="24"><br />
      Android
    </td>
    <td>
      <span>universal</span>
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-android-10.19.4-universal-release-unsigned.apk">
        📦 APK
      </a> |
      <a href="https://github.com/liudonghua123/cyberchef-app/releases/latest/download/cyberchef-app-android-10.19.4-universal-release.aab">
        💿 AAB bundle
      </a><br />
      <span>By default the generated AAB and APK is universal, containing all supported targets.</span>
    </td>
  </tr>
</table>

<hr />

![Screenshot](./.github/images/preview.png)

## Does it work?

Yes! Quite well, actually - on macOS, Windows, and Linux.

## Credits

99% of the work was done over at [cyberchef](https://github.com/gchq/CyberChef).

## License

MIT License

Copyright (c) 2022 liudonghua
