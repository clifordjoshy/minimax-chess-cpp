# minimax-chess-cpp

A chess AI made using the minimax algorithm with alpha-beta pruning and negamax optimisations.
<ul>
<li>Set to a default search depth of 6 (moves ahead)</li>
<li>Made using the Win32 API in mingw C++</li>
</ul>

Can be compiled using the following instructions:<br>
`windres resource.rc -O coff -o resource.o`<br>
`g++ main.cpp chess.cpp resource.o -mwindows -lgdiplus`
