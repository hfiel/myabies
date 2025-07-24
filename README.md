# myabies

 **ARCHIVED REPO** MyAbies: acceso al catálogo bibliotecario Abies desde un navegador Web

This is an archived copy with all the code and documentation from my 2009 project *"MyAbies: web access to ABIES library catalog"*.
The documentation is in Spanish, and not a single line has been changed since the original publishing, except to adapt the HTML landing page to the archival process.

**This is absolutely outdated, I do not recommend using it at all.**

I am keeping it here only for historical storage.

My code is bad, I do not even think ABIES is alive (or used) anymore, and I haven't even tested the code or functionality in years (when I made this, it required _Microsoft Access 2003_ to manage the catalog export. I have no idea if it will even open on current Access).

I will not provide any guarantee (or help) at all: **USE IT AT YOUR OWN RISK.**

The original license was a naive _just use it as you want as long it remains free software_, but I am archiving it here under CC-BY-SA-4.0

# What is this?
In the 2000's, _ABIES_ was a software used to manage the book catalog of some public libraries in Spain (think: manage the collections of a _very small_ public school library, providing a simple search by Author, Title, Publisher...). It was a program that stored the information on a _Microsoft Access_ database backend and provided a management/query GUI for the library workers and users under _Microsoft Windows_. However it was 100% local and that made it quite limited for public queries.

So I took an existing (and only partially working) MDB to PHP/MySQL export project, and refactored it (I think this was on PHP... 5?) to fix some errors and make it fully usable (e.g. launching advanced queries by filling several fields at once, managing the MySQL updates...). The final result generated a MySQL dump of the catalog and an associated web interface to launch queries. I know at least one library was using MyAbies for a few years, but I have not maintained or tracked it at all since I made it.
