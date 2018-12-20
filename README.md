# IAST-shortcuts
Extension to MacOS Press-and-hold keyboard shortcuts for accented letters

This .plist adds the IAST characters Ḍ ḍ Ḥ ḥ Ḷ ḷ Ḹ ḹ Ṃ ṃ Ṇ ṇ Ṛ ṛ Ṝ ṝ Ṣ ṣ Ṭ ṭ to the press-and-hold keyboard popups on MacOS.

Copy the Keyboard-en.plist file into 

/System/Library/Input Methods/PressAndHold.app/Contents/PlugIns/PAH_Extension.appex/Contents/Resources/

If System Integrity Protection (SIP) prevents writing to this folder, you can disable it as follows:

    Restart your Mac and hold down Cmd-R to open Utilities on startup.
    From the Utilities menu, choose terminal
    Type 'csrutil disable' and press return
    Restart your Mac
    
Don't forget to enable SIP again afterwards by typing 'csrutil enable' in the same way.
    
Note Ḹ ḹ Ṃ ṃ Ṝ ṝ may not appear correctly in all fonts.
