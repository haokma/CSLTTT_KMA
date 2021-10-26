# CSLTTT_KMA

```python
import math

pa1 = 0.25
pa2 = 1 - pa1

pDung = 0.75
pSai  = 1 - pDung

pA1B1 = (pa1*pDung)/(pa1*pDung + pa2*pSai)
pA2B2 = (pa2*pDung)/(pa2*pDung + pa1*pSai)
pA1B2 = (pa1*pSai)/(pa1*pSai + pa2*pDung)
pA2B1 = (pa2*pSai)/(pa1*pDung + pa2*pSai)


print('I(a1/b1)',(-math.log10(pA1B1)))
print('I(a2/b2)',(-math.log10(pA2B2)))
print('I(a1/b2)',(-math.log10(pA1B2)))
print('I(a2/b1)',(-math.log10(pA2B1)))
print('\n')
print('I(a1b1)',-math.log10((pa1/pDung)))
print('I(a2b2)',-math.log10((pa2/pDung)))
print('I(a1b2)',-math.log10((pa1/pSai)))
print('I(a2b1)',-math.log10((pa2/pSai)))



```

