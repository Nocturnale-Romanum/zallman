# zallman
Forked version of the Zallman Caps with AE ligature, specifically for NR

Here is the way I installed it on nocturnale.marteo.fr :

put ZallmanCaps.afm, ZallmanCaps.ttf and ZallmanCaps.pfb in some folder and cd into it.

```sh
find / | grep Zallman
  /usr/local/share/fonts/ZallmanCaps.TTF
  /usr/share/doc/texlive-doc/fonts/initials/Zallman.tex
  /usr/share/texlive/texmf-dist/tex/latex/cfr-initials/Zallman.sty
  /usr/share/texlive/texmf-dist/tex/latex/initials/Zallman.fd
  /usr/share/texlive/texmf-dist/fonts/map/dvips/initials/Zallman.map
  /usr/share/texlive/texmf-dist/fonts/afm/public/initials/Zallman.afm
  /usr/share/texlive/texmf-dist/fonts/tfm/public/initials/Zallman.tfm
  /usr/share/texlive/texmf-dist/fonts/type1/public/initials/Zallman.pfb
  /usr/share/texlive/texmf-dist/dvips/initials/config.Zallman
mv /usr/share/texlive/texmf-dist/fonts/afm/public/initials/Zallman.afm /usr/share/texlive/texmf-dist/fonts/afm/public/initials/Zallman.afm.restoreme
mv ZallmanCaps.afm /usr/share/texlive/texmf-dist/fonts/afm/public/initials/Zallman.afm
mv /usr/share/texlive/texmf-dist/fonts/type1/public/initials/Zallman.pfb /usr/share/texlive/texmf-dist/fonts/type1/public/initials/Zallman.pfb.restoreme
mv ZallmanCaps.pfb /usr/share/texlive/texmf-dist/fonts/type1/public/initials/Zallman.pfb
mv /usr/local/share/fonts/ZallmanCaps.TTF /usr/local/share/fonts/ZallmanCaps.TTF.restoreme
mv ZallmanCaps.ttf /usr/local/share/fonts/ZallmanCaps.TTF
```
