- I teoremi di König sono due teoremi che permettono di stabili un sistema di punti materiali una relazione per il momento angolare e l'energia cinetica tra il valore misurato nel sistema di riferimento del centro di massa e quello misurato in un sistema di riferimento inerziale.
- ### I Teorema di König (teorema del momento angolare)
	- #+BEGIN_QUOTE
	  Il primo teorema di König afferma che il momento angolare di un sistema puó essere riscritto nel sistema di riferimento inerziale come il momento angolare dovuto al moto del centro di massa del sistema piú il momento angolare rispetto al sistema di riferimento del centro di massa
	  #+END_QUOTE
	- Per dimostrare questa affermazione prendiamo un sistema di riferimento inerziale e assumiamo come polo l'origine di questo sistema di riferimento. Se andassimo a calcolare il momento angolare rispetto a questo polo avremo:
	- $$L = \sum_{i=0}^N r_i  \times m_i v_i $$
	- Ricordando se andiamo a considerare il sistema di riferimento del centro di massa abbiamo che $$r = r_{CM} + r'$$ e $$v = v_{CM} + v'$$ allora la sommatoria diverrebbe:
	- $$L = \sum_{i=0}^N [(r_{CM} + r')  \times m_i (v_{CM} + v')] $$
	- andando a fare i prodotti avremo:
	- $$L = \sum_{i=0}^N r_{CM}\times m_i v_{CM} + \sum_{i=0}^N r_{CM} \times m_i v'_i +\sum_{i=0}^N  r'_i\times m_i v_{CM}+\sum_{i=0}^N r'_i \times m_i v'_i$$
	- Riorganizzando i termini possiamo scrivere:
	- $$L = r_{CM} \times \sum_{i=0}^N (m_i) v_{CM} + r_{CM} \times \sum_{i=0}^N  (m_i v'_i) +\sum_{i=0}^N  (r'_i m_i) \times v_{CM}+\sum_{i=0}^N (r'_i \times m_i v'_i)$$
	- poiché nel sistema di riferimento del centro di massa si ha che la posizione e la velocitá del centro di massa sono nulle, dal secondo termine abbiamo $$r_{cdm}= \frac {\sum_{i=0}^N (m_i v'_i)}{M} = \vec 0 $$ ed un raggionamento analogo puo essere fatto per il terzo termine.
	- Da questo otteniamo che:
	- $$L= r_{CM} \times \sum_{i=0}^N (m_i) v_{CM} + \sum_{i=0}^N (r'_i \times m_i v'_i)$$
	- Dove il primo termine rappresenta il momento angolare del centro di massa mentre il secondo termine rappresenta il momento angolare del sistema rispetto al centro di massa. In conclusione possiamo scrivere :
	- $$L = L_{CM} + L'$$
- ### II Teorema di König (teorema dell'energia cinetica)
- #+BEGIN_QUOTE
  Il secondo teorema di König afferme che l'energia cinetica di un sistema di punti materiali puó essere espressa come la somma tra l'energia cinetica dovuta al moto del centro di massa e l'energia cinetica del sistema rispetto al sistema del centro di massa
  #+END_QUOTE
- Analogamente a prima per dimostrare questo teorema partiamo dal calcolo dell'energia cinetica rispetto ad una sistema di riferimento inerziale
- $$E_k = \sum_i \frac{1}{2} m_i v_i^2$$
- esprimendo la velocitá rispetto al sistema di riferimento del centro di massa otteniamo:
- $$E_k = \sum_i \frac{1}{2} m_i ( v'_i + v_{CM})^2 = \sum_i \frac{1}{2} m_i (v'_i)^2 + \sum_i \frac{1}{2} m_i  (v_{CM})^2 + \sum_i m_i v'_i \cdot v_{CM}$$
- Da questo possiamo osservare che il primo termina rappresenta l'energia cinetica del sistema rispetto al centro di massa, il secondo termine rappresenta l'energia cinetica del centro di massa mentre l'ultimo termine é nullo dovuto al fatto che rappresenta la velocitá del centro di massa rispetto al sistema di riferimento del centro di massa.
- Infine possiamo quindi affermare che:
- $$E_k = E'_k +E_{k, cdm}$$