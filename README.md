# Bitmap Font Localizer

My fork of BitmapFontEditor of RetroNick2020, focused on adding new alphabets to existing fonts.

Check original repo for detailed description of basic version.



Improvements in this fork: 

- Extended Charset/Encoding support; Correct preview for non-default encoding.

- Correctly write selected encoding data when saving.

- Character list now split into two columns, with latin on the left and additional characters on the right.

Minor fixes for original:

- Load correct copyright metadata back when loading previously saved font.

- Longer length limit for font name and copyright.

- Saving rewrites previously saved file by correct name, added separate "Save As" button.

- Better preview field with multiline support and option to hide red baseline.

Future plans:

- Support for Unicode and BDF file format.

<img width="1059" height="799" alt="image" src="https://github.com/user-attachments/assets/6ac46b56-7068-446f-83d6-a516f9d9abf5" />

---

**Note:** This is the first time I see Pascal code in, like, 15 years. So i should admit, 100% of code lines in this fork are written by AI. However, I've added these edits in small chunks, checking and reviewing every single edit, so I can (in limits of my knowledge of Pascal) validate that there are no AI hallucinations or *very* unoptimal solutions in the code.
I see no problems in this, as this is small personal project of upgrading a tool I found convenient for my own working pipeline. But I think it's fair to warn anyone whom this may concern.

