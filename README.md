# valorant-dumper

By using a .dll to inject into the memory process, it allows reading of the memory despite the exception handler. The project also includes a work-in-progress exception that can be raised. As of know, I am unsure whether raising the exception matters. 

Instructions
1. Compile the .dll
2. Disable Vanguard, run Valorant from explorer.exe, inject

BEWARE: The signatures and masks are "as-is". They are not 100% perfect and may need to be updated. 
As well, the .dll can sometimes hang or become very slow. Simply re-run Valorant and re-inject. 

As of now, it can properly dump the main, necessary offsets for Valorant as of 5/22/2022
[https://streamable.com/ibb3w2]

