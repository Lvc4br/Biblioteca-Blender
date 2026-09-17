# Biblioteca Blender

Biblioteca pessoal de modelos, assets e projetos 3D desenvolvidos no **Blender** por **Luca Toniolo**.

> Repositório de arquivo e versionamento dos meus trabalhos 3D (quase 8 anos de experiência autodidata).

---

## Sobre

Esta biblioteca reúne assets hard-surface, organics, simulações, animações e ambientes criados no Blender, com foco em:

- Modelagem hard-surface de alta fidelidade
- Texturização avançada (incluindo uso estratégico de IA para materiais)
- Simulações de fluidos
- Iluminação e renderização (Cycles / Eevee)
- Composição e efeitos ópticos

O objetivo principal é **não perder o histórico** dos projetos e, no futuro, servir como fonte de dados para uma API/banco de dados que alimentará o portfólio em React.

---

## Projetos em destaque

### Assets Hard-Surface Realistas
Modelagem e texturização de alta fidelidade de peças comerciais e equipamentos:
- **Blackmagic ATEM Mini Pro** (várias versões de venda)
- Coca-Cola Bottle

Inclui iluminação, renderização Cycles/Eevee e materiais refinados com apoio de IA.  
Publicados no [ArtStation](https://artstation.com/lvc4br) e [Behance](https://www.behance.net/Toniolo_Luca).

### Crank Boy (Game Boy)
Réplica 3D de brinquedo antigo de console com manivela.  
Modelagem hard-surface, texturização detalhada, iluminação e renderização.

### Sci-fi Planet
Ambiente completo de ficção científica, do conceito à renderização final (modelagem, texturização avançada, iluminação e composição).

### Laser Animation
Animação 3D focada em efeitos de feixe de laser e refração de luz.  
Iluminação volumétrica, materiais emissores e renderização técnica para simulação de efeitos ópticos.

### Water VFX Simulation
Simulação física de fluidos com foco em realismo (parâmetros de física, iluminação e renderização).

### Coliseu de Roma *(em desenvolvimento)*
Recriação 3D histórica do Coliseu, com pesquisa em fontes arquitetônicas originais (pranchas de F. Guadet, 1878).  
Planejado para submissão ao **The Rookies Award**.

### Coleção “Constelação Floral” *(em desenvolvimento)*
Design autoral de joia (3 anéis: Namoro, Noivado e Casamento).  
Atualmente em fase de concept art, também destinado ao The Rookies Award.

---

## Estrutura atual da biblioteca

```
3d/
├── atem mini pro/          # Modelos do Blackmagic ATEM Mini Pro
├── lazer blend/            # Animações e testes de laser + compositing
├── ROOKIE/
│   ├── game boy/           # Crank Boy / Game Boy
│   └── THE ROOKIES AWARDS/
├── The Colosseum amphitheatre/
│   ├── colunas/            # Ordens arquitetônicas (iónica, coríntia...)
│   ├── estatuas/
│   └── the colosseum/
├── product commercial/
│   └── coke/               # Assets comerciais (Coca-Cola)
├── planet cinemact/        # Sci-fi Planet
├── music space/
└── vinheta/                # Logos e vinhetas (SVG + Blend)
```

> Ainda serão adicionadas pastas de **referências** e **renders** finais.

---

## Como usar / baixar

### Opção recomendada (arquivo)
Os arquivos `.blend` são grandes. A forma mais simples e estável de baixar tudo é através dos **Releases**:

1. Vá em [Releases](https://github.com/Lvc4br/Biblioteca-Blender/releases)
2. Baixe o arquivo `.7z` mais recente
3. Extraia e abra os `.blend` no Blender

### Git LFS (se quiser versionar individualmente)
```bash
git lfs install
git lfs track "*.blend"
git lfs track "*.blend1"
git add .gitattributes
# depois adicione e faça push dos arquivos
```

**Recomendação atual:** use **Release + arquivo compactado (.7z)** enquanto o repositório servir principalmente como backup.  
Git LFS só vale a pena se você for versionar mudanças frequentes em arquivos individuais.

---

## Sobre o autor

**Luca Toniolo**  
Estudante de Desenvolvimento de Sistemas | Generalista 3D (Blender)

- Quase 8 anos de experiência autodidata em modelagem 3D avançada
- Portfólio ativo: [ArtStation](https://artstation.com/lvc4br) · [Behance](https://www.behance.net/Toniolo_Luca) · [The Rookies](https://therookies.co/u/Lvc4br)
- GitHub: [Lvc4br](https://github.com/Lvc4br)
- Portfólio web: [lvc4br.github.io/Web-Portfolio](https://lvc4br.github.io/Web-Portfolio/)

---

## Roadmap

- [x] README inicial
- [ ] Upload dos arquivos `.blend` via Release
- [ ] Pastas de referências e renders finais
- [ ] Estrutura limpa e padronizada de pastas
- [ ] (Futuro) API + banco de dados para alimentar o portfólio React

---

*Última atualização: Setembro 2026*
