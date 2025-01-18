# Proiect: Sistem de alarmă cu senzor ultrasonic și buzzer
##Descriere generală
Acest proiect implementează un sistem de alarmă bazat pe un senzor ultrasonic HC-SR04, un buzzer și un LED. Sistemul detectează obiectele aflate în proximitatea sa și activează alarma (buzzer și LED) atunci când acestea se află la o distanță mai mică de 50 cm. Intensitatea și frecvența alarmei cresc pe măsură ce obiectul se apropie.

#Funcționalități
1.Detectarea distanței: Folosește senzorul ultrasonic HC-SR04 pentru a măsura distanța față de un obstacol.

2. Alertare progresivă:
  Buzzer-ul emite semnale sonore cu frecvență ajustată în funcție de distanță.
   LED-ul luminează intermitent mai rapid pe măsură ce obiectul se apropie.
3.Feedback serial: Afișează distanța măsurată în monitorul serial al Arduino IDE.

#Componente necesare
1.Placă Arduino (UNO, Nano sau similar).
2.Senzor ultrasonic HC-SR04.
3.Buzzer activ.
4.LED.
5.Rezistor (220Ω sau 330Ω pentru LED).
6.Breadboard și fire de conexiune.
