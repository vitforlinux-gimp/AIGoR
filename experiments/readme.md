In questa cartella sono contenuti esperimenti in lingua italiana basati sul codice di AIGoR e text.pollinations.ai, funzionano con Linux se si ha installato yad

AIngA scrive poesie

VanIA scrive storie brevi di vario tipo

SAIge scrive saggi brevi, di circa 1000 / 1500 parole

Usano tutti i motori di AI disponibili in pollinations.ai, lo scopo è vedere se ci sono motori migliori per qualche uso,
ad esempio mi sembra che mistral sia migliore nelle poesie.

Ma non vanno presi seriamente, sono giocattoli. Il codice è ancora molto provvisorio.

Per installare AIngA

```wget -P /tmp https://raw.githubusercontent.com/vitforlinux-gimp/AIGoR/refs/heads/main/experiments/AIngA && chmod +x /tmp/AIngA && sudo mv /tmp/AIngA /usr/local/bin/```

Per installare VanIA

```wget -P /tmp https://raw.githubusercontent.com/vitforlinux-gimp/AIGoR/refs/heads/main/experiments/VanIA && chmod +x /tmp/VanIA && sudo mv /tmp/VanIA /usr/local/bin/```

Per installare SAIge

```wget -P /tmp https://raw.githubusercontent.com/vitforlinux-gimp/AIGoR/refs/heads/main/experiments/SAIge && chmod +x /tmp/SAIge && sudo mv /tmp/SAIge /usr/local/bin/```

I file generati si trovano in ~/nome_programma

La configurazione si trova in ~/.config/nome_programma
