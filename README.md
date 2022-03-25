# Keylogger (w/ Pynput)

Very simple keylogger. When you run it, a notification will pop up with some quirky statement about the logger starting. Click "ESC" to stop the logging, which then all of the logged data would be pasted into a text file. The text will integrate any backspaces and/or alt+tabs that were taken in, and display what was typed as if it was actually typed into the text file plaintext.



Quirks

- Could never be used maliciously. Windows Defender already has its ID, and any instance of the keylogger would fail unless you purposely tell Defender to kindly f*ck off. The victim would have to be complacent to an extent while you download and override all Defender protections.
- NEW: Starting and ending notifications are now threaded.