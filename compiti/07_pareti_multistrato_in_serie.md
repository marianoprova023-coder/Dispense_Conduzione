# Dispensa 07 — Pareti Multistrato in Serie e Coefficienti Liminari

## Richiami teorici
Per una parete multistrato in serie tra due fluidi, la resistenza unitaria totale è la somma delle resistenze conduttive e di quelle superficiali (liminari):
$$R\text{'}_{\text{tot}} = \frac{1}{\alpha_{\text{in}}} + \sum_i \frac{L_i}{\lambda_i} + \frac{1}{\alpha_{\text{out}}}$$

## Esercizio
Una parete ha intonaco interno ($L_1 = 1{,}5\ \text{cm}$, $\lambda_1 = 0{,}7\ \text{W/(m}\cdot\text{K)}$), laterizio ($L_2 = 25\ \text{cm}$, $\lambda_2 = 0{,}4\ \text{W/(m}\cdot\text{K)}$) e intonaco esterno ($L_3 = 1{,}5\ \text{cm}$, $\lambda_3 = 0{,}9\ \text{W/(m}\cdot\text{K)}$). Con $\alpha_{\text{in}} = 8\ \text{W/(m}^2\cdot\text{K)}$, $\alpha_{\text{out}} = 25\ \text{W/(m}^2\cdot\text{K)}$, $T_i = 20\,^\circ\text{C}$ e $T_e = 2\,^\circ\text{C}$, calcolare $R\text{'}_{\text{tot}}$ e $\dot{q}$.

### Svolgimento
- $R\text{'}_{s,i} = 0{,}125$, $R\text{'}_1 = 0{,}0214$, $R\text{'}_2 = 0{,}625$, $R\text{'}_3 = 0{,}0167$, $R\text{'}_{s,e} = 0{,}040$
- $R\text{'}_{\text{tot}} = 0{,}828\ \text{m}^2\cdot\text{K/W}$
- $\dot{q} = \frac{20 - 2}{0{,}828} \approx 21{,}7\ \text{W/m}^2$
