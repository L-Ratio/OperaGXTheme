# How to use custom background


### To use a custom background do the following

1. First find the image you want and host it online somewhere like imgur.
   * > Example imgur link ``https://i.imgur.com/IMAGENAME.png``

2. Open a text editor to edit the file.
   * > When using a text editor make sure to disable text wrapping!

3. Go to line 21.
   
4. On line 21 replace the var ``var(--opera-gx-bg-1)`` in line 21 with the image you want.

   * > Example ``url(https://raw.githubusercontent.com/L-Ratio/OperaGXTheme/main/Backgrounds/01.jpg)`` or ``url(https://....)``
     * > Instead of it looking like ``--background: var(--opera-gx-bg-1)`` 
       * > It should look like ``--background: url(https://raw.githubusercontent.com/L-Ratio/OperaGXTheme/main/Backgrounds/01.jpg)`` or ``url(https://....)``

5. Save the file.

6. Congratulations if you followed the steps the custom background should work! :smile:
    * > If not using a grayscale image set line 23 AKA `--background-accent-color-1:` to `to 0,0,0,0` or `transparent`
       * > Example ``--background-accent-color-1: transparent``