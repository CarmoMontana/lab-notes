---
title: "Nmap — Scan básico e flags úteis"
date: 2025-10-06
tags: [rede, nmap, ferramenta, comandos, nivel-iniciante]
difficulty: "Iniciante"
status: "Feito" # Rascunho / Em Progresso / Feito
---

# Resumo
Breve descrição do que é o Nmap e para que serve.

# Objetivo da nota
Ex.: "Entender as opções -sS, -sV, -O e criar um checklist para reconhecimento inicial."

# Comandos essenciais
- `nmap -sS -Pn -p- <IP>` — TCP SYN scan em todas as portas.
- `nmap -sV -A <IP>` — Detecção de versão + scripts + OS fingerprint.

# Explicação detalhada
(Descrever o que cada flag faz, exemplos práticos e quando usar)

# Exemplo prático
- Alvo: 10.0.0.5
- Resultado: portas 22/tcp (ssh), 80/tcp (http)...
- Comandos usados + saída chave (copiar trechos importantes)

# Observações / Armadilhas
- `-Pn` ignora ping — útil quando o host bloqueia ICMP.
- `-A` é ruidoso e pode disparar IDS.

# Exercícios / Checkpoints
1. Rodar `nmap -sS -p1-65535` em Metasploitable.
2. Comparar resultados com e sem `-Pn`.

# Referências
- link do manual `man nmap`
- tutorial x (cite autor)

# Próximos passos
- Aprender NSE scripts e criar scans automatizados com cron.













