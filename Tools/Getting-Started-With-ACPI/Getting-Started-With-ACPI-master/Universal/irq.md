# Fixing IRQ Conflicts (SSDT-HPET + OC_Patches.plist)

So you miss having those fancy hot-patches from Clover like FixIPIC, FixTMR, FixRTC, FixHPET, etc

Well 1 very small problem, figuring out IRQ patching is a massive headache. **I highly recommend you use SSDTTime**. So head over to [SSDT: Easy Way](/ssdt-methods/ssdt-easy.md) on how to make it.(use option `C` to omit conflicting legacy IRQs)
