Egglist is a wordlist generator written in C++ that can generate wordlists quickly and with a lot of customization.

I wrote this application during a security class I was taking when I couldn't find a wordlist generator that was flexible
enough to meet my needs. I originally wrote this utility in Java but when I found that it used a ton of memory, I rewrote 
it in C++ using only the standard libraries for maximum portability. It has a small memory footprint and is blazing fast.

Output can also be piped directly into other tools such as Hydra or John to eliminate the need to save massive wordlists
on disk.
