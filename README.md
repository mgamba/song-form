song-form
=========

A record of song structures, including measure count and lyric reference points

Repo Structure
=========
Each file represents a song.  These are nested within album folders which are nested within artist folders.  All files are ".frm" suffixed.

Internal file format
=========
The files are basically in a csv format.  The first column is the structure identifier.  For example, a song that is hook,verse,hook,bridge,hook would have A B A C A as it's values for the first column.  The second column represents measures.  In general, a measure is two hits of the snare drum (2 and 4 of a 4-beat measure).  An ellipsis either appended to a number or by itself represents the fading out of sound.  The third column is a reference to lyrics at the start of the given section.  Lyrics occur zero or once and are in double-quotes.  After lyrics, there may be musical descriptors in parenthesis, such as (instr.) to represent that the section is instrumental, or (background vocals + ad lib) to represent that the singer is ad libbing over background vocals.  In some cases, primes (') are used to denote that a part of the song is nearly identical to another part, execept for a small change, such as the last chord at the end of an 8-bar sequence.

