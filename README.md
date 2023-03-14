# Active-James-Tonestack
Active James Tonestack with a centre frequency of 4kHz

RO: 
Să se proiecteze şi să se realizeze practic un preamplificator de audiofrecvență cu corecție de ton având 
următoarele caracteristici:
  Tensiunea de alimentare unipolară (VCC = 14 V) sau bipolară (VCC = 14 V, VEE = -VCC = -14V). 
  Semnalizarea prezenței tensiunii cu LED.
  Tensiune de intrare alternativă cu amplitudinea 20mV.
  Banda de frecvență cuprinsă între fj = 400 Hz și fs = 12 kHz.
  Frecvența centrală neutră la corecția de ton N = 4 kHz.
  Corecție de ton de tip BAXANDALL sau echivalentă cu ±14 dB.
  Amplificarea în tensiune la frecvența neutră 100, echivalentă 40 dB.
  Rezistența de ieșire pentru a utiliza rezistența de sarcină a unor căști de 600 Ohmi


Pentru realizarea modulului electronic, luând în considerare cerințele de proiectare, s-a ales un
corector de ton de tip James pentru a realiza corecția de ton. Acesta, spre deosebire de corectorul de ton
clasic Baxandall, are un număr mai redus de componente și nu produce dificultăți la simulările de tip Pspice,
însă desimetrizează răspunsul circuitului la frecvențe înalte (atenuarea apare la frecvențe, în principiu, mai
mari, decât în cazul amplificării). Acest compromis nu afecteaza profund funcția modulului, având în
vedere intervalul de frecvențe de lucru. Din cauza lipsei simetriei acestui interval (frecvența de sus nu este
de 10 ori mai mare decât frecvența neutră, ci doar de N ori, în cazul dat N = 4), atenuarea la frecvențe înalte
se realizează deficitar, rămânând o cerința de proiectare neîndeplinită. 

EN: 

Design and practically build an audio frequency preamplifier with tone correction having
the following features:
   Unipolar (VCC = 14 V) or bipolar (VCC = 14 V, VEE = -VCC = -14V) supply voltage.
   Signaling the presence of voltage with LED.
   Alternating input voltage with an amplitude of 20mV.
   Frequency band between low_freq = 400 Hz and high_freq = 12 kHz.
   Neutral center frequency for the tonestack N = 4 kHz.
   BAXANDALL type tone correction or equivalent with ±14 dB.
   Voltage gain at neutral frequency 100, equivalent to 40 dB.
   Output resistance equal to the load resistance of some 600 Ohm headphones


For the realization of this particular electronic module, while taking into account the design requirements, 
a James tonestack was chosen. This, unlike the Baxandall tonestack, has a smaller number of components and does not cause difficulties 
while simulating its properties in Pspice programs. However, it desymmetrizes the circuit's response at high frequencies 
(attenuation appears at higher frequencies than in the case of boosting). This compromise does not deeply affect the function of the module, 
considering the imposibility of fulfilling every requirement caused by the working frequency range. 
Because of the lack of symmetry of this interval (the upper frequency is not 10 times higher than the neutral frequency,
but only N times, in the given case N = 4), the attenuation at high frequencies performs poorly, leaving this design requirement unfulfilled.
