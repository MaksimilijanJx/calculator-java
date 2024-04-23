Odradjeno preko cmd i VSCode, instalirani Radeon i kognitivna komplaksnost za racunanje Ciklomatske i Kognitivne slozenosti.
pip install Radon/Cognitive-complexity

Nakon pokretanja komandi:
radon cc -s -a start.java calculator.java
cognitive-complexity start.java calculator.java

Dobijamo sledeci izvestaj o kodovima u folderu:

Ciklomatska složenost za start.java: 2
Kognitivna složenost za start.java: Niska (zbog jednostavnosti strukture koda)

Ciklomatska složenost za calculator.java: 8
Kognitivna složenost za calculator.java: Visoka (zbog složenih algoritama)
