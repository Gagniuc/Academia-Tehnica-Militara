# Analiza malware

Prefața acestui curs este construită ca un ghid complex dedicat domeniului securității cibernetice și analizei malware, având scopul de a introduce atât fundamentele teoretice, cât și metodologiile practice de investigare, detectare și contracarare a amenințărilor informatice. Materialul este structurat pe module progresive, fiecare abordând o etapă distinctă din ciclul de viață al aplicațiilor malițioase și din arsenalul tehnic al specialiștilor în securitate.

Partea introductivă surprinde istoria și evoluția mașinilor artificiale de uz general, apariția aplicațiilor malware și dezvoltarea soluțiilor de securitate, precum și rolul sistemelor de operare ca strat de portabilitate. Aceste teme stabilesc cadrul conceptual necesar pentru a înțelege modul în care mediul informatic a facilitat atât proliferarea, cât și combaterea codului malițios. Urmează o secțiune dedicată limbajului și codului, unde sunt explicate structura acestuia, entropia și compresia, cuantificarea informației și diversitatea sistemelor de referință.

Capitolele dedicate malware-ului descriu motivațiile din spatele proiectării, clasificările și tipologiile întâlnite (troieni, viermi, viruși), precum și metodele de infectare, de la backdoor și dropper până la mecanisme avansate de polimorfism, metamorfism și ofuscări. Se discută, de asemenea, criptografia și persistența ca elemente esențiale în arsenalul atacatorilor. Mediul de analiză și ingineria inversă sunt introduse prin prezentări despre detonare, instrumente specializate, automatizarea mașinilor virtuale și manipularea mostrelor malware.

<div align="center">
	<a href="https://github.com/Gagniuc/Antivirus-Engines">
	  <kbd>
	    <img src="https://github.com/Gagniuc/ATM/blob/main/img/abstract.png" alt="ATM | MTA">
	  </kbd>
	</a>
</div>

Un segment important al cursului este dedicat executabilelor și arhitecturii de sistem, analizând formatele de fișiere, detectarea bazată pe semnături, diferențele dintre executabile compilate și interpretate, regimurile de compilare și instrucțiunile fundamentale ale procesorului. Tot aici sunt prezentate tehnici de dezasamblare, patching și optimizare, evidențiind utilizarea unor instrumente precum IDA și x64dbg pentru studierea comportamentului executabilelor și a funcțiilor criptografice.

Ulterior, accentul cade pe modificarea executabilelor prin inserție de cod mașină, schimbarea punctului de intrare, manipularea stringurilor și interceptarea execuției în RAM, dar și pe tehnici defensive și ofensive legate de criptare, detecție și exploatare. Analiza comportamentală a malware-ului, realizată prin filtrarea evenimentelor sistemului de operare, inspecția cu honeypot-uri și captarea evenimentelor efemere, completează arsenalul de metode pentru identificarea și înțelegerea atacurilor.

Cursul se încheie cu o privire asupra strategiilor de infecție, de la phishing și droppere până la exploiturile complexe, precum și asupra metodelor de persistență și anihilare a soluțiilor antimalware. Ultimele prezentări oferă o sinteză asupra metodelor de detecție: analiza salturilor în cod, utilizarea semnăturilor, arhitectura motoarelor antivirus și algoritmii fundamentali care susțin securitatea cibernetică modernă.

Prin urmare, aceste materiale formează un curs complet și interdisciplinar, care îmbină informatica teoretică, principiile criptografiei, ingineria inversă și practica securității informatice. Ele oferă nu doar o imagine istorică și conceptuală asupra fenomenului malware, ci și un ghid practic pentru înțelegerea mecanismelor de atac și apărare, constituind o resursă esențială pentru orice specialist sau student interesat de domeniul securității cibernetice.

# Detalii

Aceste prezentări constituie un curs complex de securitate cibernetică și inginerie inversă, structurat progresiv pentru a acoperi atât aspectele teoretice, cât și pe cele practice ale domeniului. Primele capitole (C.1.1-C.1.4) urmăresc istoria și evoluția mașinilor artificiale de uz general, apariția și transformarea aplicațiilor malware, dezvoltarea soluțiilor de securitate și rolul sistemelor de operare ca strat de portabilitate. Ulterior, se intră în detalii legate de structura codului și a limbajului (C.2.1-C.2.4), cu accent pe entropie, compresie, cuantificarea informației și perspectiva diferitelor sisteme de referință. Partea dedicată aplicațiilor malware (C.3.1-C.3.10) analizează limbajele computerizate și motivația proiectării codului malițios, relația acestuia cu sistemele de operare, clasificarea tipurilor de malware și metodele lor de infectare, precum și tehnici precum criptografia, persistența, ofuscarea și exploatările. Se discută detaliat backdoor-urile, dropperele, troienii, viermii și virușii împreună cu ciclurile lor de viață.

Capitolele dedicate mediului de analiză (C.4.1-C.5.4) introduc conceptele de detonare controlată, instrumente de inginerie inversă, automatizarea mașinilor virtuale și lucrul cu mostre malware, inclusiv protocoalele de manipulare. Urmează un set de prezentări orientate pe analiza executabilelor (C.6.1-C.6.6), cu accent pe formatele de fișiere, detectarea bazată pe semnături, diferențele dintre executabile compilate și interpretate, tehnici de ofuscare, identificarea punctului de intrare și arhitectura CPU. În continuare, seria de prezentări dedicate dezasamblării și patchingului (C.7.1-C.7.8) explică procesul de compilare, optimizările compilatorului, encodarea, modificarea executabilelor prin instrucțiuni precum NOP sau JMP, detectarea funcțiilor de criptare și utilizarea IDA pentru analiza codului malware.

<div align="center">
	<a href="https://github.com/Gagniuc/Antivirus-Engines">
	  <kbd>
	    <img src="https://github.com/Gagniuc/Academia-Tehnica-Militara/blob/main/img/echilibru.png" alt="Curs | Securitate">
	  </kbd>
	</a>
</div>

***

Partea practică se aprofundează prin capitolele C.8 și 9, unde sunt descrise tehnici de inserție de cod mașină, modificări de entry point, manipularea stringurilor și a adreselor, dar și metode de dezasamblare, patching și schimbarea mediului de execuție. Următoarele secțiuni (10.1–10.8) tratează optimizările în x32dbg/x64dbg, gestionarea memoriei HEAP și STACK, interceptarea și criptarea datelor în RAM, identificarea parolelor și a centrelor de comandă și control, precum și tehnici de criptare a instrucțiunilor în secțiunea .text. Analiza comportamentală (C.11.1–C.11.4) prezintă filtrarea evenimentelor de sistem, inspecția prin detonare controlată, captarea evenimentelor efemere și utilizarea honeypot-urilor pentru studierea virușilor.

Capitolul dedicat strategiilor de infecție (C.12.1–C.12.4) explorează phishing-ul, dropperele, injecția de cod mașină și exploiturile. Persistența malware-ului și tehnicile de evitare a detecției sunt explicate în C.13, unde apar subiecte precum anihilarea programelor antimalware, DLL hijacking și metode avansate de menținere a controlului asupra sistemului compromis. În final, prezentările despre metodele de detecție (C.14.1–C.14.4) abordează tipurile de salturi și implicațiile lor pentru detectarea malware-ului, semnăturile utilizate de soluțiile antivirus, mecanismele motoarelor antivirus și algoritmii folosiți în securitatea cibernetică modernă. Setul de prezentări construiește o imagine unitară și completă asupra malware-ului, de la origini și clasificări, la metode de analiză, detecție și contracarare, îmbinând teoria informației, principiile criptografiei și tehnicile de inginerie inversă cu practica exploatării și apărării în domeniul securității cibernetice.

<div align="center">
	<a href="https://github.com/Gagniuc/Antivirus-Engines">
	  <kbd>
	    <img src="https://github.com/Gagniuc/ATM/blob/main/img/atm.png" alt="Curs | Securitate">
	  </kbd>
	</a>
</div>
