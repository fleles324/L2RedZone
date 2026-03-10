# L2RedZone - Pro Edition

O **L2RedZone** é uma ferramenta avançada de automação para Lineage II, desenvolvida pela **RL STUDIO**, focada em performance, segurança e facilidade de uso para jogadores solo.

## 🚀 Principais Funcionalidades

- **Modo Farm Inteligente**:
  - Filtro de alvos por nome via **OCR (Tesseract)** ou comandos de chat.
  - **Busca Visual (OCR)**: O bot identifica o nome do mob na tela e clica automaticamente para dar target.
  - Detecção de morte instantânea para troca de alvo com **Delay Zero**.
- **Modo PvP Pro**: Configure sequências de skills e combos configuráveis.
- **Auto Rebuff**: Sistema inteligente que detecta quando os buffs acabam, usa SOE, vai ao NPC e retorna ao spot de farm.
- **Monitor de Buffs & Summon**: Acompanhe o status do seu personagem e pet em tempo real através de pixels de cor.
- **Rota / GPS**: Grave e siga rotas complexas de farm com suporte a múltiplos pontos de parada.
- **Segurança Ativa**:
  - **Auto-Revide**: Ataca automaticamente se o HP estiver baixo (defesa contra players).
  - **Avoid Players**: Opção para cancelar target se detectar um player.
- **Update Automático**: Verificação de novas versões diretamente pelo GitHub com instalação automática.

## ⌨️ Atalhos Globais (Hotkeys)

- **PAUSE BREAK**: Iniciar / Parar o Bot.
- **INSERT**: Restaurar janela do bot (quando minimizado na bandeja).
- **HOME**: Capturar posição do mouse/pixel (usado nas configurações).
- **END**: Fechar o aplicativo completamente.

## 🛠️ Como Iniciar

1. **Dependências**: Certifique-se de ter o [Python 3.x](https://www.python.org/) instalado.
2. **Execução**:
   - Para desenvolvedores: Execute `python main.py`.
   - Para usuários: Execute o arquivo `L2RedZone.exe` (gerado via `gerar_executavel.bat`).
3. **Configuração**:
   - Configure as teclas de ataque nas abas Farm/PvP.
   - Capture a barra de HP do Mob usando a tecla **HOME**.
   - Se usar o filtro de nomes, instale o [Tesseract OCR](https://github.com/UB-Mannheim/tesseract/wiki).

## 📦 Gerando o Executável

Para criar sua própria versão `.exe`, basta executar o arquivo `gerar_executavel.bat`. Ele cuidará de todas as dependências e gerará o arquivo na pasta `dist/`.

## ⚠️ Aviso Legal

Este bot foi desenvolvido pela **RL STUDIO (RICK LELES)** para fins educacionais e automação de tarefas repetitivas. O uso de ferramentas de automação pode violar os termos de serviço de alguns servidores de jogos. Use por sua conta e risco.

---
**RL STUDIO** | *Desenvolvendo soluções inteligentes para o seu jogo.*
