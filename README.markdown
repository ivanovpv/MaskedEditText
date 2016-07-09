# MaskedEditText

*************************************************************************************************
Forked from [toshikurauchi's MaskedEditText](https://github.com/toshikurauchi/MaskedEditText)

Works through declaring in xml layout smth like:

    <br.com.sapereaude.maskedEditText.MaskedEditText 
        android:layout_width="fill_parent"
        android:layout_height="wrap_content"
        mask:mask="ccc.ccc.ccc-cc"
        mask:char_representation="c"
        mask:mask_fill="_"
    />

There's only one difference from original version: `unMask()` - just clears String from applied mask.
