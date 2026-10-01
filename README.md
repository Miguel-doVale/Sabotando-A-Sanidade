<div align="center">

# 🎮 Sabotando Sanidade

**Você é o vilão.**

🏆 **1º lugar na categoria Jogos Digitais — UNDB GameJam 2026**

<a href="https://sun-akuma.itch.io/sabotando-sanidade"><img src="https://img.shields.io/badge/baixar-itch.io-FA5C5C?style=for-the-badge&logo=itchdotio&logoColor=white&labelColor=1a1a1a"/></a>
![Godot](https://img.shields.io/badge/Godot_4.7-1a1a1a?style=for-the-badge&logo=godotengine&logoColor=478CBF)
![GDScript](https://img.shields.io/badge/GDScript-1a1a1a?style=for-the-badge&logo=godotengine&logoColor=478CBF)

</div>

---

## Sobre o jogo

Um personagem atravessa uma depressão profunda e, um dia, decide que vai sair dessa. O seu objetivo é impedir que isso aconteça, porque **o vilão é você**.

*Sabotando Sanidade* é um jogo brasileiro criado em equipe durante a **UNDB GameJam 2026**, onde conquistou o **1º lugar na categoria de jogos digitais**. A proposta inverte o papel tradicional do jogador para levantar uma reflexão sobre saúde mental.

> ⚠️ **Aviso de conteúdo:** o jogo aborda o tema da depressão.

## Download

O jogo está disponível gratuitamente no itch.io: **[sun-akuma.itch.io/sabotando-sanidade](https://sun-akuma.itch.io/sabotando-sanidade)**

## Equipe

Desenvolvido em game jam por uma equipe de 4 pessoas: 2 designers e 2 desenvolvedores.

| Integrante | Função |
|---|---|
| **Miguel Victor** ([@Miguel-doVale](https://github.com/Miguel-doVale)) | Desenvolvimento do jogo e integração da arte |
<!-- Adicione aqui os demais integrantes, no mesmo formato:
| **Nome** ([@usuario](https://github.com/usuario)) | Design / Desenvolvimento |
-->

## Rodando o projeto

1. Instale o [Godot Engine 4.7](https://godotengine.org/download) (renderizador *Compatibility*).
2. Clone o repositório:
   ```bash
   git clone https://github.com/Miguel-doVale/Sabotando-A-Sanidade.git
   ```
3. No Godot, clique em **Importar** e selecione o arquivo `project.godot`.
4. Pressione **F5** para jogar.

**Testes:** o projeto usa o [GUT](https://github.com/bitwes/Gut) (Godot Unit Test). Os testes ficam em `tests/unit/` e rodam pelo painel do GUT dentro do editor.

## Estrutura do projeto

```
├── assets/                    # recursos gerais do jogo
├── components/interactable/   # componente de objetos interativos
├── entities/resident/         # o personagem (morador)
├── levels/bedroom/            # cenário do quarto
├── ui/hud/                    # interface durante o jogo
├── localization/              # textos traduzíveis (pt-BR)
├── resources/interactables/   # dados dos objetos interativos
├── sprites/  game sprites menu/  concept_art/   # arte
├── sound_effects/             # efeitos sonoros
├── specs/                     # especificação das mecânicas
├── tests/unit/                # testes automatizados (GUT)
├── telainicial.tscn           # tela inicial
└── créditos.tscn              # tela de créditos
```

---

<div align="center">

Feito com ☕ e pouco sono na **UNDB GameJam 2026** · São Luís, MA

</div>
