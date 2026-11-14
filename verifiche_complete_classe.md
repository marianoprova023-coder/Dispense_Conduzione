# Verifiche Complete di Classe — Trasmissione del Calore e Conduzione

Materiale elaborato a partire dalle dispense del corso (*01_Trasmissione Generalità.pdf* e *02_Conduzione_.pdf*, Prof. Mariano Pierantozzi).

---

## Variante 1 — Livello Base

### Parte I — Quesiti a risposta multipla (2 punti ciascuno)

**1. Nel Postulato di Fourier per la conduzione unidimensionale ($\dot{Q} = -\lambda A \frac{dT}{dx}$), che cosa indica il segno meno?**
- A) Che la conducibilità termica $\lambda$ è una grandezza negativa nei solidi isolanti.
- B) Che la potenza termica scambiata è sempre negativa quando il corpo si raffredda.
- C) Che il flusso termico avviene spontaneamente nel verso opposto al gradiente di temperatura, cioè dalle zone più calde a quelle più fredde.
- D) Che il flusso termico è diretto sempre verso le $x$ negative, indipendentemente da come è orientato l'asse.

**2. Quale delle seguenti affermazioni sulla conducibilità termica ($\lambda$) e sulla diffusività termica ($\alpha = \frac{\lambda}{\rho c_p}$) è corretta?**
- A) Un materiale con bassa conducibilità termica ha necessariamente anche una bassa diffusività termica.
- B) La diffusività termica misura la rapidità con cui le variazioni di temperatura si propagano nel materiale; l'aria, pur avendo bassa conducibilità, ha una diffusività simile a quella del ferro.
- C) La conducibilità termica si misura in $\text{m}^2/\text{s}$, mentre la diffusività termica si misura in $\text{W}/(\text{m}\cdot\text{K})$.
- D) Nei gas la conducibilità termica diminuisce sempre all'aumentare della temperatura.

**3. Nel calcolo della potenza termica scambiata per irraggiamento mediante la legge di Stefan-Boltzmann ($\dot{Q} = \varepsilon \sigma A (T_1^4 - T_2^4)$), quale accortezza è indispensabile adottare?**
- A) Esprimere le temperature $T_1$ e $T_2$ in gradi Celsius, perché le differenze di temperatura sono equivalenti in Celsius e in Kelvin.
- B) Esprimere le temperature $T_1$ e $T_2$ in Kelvin (temperatura assoluta), perché compaiono elevate alla quarta potenza.
- C) Utilizzare $\varepsilon = 1$ per qualsiasi materiale reale, poiché il corpo nero è l'unico modello valido.
- D) Moltiplicare il risultato per il coefficiente di scambio convettivo $h$.

---

### Parte II — Problemi aperti (7 punti ciascuno)

**4. Postulato di Fourier — Parete piana omogenea**
Una parete piana in calcestruzzo ($\lambda = 0{,}80\ \text{W}/(\text{m}\cdot\text{K})$) ha superficie $A = 12\ \text{m}^2$ e spessore $L = 0{,}20\ \text{m}$. In regime stazionario, le due superfici sono mantenute alle temperature costanti $T_1 = 20\,^\circ\text{C}$ e $T_2 = 5\,^\circ\text{C}$. Calcolare:
a) Il flusso termico specifico $\dot{q}$ (in $\text{W/m}^2$).
b) La potenza termica complessiva $\dot{Q}$ che attraversa la parete (in $\text{W}$).
c) L'energia termica totale $Q$ dispersa in $2\text{ ore}$ (in $\text{kWh}$ e in $\text{MJ}$).

**5. Trasmissione del calore — Convezione e irraggiamento**
Una piastra metallica riscaldata di area $A = 0{,}5\ \text{m}^2$ e temperatura superficiale $T_s = 47\,^\circ\text{C}$ è esposta all'aria e alle pareti di una stanza, entrambe a temperatura $T_\infty = T_{\text{amb}} = 20\,^\circ\text{C}$. Sapendo che il coefficiente di scambio termico convettivo è $h = 8\ \text{W}/(\text{m}^2\cdot\text{K})$ e l'emissività della piastra è $\varepsilon = 0{,}90$ ($\sigma = 5{,}67 \cdot 10^{-8}\ \text{W}/(\text{m}^2\cdot\text{K}^4)$), calcolare la potenza termica totale persa dalla piastra ($\dot{Q}_{\text{tot}} = \dot{Q}_{\text{conv}} + \dot{Q}_{\text{irr}}$).

---

## Variante 2 — Livello Intermedio

### Parte I — Quesiti a risposta multipla (2 punti ciascuno)

**1. Confrontando la conducibilità termica di una lega metallica (es. costantana, 55% Cu e 45% Ni) con quella dei metalli puri che la compongono, cosa si osserva a parità di temperatura?**
- A) La conducibilità della lega è esattamente la media aritmetica delle conducibilità dei due metalli puri.
- B) La conducibilità della lega è maggiore di quella di entrambi i metalli puri grazie alla presenza di più tipi di atomi.
- C) La conducibilità della lega è sensibilmente inferiore rispetto al metallo puro di base (e spesso inferiore a entrambi), perché gli atomi estranei introducono disordine reticolare che ostacola elettroni e fononi.
- D) La conducibilità della lega dipende solo dalla densità media e non dalla struttura cristallina.

**2. Quale relazione intercorre tra la resistenza termica totale $R$, la resistenza termica unitaria $R'$ e la trasmittanza termica $U$ di una parete piana?**
- A) $R' = \frac{L}{\lambda}$ si misura in $\text{m}^2\cdot\text{K}/\text{W}$ ed è indipendente dall'area; inoltre $U = \frac{1}{R'_{\text{tot}}}$.
- B) $R = \frac{L}{\lambda A}$ si misura in $\text{m}^2\cdot\text{K}/\text{W}$ ed è indipendente dall'area.
- C) $U = R'_{\text{tot}} \cdot A$, quindi maggiore è la resistenza termica, maggiore è la trasmittanza.
- D) $R$ e $R'$ hanno la stessa unità di misura ($\text{K}/\text{W}$), ma $R'$ si usa solo per i fluidi.

**3. Nel calcolo delle dispersioni termiche attraverso una parete che separa due ambienti (interno ed esterno), perché è fondamentale includere i coefficienti liminari $\alpha_{\text{in}}$ e $\alpha_{\text{out}}$?**
- A) Perché rappresentano la conducibilità termica dell'intonaco interno ed esterno.
- B) Perché tengono conto degli scambi termici superficiali per convezione e irraggiamento; trascurarli porta a sovrastimare notevolmente le dispersioni.
- C) Perché permettono di convertire automaticamente i gradi Celsius in Kelvin.
- D) Perché sostituiscono la resistenza termica dello strato isolante.

---

### Parte II — Problemi aperti (7 punti ciascuno)

**4. Parete multistrato in serie con resistenze superficiali**
Una parete piana di area $A = 10\ \text{m}^2$ separa un ambiente interno a $T_i = 20\,^\circ\text{C}$ ($\alpha_i = 8\ \text{W}/(\text{m}^2\cdot\text{K})$) da un ambiente esterno a $T_e = 0\,^\circ\text{C}$ ($\alpha_e = 25\ \text{W}/(\text{m}^2\cdot\text{K})$). La parete è composta da:
- Strato 1 (intonaco interno): $L_1 = 2\ \text{cm}$, $\lambda_1 = 0{,}70\ \text{W}/(\text{m}\cdot\text{K})$
- Strato 2 (laterizio): $L_2 = 20\ \text{cm}$, $\lambda_2 = 0{,}40\ \text{W}/(\text{m}\cdot\text{K})$
- Strato 3 (isolante EPS): $L_3 = 6\ \text{cm}$, $\lambda_3 = 0{,}037\ \text{W}/(\text{m}\cdot\text{K})$

Calcolare:
a) La resistenza termica unitaria totale $R'_{\text{tot}}$ e la trasmittanza $U$.
b) Il flusso termico specifico $\dot{q}$ e la potenza termica dispersa $\dot{Q}$.
c) La temperatura della superficie interna della parete $T_{s,i}$.

**5. Postulato di Fourier — Parete composta con strato incognito**
Una parete piana in regime stazionario è composta da 3 strati in serie. Sono noti gli spessori $L_1 = 2\ \text{cm}$ e $L_3 = 4\ \text{cm}$ (mentre $L_2$ è incognito) e le conducibilità $\lambda_1 = 0{,}08\ \text{W}/(\text{m}\cdot\text{K})$ e $\lambda_3 = 0{,}16\ \text{W}/(\text{m}\cdot\text{K})$ (mentre $\lambda_2$ è incognito). Le temperature note sono: $T_1 = 28\,^\circ\text{C}$ (faccia esterna del primo strato), $T_{12} = 23\,^\circ\text{C}$ (interfaccia tra strato 1 e 2) e $T_4 = -2\,^\circ\text{C}$ (faccia esterna del terzo strato). Determinare il flusso termico $\dot{q}$ e la temperatura di interfaccia $T_{23}$ tra il secondo e il terzo strato.

---

## Variante 3 — Livello Avanzato

### Parte I — Quesiti a risposta multipla (2 punti ciascuno)

**1. In regime dinamico estivo, qual è il ruolo dell'inerzia termica di una parete opaca?**
- A) Aumenta la trasmittanza stazionaria $U$ per favorire la dispersione del calore interno durante il giorno.
- B) Produce uno smorzamento dell'ampiezza dell'onda termica esterna e uno sfasamento temporale (ottimale intorno alle 10–12 ore), riducendo e ritardando il picco di calore alle ore notturne.
- C) Elimina completamente la necessità di schermare i componenti finestrati.
- D) È determinata esclusivamente dalla conducibilità $\lambda$ dell'isolante, indipendentemente dalla massa frontale della parete.

**2. In un vetrocamera doppio (facce numerate da 1 a 4 dall'esterno verso l'interno), dove conviene posizionare il trattamento basso-emissivo e quale problema introduce il distanziatore?**
- A) In climi freddi si applica sulla faccia 3 per riflettere il calore interno verso l'interno; il distanziatore (specie se metallico) crea un ponte termico perimetrale che riduce l'efficienza energetica della vetrata.
- B) Si applica sempre sulla faccia 1 esterna; il distanziatore migliora l'isolamento perimetrale grazie all'alluminio.
- C) In climi caldi si applica sulla faccia 4 interna; il distanziatore serve solo a evitare la rottura meccanica del vetro.
- D) Il trattamento basso-emissivo aumenta l'emissività $\varepsilon$ del vetro da $0{,}1$ a $0{,}89$ per favorire l'irraggiamento.

**3. Nella formulazione tridimensionale della legge di Fourier per un materiale anisotropo (es. legno), quale affermazione è corretta?**
- A) La conducibilità è descritta da un unico scalare $\lambda$ uguale in tutte le direzioni.
- B) Il flusso termico $\dot{\mathbf{q}}$ è sempre esattamente parallelo e opposto al gradiente di temperatura $\nabla T$.
- C) La conducibilità è rappresentata da un tensore (matrice $3\times 3$) e il vettore flusso termico $\dot{\mathbf{q}}$ non è necessariamente parallelo al gradiente $\nabla T$.
- D) Il legno conduce il calore meglio in direzione trasversale alle fibre rispetto alla direzione parallela alle fibre.

---

### Parte II — Problemi aperti (7 punti ciascuno)

**4. Rete resistiva mista (serie + parallelo)**
Una porzione rappresentativa di parete di area $A_{\text{tot}} = 0{,}25\ \text{m}^2$ (altezza $0{,}25\ \text{m}$, larghezza $1\ \text{m}$) è costituita da:
- Strato 1 (isolante continuo): spessore $L_1 = 0{,}04\ \text{m}$, $\lambda_1 = 0{,}04\ \text{W}/(\text{m}\cdot\text{K})$ esteso su tutta l'area $A_{\text{tot}} = 0{,}25\ \text{m}^2$.
- Strato 2 (elementi in parallelo): mattone ($L_2 = 0{,}16\ \text{m}$, $\lambda_m = 0{,}80\ \text{W}/(\text{m}\cdot\text{K)}$, area $A_m = 0{,}20\ \text{m}^2$) affiancato da un giunto di malta ($L_2 = 0{,}16\ \text{m}$, $\lambda_g = 0{,}20\ \text{W}/(\text{m}\cdot\text{K)}$, area $A_g = 0{,}05\ \text{m}^2$).

Trascurando le resistenze superficiali e assumendo $\Delta T = 20\ \text{K}$ ai capi della porzione di parete, calcolare:
a) La resistenza termica equivalente $R_\parallel$ dello strato in parallelo.
b) La resistenza termica totale $R_{\text{tot}}$ della porzione di parete.
c) La potenza termica $\dot{Q}$ che attraversa la porzione di parete.

**5. Trasmittanza termica di un serramento ($U_w$)**
Un serramento ha area totale $A_T = 2{,}0\ \text{m}^2$, area del vetro $A_V = 1{,}5\ \text{m}^2$ con $U_V = 1{,}4\ \text{W}/(\text{m}^2\cdot\text{K})$, area del telaio $A_{\text{tel}} = 0{,}5\ \text{m}^2$ con $U_{\text{tel}} = 1{,}8\ \text{W}/(\text{m}^2\cdot\text{K})$, perimetro del vetro $l_D = 5{,}0\ \text{m}$ e distanziatore con trasmittanza lineare $\psi_D = 0{,}06\ \text{W}/(\text{m}\cdot\text{K})$.
a) Calcolare la trasmittanza termica complessiva del serramento $U_w$.
b) Calcolare la potenza termica dispersa $\dot{Q}$ con $T_i = 20\,^\circ\text{C}$ e $T_e = 0\,^\circ\text{C}$.

---

## Griglia di Valutazione per il Docente

Ogni variante prevede un punteggio totale massimo di **20 punti** (convertibile in decimi dividendo per 2):
- **Quesiti a risposta multipla**: 3 quesiti $\times$ 2 punti = **6 punti** (0 punti per risposta errata o non data).
- **Problemi aperti**: 2 problemi $\times$ 7 punti = **14 punti**.

### Soluzioni dei quesiti a risposta multipla

| Variante | Quesito 1 | Quesito 2 | Quesito 3 |
| :--- | :---: | :---: | :---: |
| **Variante 1 (Base)** | **C** | **B** | **B** |
| **Variante 2 (Intermedio)** | **C** | **A** | **B** |
| **Variante 3 (Avanzato)** | **B** | **A** | **C** |

---

### Griglia analitica per i problemi aperti

#### Variante 1 — Livello Base
- **Problema 4 (7 punti)**:
  - Calcolo $\Delta T = 20 - 5 = 15\ \text{K}$: **1 pt**
  - Applicazione Legge di Fourier $\dot{q} = \lambda \frac{\Delta T}{L} = 0{,}80 \cdot \frac{15}{0{,}20} = 60\ \text{W/m}^2$ (con unità di misura): **2 pt**
  - Calcolo potenza $\dot{Q} = \dot{q} \cdot A = 60 \cdot 12 = 720\ \text{W}$: **2 pt**
  - Calcolo energia in $2\text{ h}$: $Q = 0{,}72\ \text{kW} \cdot 2\ \text{h} = 1{,}44\ \text{kWh}$ (**1 pt**) e $Q = 720\ \text{W} \cdot 7200\ \text{s} = 5{,}18\ \text{MJ}$ (**1 pt**).
- **Problema 5 (7 punti)**:
  - Calcolo $\dot{Q}_{\text{conv}} = h A (T_s - T_\infty) = 8 \cdot 0{,}5 \cdot (47 - 20) = 108\ \text{W}$: **2 pt**
  - Conversione temperature in Kelvin ($T_s = 320\ \text{K}$, $T_{\text{amb}} = 293\ \text{K}$): **1 pt**
  - Applicazione Stefan-Boltzmann $\dot{Q}_{\text{irr}} = 0{,}90 \cdot 5{,}67\cdot 10^{-8} \cdot 0{,}5 \cdot (320^4 - 293^4) \approx 79{,}5\ \text{W}$: **3 pt**
  - Somma finale $\dot{Q}_{\text{tot}} = 108 + 79{,}5 = 187{,}5\ \text{W}$: **1 pt**

#### Variante 2 — Livello Intermedio
- **Problema 4 (7 punti)**:
  - Resistenze superficiali $R'_{s,i} = 1/8 = 0{,}125$ e $R'_{s,e} = 1/25 = 0{,}040\ \text{m}^2\cdot\text{K/W}$: **1 pt**
  - Resistenze conduttive $R'_1 = 0{,}0286$, $R'_2 = 0{,}5000$, $R'_3 = 1{,}6216\ \text{m}^2\cdot\text{K/W}$: **2 pt**
  - $R'_{\text{tot}} = 2{,}3152\ \text{m}^2\cdot\text{K/W}$ e $U = 1/R'_{\text{tot}} \approx 0{,}432\ \text{W}/(\text{m}^2\cdot\text{K})$: **1,5 pt**
  - Flusso $\dot{q} = 20 / 2{,}3152 \approx 8{,}64\ \text{W/m}^2$ e $\dot{Q} = 86{,}4\ \text{W}$: **1,5 pt**
  - Temperatura superficiale interna $T_{s,i} = 20 - 8{,}64 \cdot 0{,}125 = 18{,}92\,^\circ\text{C}$: **1 pt**
- **Problema 5 (7 punti)**:
  - Riconoscimento che $\dot{q}$ è costante in tutti gli strati in regime stazionario: **1 pt**
  - Calcolo $R'_1 = 0{,}02 / 0{,}08 = 0{,}25\ \text{m}^2\cdot\text{K/W}$: **1,5 pt**
  - Calcolo $\dot{q} = (28 - 23) / 0{,}25 = 20\ \text{W/m}^2$: **1,5 pt**
  - Calcolo $R'_3 = 0{,}04 / 0{,}16 = 0{,}25\ \text{m}^2\cdot\text{K/W}$: **1,5 pt**
  - Calcolo $T_{23} = -2 + 20 \cdot 0{,}25 = 3\,^\circ\text{C}$: **1,5 pt**

#### Variante 3 — Livello Avanzato
- **Problema 4 (7 punti)**:
  - Calcolo $R_1 = \frac{0{,}04}{0{,}04 \cdot 0{,}25} = 4{,}00\ \text{K/W}$: **1,5 pt**
  - Calcolo $R_m = \frac{0{,}16}{0{,}80 \cdot 0{,}20} = 1{,}00\ \text{K/W}$ e $R_g = \frac{0{,}16}{0{,}20 \cdot 0{,}05} = 16{,}00\ \text{K/W}$: **2 pt**
  - Calcolo parallelo $\frac{1}{R_\parallel} = 1 + \frac{1}{16} = 1{,}0625 \Rightarrow R_\parallel \approx 0{,}941\ \text{K/W}$: **1,5 pt**
  - Calcolo $R_{\text{tot}} = 4{,}00 + 0{,}941 = 4{,}941\ \text{K/W}$ e $\dot{Q} = \frac{20}{4{,}941} \approx 4{,}05\ \text{W}$: **2 pt**
- **Problema 5 (7 punti)**:
  - Impostazione corretta della formula $U_w = \frac{A_V U_V + A_{\text{tel}} U_{\text{tel}} + l_D \psi_D}{A_T}$: **2 pt**
  - Sostituzione e calcolo $U_w = \frac{2{,}10 + 0{,}90 + 0{,}30}{2{,}0} = 1{,}65\ \text{W}/(\text{m}^2\cdot\text{K})$: **3 pt**
  - Calcolo $\dot{Q} = U_w \cdot A_T \cdot \Delta T = 1{,}65 \cdot 2{,}0 \cdot 20 = 66\ \text{W}$: **2 pt**

---

### Errori più comuni commessi dagli studenti

1. **Temperature in Celsius nella legge di Stefan-Boltzmann**: molti studenti inseriscono direttamente $T_1^4 - T_2^4$ in $^\circ\text{C}$ invece di convertire in Kelvin ($T(\text{K}) = T(^\circ\text{C}) + 273$). L'errore è grave perché $(47^4 - 20^4) \neq (320^4 - 293^4)$.
2. **Confusione tra flusso termico $\dot{q}$ ($\text{W/m}^2$) e potenza termica $\dot{Q}$ ($\text{W}$)**: dimenticare di moltiplicare (o dividere) per l'area $A$, oppure mescolare $R = \frac{L}{\lambda A}$ ($\text{K/W}$) con $R' = \frac{L}{\lambda}$ ($\text{m}^2\cdot\text{K/W}$).
3. **Mancata conversione degli spessori da $\text{cm}$ a $\text{m}$**: usare $L = 2\ \text{cm}$ invece di $0{,}02\ \text{m}$ nella formula $R' = L/\lambda$, ottenendo resistenze 100 volte più grandi.
4. **Dimenticanza dei coefficienti liminari**: calcolare $R'_{\text{tot}}$ sommando solo gli strati solidi e omettendo $R'_{s,i} = 1/\alpha_i$ e $R'_{s,e} = 1/\alpha_e$.
5. **Resistenze in parallelo**: sommare direttamente $R_m + R_g$ invece di sommare i reciproci ($\frac{1}{R_\parallel} = \frac{1}{R_m} + \frac{1}{R_g}$), oppure usare $R'$ invece di $R$ (senza tenere conto delle diverse aree $A_m$ e $A_g$ dei rami in parallelo).
6. **Energia vs Potenza**: confondere $\text{kW}$ con $\text{kWh}$ o dimenticare di convertire le ore in secondi ($1\ \text{h} = 3600\ \text{s}$) nel calcolo dell'energia in Joule.
