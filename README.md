Strojovy-preklad-DP

Súbor Predspracovanie_dat_Trenovanie.ipynb obsahuje:

  1. Predspracovanie dát do vhodnej formy
  2. Tokenizácia pomocou SentencePiece
  3. Rozdelenie dát do Trénovacej, testovacej a development (validačnej) množiny
  4. Vytvorenie config súboru pre trénovanie
  5. Trénovanie pomocou OpenNMT na základe vytvoreného configu
  6. Súbory tokenizované pomocou SentencePiece je následne nutné desubwordovať (konkrétne target model (SK jazyk), target testovací súbor (SK jazyk) ktorý bude slúžiť ako referencia a prekladový súbor (SK jazyk))
  7. Evalvácia na základe metrík BLEU a METEOR

Poznámka: v čase prvého uploadu do tohto repozitu som už vykonal 14 rôznych ÚSPEŠNÝCH trénovaní. Prvotné riešenia predtým boli len plné unk tokenov.

porovnanie.xlsx obsahuje informácie ohľadom jednotlivých model resp. ich BLEU a METEOR skóre a nastavenia niektorých hyperparametrov
