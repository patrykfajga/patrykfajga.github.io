---
title: "FlyMind"
date: 2026-11-20
---


FlyMind to eksperymentalny projekt łączący dane z connectomu mózgu muchy z modelem podejmowania decyzji. Punktem wyjścia jest pytanie, czy zapis struktury i aktywności mózgu może stać się podstawą modelu, który nie tylko odtwarza połączenia, ale także uczy się reagować na zmieniające się warunki.


Projekt wykorzystuje dane BANC uzyskane z obrazów EM. Zostały one uporządkowane między innymi w formatach Feather/Parquet i SWC, a przebieg eksperymentów może być zapisywany jako replay w JSON. W wizualizacji FlyMind Lab model działa w środowisku 3D: obserwuje sygnał A albo B, uwzględnia pamięć wartości, kontekst i zagrożenie, po czym wybiera „Aplikuj” albo „Odrzuć”. Otrzymany wynik aktualizuje wartości przypisane do obu opcji.


W prezentacji pokazano również porównanie wariantów modelu. Wariant Functional odrzucał ryzykowną ofertę w 79,2% przypadków, model z przetasowanymi połączeniami w 85,0%, model z uproszczoną pamięcią w 71,8%, a wariant bez central complex w 77,2%. Po wyłączeniu modułu emergency wynik spadł do 18,2%, co wskazuje na jego znaczenie dla zachowania modelu.
