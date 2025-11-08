# jogo-2# Battle of the Kingdom

 **Projeto de Desenvolvimento de Jogos — Python (Pygame, 2D, Era Medieval)**

---

## 👥 Integrantes
1. Felipe Kazulle  
2. João Pedro  
3. Odilon Neto  
4. Pedro Igor  

---

##  Ideia Principal

**Battle of the Kingdom** é um jogo 2D feito no Unity com C#, ambientado na era medieval.  
O jogador controla um cavaleiro solitário que deve proteger o castelo de ondas de inimigos.  
Cada inimigo derrotado concede pontos, e o objetivo é sobreviver o máximo possível.

---

## Gameplay

- O personagem pode **andar**, **pular** e **atacar**.
- Inimigos aparecem automaticamente (spawns) e ficam mais fortes com o tempo.
- Quando a vida chega a zero, o jogo exibe “Game Over”.

---

##  Controles
| Ação | Tecla |
|------|-------|
| Mover | A / D ou Setas |
| Pular | Espaço |
| Atacar | botao direito do mouse |
| Pausar | ESC |

---

##  Sistema de Pontuação
- +10 pontos por inimigo derrotado  
- Quando a vida chega a zero → **Game Over**

---

##  Estrutura do Projeto

src/
├── main.py
├── game.py
├── player.py
├── enemy.py
└── settings.py


---

##  Ferramentas
- Unity  
- C# 
- Git / GitHub  

---

##  Executar o jogo

### Criar ambiente virtual
```bash
python -m venv venv


Ativar o ambiente
Windows:
venv\Scripts\activate

macOS/Linux:
source venv/bin/activate

 Instalar dependências
pip install -r requirements.txt

 Rodar o jogo
python src/main.py


 Projeto desenvolvido em 2025 — Disciplina de Desenvolvimento de Jogos.

---

## 6. `CONTRIBUTING.md`

```markdown
#  Guia de Contribuição

##  Como contribuir

1. Faça um fork do repositório.
2. Crie uma branch para sua modificação:
git checkout -b feature/nome-da-feature
3. Faça suas alterações e commit:
git commit -m "Adiciona feature X"
4. Envie para o seu fork e abra um Pull Request.

---

##  Padrões de Código
- Use nomes descritivos para variáveis e funções.
- Comente trechos complexos do código.
- Mantenha o estilo PEP8.

---

## Checklist antes de enviar
- [ ] O jogo roda sem erros
- [ ] Testei a nova funcionalidade
- [ ] Atualizei o README se necessário
