# CSLTTT_KMA

```python
import math




pa1 = 2/13
pa2 = 1 - pa1

pDung = 10/11
pSai  = 1 - pDung


pA1xB1 = (pa1*pDung)/(pa1*pDung + pa2*pSai)
pA2xB2 = (pa2*pDung)/(pa2*pDung + pa1*pSai)
pA1xB2 = (pa1*pSai)/(pa1*pSai + pa2*pDung)
pA2xB1 = (pa2*pSai)/(pa1*pDung + pa2*pSai)



print('I(a1/b1)',(-math.log2(pA1xB1)))
print('I(a2/b2)',(-math.log2(pA2xB2)))
print('I(a1/b2)',(-math.log2(pA1xB2)))
print('I(a2/b1)',(-math.log2(pA2xB1)))
print('\n')
print('I(a1b1)',-math.log2((pa1/pA1xB1)))
print('I(a2b2)',-math.log2((pa2/pA2xB2)))
print('I(a1b2)',-math.log2((pa1/pA1xB2)))
print('I(a2b1)',-math.log2((pa2/pA2xB1)))


pA1B1 = pa1*pDung
pA2B2 = pa2*pDung
pA1B2 = pa1*pSai
pA2B1 = pa2*pSai
print('\n')
print('P(A1/B1)',pA1B1)
print('P(A2/B2)',pA2B2)
print('P(A1/B2)',pA1B2)
print('HP(A2/B1)',pA2B1)
print('\n')
hAxB = -(((pA1B1)*math.log(pDung) + (pA1B2)*math.log(pSai))+((pA2B2)*math.log(pDung) + (pA2B1)*math.log(pSai)))
print('H(A/B)',hAxB)





```

```python



pa1 = 2/13
pa2 = 1 - pa1

pDung = 10/11
pSai  = 1 - pDung


pA1xB1 = (pa1*pDung)/(pa1*pDung + pa2*pSai)
pA2xB2 = (pa2*pDung)/(pa2*pDung + pa1*pSai)
pA1xB2 = (pa1*pSai)/(pa1*pSai + pa2*pDung)
pA2xB1 = (pa2*pSai)/(pa1*pDung + pa2*pSai)



print('I(a1/b1)',(-math.log10(pA1xB1)))
print('I(a2/b2)',(-math.log10(pA2xB2)))
print('I(a1/b2)',(-math.log10(pA1xB2)))
print('I(a2/b1)',(-math.log10(pA2xB1)))
print('\n')
print('I(a1b1)',-math.log10((pa1/pA1xB1)))
print('I(a2b2)',-math.log10((pa2/pA2xB2)))
print('I(a1b2)',-math.log10((pa1/pA1xB2)))
print('I(a2b1)',-math.log10((pa2/pA2xB1)))


pA1B1 = pa1*pDung
pA2B2 = pa2*pDung
pA1B2 = pa1*pSai
pA2B1 = pa2*pSai
print('\n')
print('P(A1/B1)',pA1B1)
print('P(A2/B2)',pA2B2)
print('P(A1/B2)',pA1B2)
print('HP(A2/B1)',pA2B1)
print('\n')
hAxB = -(((pA1B1)*math.log(pDung) + (pA1B2)*math.log(pSai))+((pA2B2)*math.log(pDung) + (pA2B1)*math.log(pSai)))
print('H(A/B)',hAxB)





```

