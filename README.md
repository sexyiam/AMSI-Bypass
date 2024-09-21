WD as of now are detecting anytime if you try to patch AmsiScanBuffer, so it's better to use hooks like VEH, ret, jmp etc...
Used a jmp hook to jump to AMSI_RESULT_CLEAN in both x64 + x32 PS Process.

Used string joining for light obfuscation.

Currently bypasses Windows Defender 10 + 11.

![Imgur Image](https://i.imgur.com/tI2V70G.png)


Indirect Syscall stub from https://github.com/ProcessusT/SharpVenoma
