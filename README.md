# Shortcuts for Indic transliteration

Extension to MacOS Press-and-hold keyboard shortcuts for accented letters

This .plist adds IAST and ISO 15919 characters to the press-and-hold keyboard popups on MacOS:

     Ǣǣ Ḍḍ Ḏḏ Đđ Ḑḑ Ġġ Ḥḥ H̱ẖ Ḫḫ Ḵḵ Ḷḷ Ḹḹ L̥l̥ L̥̄l̥̄ Ḻḻ Ṃṃ M̊m̊ M̐m̐ M̆m̆ Ṇṇ Ṉṉ N̆n̆ Ṛṛ Ṝṝ R̥r̥ R̥̄r̥̄ Ṟṟ R̆r̆ Ṣṣ Şş Ṭṭ Ṯṯ Ţţ Ŭŭ Ẏẏ Ẓẓ

Copy the Keyboard-en.plist file into 

    /System/Library/Input Methods/PressAndHold.app/Contents/PlugIns/PAH_Extension.appex/Contents/Resources/

If System Integrity Protection (SIP) prevents writing to this folder, you can disable it as follows:

    Restart your Mac and hold down Cmd-R to open Utilities on startup.
    From the Utilities menu, choose terminal
    Type 'csrutil disable' and press return
    Restart your Mac
    
Don't forget to enable SIP again afterwards by typing 'csrutil enable' in the same way.
    
Note Ḹ ḹ Ṃ ṃ M̐ m̐ Ṝ ṝ may not appear correctly in all fonts.
