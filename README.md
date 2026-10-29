# Biblioteca Blender

Repositório privado planejado para organizar, versionar e preservar arquivos-fonte 3D desenvolvidos no **Blender**.

> **Estado atual:** a árvore versionada contém somente este README. Os projetos listados no portfólio não estão armazenados aqui neste momento; esta página descreve o objetivo da biblioteca, não confirma a presença dos arquivos.

## Objetivo

- Preservar arquivos de projeto e versões de trabalho.
- Organizar estudos e assets 3D em pastas por projeto.
- Manter os arquivos-fonte separados das apresentações e renders publicados.
- Permitir, futuramente, integração com ferramentas de catalogação do portfólio, caso essa integração seja implementada.

## Estrutura sugerida

Quando os arquivos forem adicionados, uma organização possível é:

```text
Biblioteca-Blender/
├── product-models/
├── environments/
├── animation-vfx/
├── architecture/
├── experiments/
└── README.md
```

Essa árvore é uma proposta, não uma estrutura já existente. Nomeie as pastas conforme o conteúdo real e evite duplicar arquivos de projetos que já tenham um repositório canônico.

## Versionamento de arquivos grandes

Antes de adicionar arquivos `.blend`, verifique o tamanho e o histórico desejado. Git LFS pode ser útil para arquivos grandes, mas deve ser configurado deliberadamente; não habilite rastreamento global sem avaliar as cotas e os arquivos existentes. Exporte renders e vídeos de demonstração para portfólios públicos quando apropriado, sem expor arquivos privados ou dados de terceiros.

## Portfólios públicos

- [Portfólio web — programação e 3D](https://luca-toniolo.vercel.app/)
- [ArtStation](https://www.artstation.com/lvc4br)
- [Behance](https://www.behance.net/Toniolo_Luca)
- [The Rookies](https://therookies.co/u/Lvc4br)
- [GitHub — Lvc4br](https://github.com/Lvc4br)

**Autor:** Luca Toniolo — estudante de Desenvolvimento de Sistemas e artista 3D autodidata.
