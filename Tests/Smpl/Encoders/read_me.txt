Poznámky k testování enkoderů a dekoderů:

1) V současnosti není implementován ASCII enkodér, takže není vytvořena ani sada testů
   {%%TODO(Implementovat ASCII encoder)}

2) kodér pro UCS-2 je chybný - kóduje znak v obráceném pořadí bajtů, navíc není implemtovaná
   podpora kódování po změně endiánu, totéž platí pro dekodér UCS-2.

3) pro kodér i dekodér USC-4 není implementovaná podpora kódování resp. dekódování po změně
   endiánu