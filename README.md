# 5.VERIFICATION-OF-NORTON-S-THEOREM

**AIM:**

To verify Norton’s theorem practically and theoretically for the given DC circuit.

**APPARATUS REQUIRED:**

1.	Regulated Power supply ( RPS)	(0-30 V)	1
2.	Voltmeter	(0-30 V) MC	1
3.	Ammeter	( 0 - 10 mA) MC	1
4.	Resistors	470 Ω 560 Ω 1 K Ω	2 1 1
5.	Bread board	---	1
6.	Multimeter	---	1

**THEORY:**

**NORTON’S THEOREM:**

Norton’s theorem states that, ‘a linear two-terminal circuit can be replaced by an equivalent circuit consisting of a current source, IN (=Isc) in parallel with a resistor RN (= RTh), where IN (=Isc) is the short-circuit current through the load terminals and RN is the equivalent resistance at the load terminals when the independent sources are turned off.Norton’s Current, IN or Isc:
It is the short-circuit current through the load terminals. i.e., IN = Isc

Norton’s Resistance, RN:It is the look-back resistance across the load terminals when all the sources are replaced by their internal resistances. An ideal voltage source is replaced by short- circuiting as its internal resistance is zero. An ideal current source is replaced by open- circuiting as its internal resistance is infinity.
 
**CIRCUIT DIAGRAM: VERIFICATION OF NORTON’S THEOREM**

**To measure IL**

<img width="1052" height="351" alt="image" src="https://github.com/user-attachments/assets/59b2ce69-2e87-4c7a-b2f2-16a03feb2cbe" />


**To measure RTh or RN**

<img width="1087" height="398" alt="image" src="https://github.com/user-attachments/assets/5ca2c7b1-811e-40ee-be5e-4901d9118357" />




**To measure IN or Isc**

<img width="1030" height="469" alt="image" src="https://github.com/user-attachments/assets/9589cd1f-80ba-417f-8928-895a4dd22dc5" />

 
**Thevenin’s equivalent circuit**

<img width="764" height="444" alt="image" src="https://github.com/user-attachments/assets/e9be6b88-a0a0-4821-91a2-b0078f0abb97" />



**Norton’s equivalent circuit**

<img width="690" height="453" alt="image" src="https://github.com/user-attachments/assets/2ac2558d-2390-4162-bf09-517e8fcc8ab2" />



**PROCEDURE:**

1.	Make the connections as per the Circuit Diagram:1

2.	Vary the RPS and set an input voltage of 10V.

3.	Note down the voltmeter reading (Vi) and ammeter reading (IL) in Tabular Column 1.

4.	Switch off the supply and make connections for Circuit Diagram 2.

5.	Measure the Thevenin’s resistance RTh= Norton’s resistance RN .

6.	Switch off the supply and make connections for Circuit Diagram:3.

7.	Set an input voltage of 10V in the RPS and note down the voltmeter readings Vi and VTh(=Voc) in Tabular Column:3

8.	Switch off the supply and make connections for Circuit Diagram 4.

9.	Set an input voltage of 10V in the RPS and note down the voltmeter reading Vi and Ammeter reading IN (= Isc) in Tabular Column 4.

10.	Draw the Thevenin’s equivalent circuit and Nortons’s equivalent circuit as shown in circuit diagrams 5 & 6 respectively.

11.	Calculate the IL value using the formula

   	Thevenin’s Theorem IL = VTh/ ( RTh+ R L)

   	Norton’s Theorem IL = IN * RN / ( RN + RL )

12.	Theoretically verify the Norton’s theorem.

**TABULAR COLUMN: 1**
To measure IL

<img width="646" height="286" alt="image" src="https://github.com/user-attachments/assets/e3ae7835-6ca2-4e99-880c-27b15150962e" />




**TABULAR COLUMN:2**

To measure RTh or RN

<img width="678" height="291" alt="image" src="https://github.com/user-attachments/assets/a834c2ef-da99-4574-908f-c3749ec57031" />


**TABULAR COLUMN:3**

To measure IN or Isc

<img width="610" height="340" alt="image" src="https://github.com/user-attachments/assets/3c479756-c2de-49ad-ab8c-d658343bd854" />

	
**MODEL CALCULATION:**

Practical value of IL (from tabulation 1) =2.3mA

**Verification of Norton’s theorem**

IL = IN * RN / ( RN+ RL ) = 2.43mA

Theoretical calculation of IL ,IN and RTh(RN) for the given circuit:

<img width="486" height="595" alt="image" src="https://github.com/user-attachments/assets/1bf72db7-8321-4387-bfa0-c6d82d5739ca" />

 


**RESULT:**

Thus Thevenin’s and Norton’s theorem is verified practically and theoretically.
