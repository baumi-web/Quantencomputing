# Quantencomputing 6. Semester
Das ist das Abschlussprojekt des Moduls Quantencomputing aus dem 6. Semester.<br>
Die Lösungen sind in einem Jupyter Notebook zusammengefasst. Die Aufgabenstellung ist im PDF [Hausarbeit_Neu](Beispielcode/HausarbeitNeu.pdf) zu finden.<br><br>


> [!NOTE]
> Das originale Vorlesungsskript ist [hier](QC.pdf) zu finden.<br>
## Übersicht der Hausarbeit

Die Hausarbeit behandelt verschiedene grundlegende und fortgeschrittene Konzepte des Quantencomputings. Die Implementierungen wurden mit Qiskit durchgeführt und umfassen folgende Themenschwerpunkte:

* **Aufgabe 1: Quantenregister und Transformationen**
    * Bestimmung einer unitären $8 \times 8$ Matrix $Q = H \otimes X \otimes Z$, die eine Transformation auf einem 3-Qubit Register realisiert.
    * Nachweis der Unitarität der Matrix $Q$.
    * Anwendung der Transformation $Q$ auf die Basiszustände $|000\rangle$ und $|111\rangle$.
    
* **Aufgabe 2: Simulation der Verschränkung (mit Qiskit)**
    * Erstellung eines 2-Qubit Anfangszustands.
    * Implementierung von Hadamard- und CNOT-Gates zur Erzeugung eines Bell-Zustands (Verschränkung).
    * Berechnung des Endzustands (Superposition) und Bestimmung der theoretischen Messwahrscheinlichkeiten.
    * Simulation von Messungen und Nachweis der Wahrscheinlichkeitsverteilung bei unterschiedlicher Anzahl von Messwiederholungen.
 
* **Aufgabe 3: Algorithmus von Deutsch**
    * Entwicklung eines allgemeinen Quantenschaltkreises für den Deutsch-Algorithmus.
    * Konstruktion des Orakel-Operators $U_f$ für alle vier möglichen unären Booleschen Funktionen ($f(0)=0, f(1)=0$; $f(0)=1, f(1)=1$; $f(0)=0, f(1)=1$; $f(0)=1, f(1)=0$).
    * Test und Verifizierung aller vier Fälle mit Qiskit-Simulationen.
      
* **Zusatzaufgabe (optional): Grover-Suchalgorithmus**
    * Implementierung des Grover-Suchalgorithmus für $n=3$ Qubits zur Suche nach dem spezifischen Zustand $|111\rangle$.
    * Entwurf des Quantenorakels $U_f$ (unter Verwendung des CCZ-Gates) und des Diffusionsoperators $U_s$.
    * Simulation und Analyse der Messergebnisse nach 1, 2, 3 und 6 Grover-Iterationen.


## Verwendete Technologien

* Python
* Qiskit
* NumPy
* Matplotlib
* Jupyter Notebook

## Ausführung

Um das Jupyter Notebook auszuführen und die Lösungen nachzuvollziehen, stellen Sie sicher, dass Sie eine Python-Umgebung mit den oben genannten installierten Bibliotheken haben. Öffnen Sie dann das Notebook `Quantum Computing.ipynb` in einer Jupyter-Umgebung.

