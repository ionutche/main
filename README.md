# FLOW WORKSPACE

Spatiu privat de lucru pentru proiectul FLOW by ICH / FlowAlarm.

## Separarea proiectelor

- `ionutche/main` — spatiul privat de lucru si documentare FLOW.
- `ionutche/ich-studio-site` — site-ul public ICH Studio. Nu modificam acest repository pentru organizarea interna.

## Principii de lucru

1. Nu modificam aplicatia FlowAlarm din acest repository; codul aplicatiei ramane in repository-ul ei dedicat.
2. Diferentiem clar:
   - **De facut**
   - **In lucru**
   - **Construit**
   - **Validat**
3. O sarcina devine **Validata** numai dupa verificare reala si dovezi.
4. FLOW sugereaza si avertizeaza; decizia ramane la utilizator.
5. Nu introducem token-uri, parole sau chei secrete in fisierele publicate in browser.
6. Orice sincronizare intre panoul web si acest repository trebuie implementata printr-un mecanism securizat, fara secrete in frontend.

## Structura planificata

- `workspace/` — panoul vizual de lucru (in curs de proiectare).
- `docs/` — decizii, rapoarte si jurnalul proiectului.
- `data/` — datele sarcinilor si starea lor, dupa stabilirea sincronizarii.

## Stadiu initial

Repository-ul a fost verificat la 18 noiembrie 2026. GitHub a raspuns cu `Git Repository is empty` la incercarea de listare a commit-urilor: nu exista inca istoric de commit-uri.

Nicio aplicatie, pagina publica sau alta ramura de proiect nu a fost modificata.
