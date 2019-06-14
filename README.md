# OpenAGT
Open sourced clone of AdventureGameToolkit

There are other similar projects out there with "adventure games" but none come close to what the AGT Devs built-

    Z-Code
    InfoCom
    Gargoyle(??)
    Graphical Novels
    
-But none that I know of with Text-mode-style "custom engines" like AGT did.<br>
THIS WAS NEVER AVAILABLE CROSS-Platform or for Unices. DOS ONLY.

This is a re-implementation. This is not the same work.<br>
MZX and FPC teams have done similar rewrites. MZX is impossible to find.


The original code (improperly) uses Turbo3 Graphics-
    
    Which is wrong
    
-to do text mode ops.

This has to do with color inversion- which is bs. <br>
Set BG to Fg and FG to BG colors. <br>
Or store the inverted values and flip them.

Turbo3 has "some slight variations" to normal GFX ops code.<br>
Sound output is used (lib uos provides the backend thru portaudio) originally- via PC Speaker.

Example:

        *You blow on OBOE* [deep waaaah] - but its too filled with sand to play.


There are plenty of games made for the engine- but as Ive said- the engine needs a rewrite.<br>

So while we need to support a conversion process- or- the ability to read the old format:

    We cannot use it internally.

(much like CHR fonts in BP7)


---


Original Licensing(its very whacky)-

The Original Code is left in a "private contact" and "authors only can make $$$" scenario.

Much like Borland and other projects- but with a few twists:

    Sources ARE available (users are expected to build them)
    Sources were limited to 8-bit DOS ERA (and compiler) limits
    
The sources were released around 1994, IIRC- into the "public domain".<br>

In some places-

    You are only allowed to charge XYZ and NO MORE for this
    
-or-

    You are allowed to distribute (even sources) -- but not modify the code.
    
    
