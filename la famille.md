# exo1 la famille
1. mkdir cli_tmp
2. touch cli_tmp/je_suis_dans_tmp.txt
3. cd cli_tmp/
4. touch in_cli_tmp.txt
5. mkdir in_cli_tmp
6. rm je_suis_dans_tmp.txt
7. rm -r in_cli_tmp
8. mkdir grand_parent parent grand_frere grande_soeur ami connaissance
9. cd grand_frere/
10. touch bachir.txt
11. mv bachir.txt ../ami
12. cp -r ../ami ../paren
13. rm  ../ami/bachir.txt
14. pwd
15. /Users/hadizatoutchiffa/cli_tmp/grand_frere
16. cd ~
17. rm -r cli_tmp/