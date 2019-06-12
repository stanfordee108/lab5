# lab5 FAQ

Q: I’m seeing two small dots in my waveform, above y = 0, centered around amplitude peaks. Is this something I need to fix?
    
A: No, this is acceptable.
    
Q: I’m seeing a vertical line in my waveform - is this something I need to fix?
    
A: Yes. This is usually a common bug where the bounds of the pixel rectangle to fill in are set by comparing the current RAM y-value (correctly placed at the positive zero crossing), and a previous y-value that is no longer relevant (usually from the other end of the wave). This is something you should figure out how to fix.
    
Q: Do we or don’t we require a flat, DC line in the waveform when no note is playing?
    
A: The lab spec doesn’t explicitly require a flat line, so either is fine.
     
Q: I’m getting the same timing violation in the Codec from lab4. Do we need to fix this?
    
A: Still no!
