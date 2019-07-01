# INSTALLATION
* 1. Install aspell-lang-20071024.tar.bz2 (or later) from http://www.gnu.org/software/aspell in INST-DIR/aspell-lang
* 2. Replace decomp.txt and unicode.txt in INST-DIR/aspell-lang with decomp.txt and unicode.txt contained in this directory
* 3. Copy maps/u-grc.txt in the subdirectory INST-DIR/aspell-lang/maps
* 4. From INST-DIR/aspell-lang execute:
* 5. mkchardata maps/u-grc.txt 
* 6. ./pre grc u-grc
* 7. Replace grc.wl (an empty file) in INST-DIR/aspell-lang/grc with grc.wl contained in this distribution (the 30Mb word list)
* 8. Change directory to INST-DIR/aspell-lang/grc and execute:
* 9. ./proc
* 10. ./configure
* 11. make
* 12. make install

You can select the Ancient Greek Aspell dictionary from emacs from Tools - Spell Checking - Change dictionary - Use new dictionary: grc

Every suggestion or help request is welcome.

N.B. character 2019 (RIGHT SINGLE QUOTATION MARK) is marked as "L" (letter) instead of "-" (non-letter) in the modified unicode.txt file used in this distribution.

Federico Boschetti <federico.boschetti.73@gmail.com>
