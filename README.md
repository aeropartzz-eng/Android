# AI Digital Operator Platform — Android da loja

Painel web em português para operar o Galaxy A21s remotamente via agentes de IA, com aprovação humana para ações sensíveis.

- **Dispositivo:** Samsung Galaxy A21s ("Android da loja") — status atual: aguardando conexão (SSH/ADB ainda não entregue).
- **Agentes:** WhatsApp e Messenger ativos; YouTube e Jogos planejados.
- **Regras de atendimento:** janela de resposta de 3 minutos; checagem a cada 30 minutos; checagem intensiva (1 min por 5 min) após atividade nova.
- **Deploy:** VPS 194.163.134.52, subdomínio **painel.aeropartz.com.br** (DNS A já existe), Caddy + TLS.
- **Responsável pela frente:** Luna (assistente do Will).

## Telas

Visão geral, Agentes, Tarefas, Aprovações, Conversas, Dispositivos, Atividade, Configurações.

## Documentos

- `docs/painel-a21s-deploy.md` — o que instalar no VPS e quem faz o quê.
- `docs/cronograma-a21s.md` — cronograma completo da implantação do A21s (fases 0–7).

## Status

O painel hoje roda hospedado no Muse (artefato `ai-digital-operator-platform`, v5). No VPS ele precisa ser montado/instalado — ver o brief de deploy. O telefone é o passo final: a conexão SSH/ADB do A21s ainda não foi entregue.
