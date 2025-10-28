# Depoimentos — Projeto

Arquivos criados para a página de Depoimentos.

O que foi adicionado:

- `index.html` — página de Depoimentos pronta para uso.
- `css/styles.css` — estilos responsivos e layout em grade.
- `assets/` — pasta onde você deve colocar a imagem que vai enviar (nome sugerido: `depoimento-bg.jpg`).

- `images/` — pasta alternativa onde você pode colar a imagem de fundo diretamente (nome sugerido: `depoimento-bg.jpg`).

Como usar:

1. Coloque a imagem que você vai me enviar em `assets/depoimento-bg.jpg`.
1. Coloque a imagem que você vai me enviar em `images/depoimento-bg.jpg` (recomendado) ou em `assets/depoimento-bg.jpg`.

Notas:

- O CSS foi atualizado para procurar, na ordem, por:
	1. `images/images.jpg` (se você colou o arquivo sem renomear)
	2. `images/depoimento-bg.jpg` (nome recomendado)
	3. `assets/depoimento-bg.jpg` (fallback)

- Se você colou a imagem com outro nome (por exemplo `images.jpg`), o CSS agora tentará usar esse arquivo automaticamente. Caso prefira, renomeie para `depoimento-bg.jpg`.
2. Abra `index.html` no navegador (duplo clique) para visualizar a página.

Comandos (PowerShell) — opcional:

```powershell
# Abre a página padrão no navegador
Start-Process 'c:\Users\wal1a\OneDrive\Área de Trabalho\Projeto-PI-Depoimentos\index.html'
```

Substituindo a imagem:

- Se quiser outro nome para a imagem, atualize a URL no `css/styles.css` (linha com `background-image:url('../assets/depoimento-bg.jpg')`).

Depoimentos incluídos (exemplos sugeridos):

1. Ana Santos — Estagiária de Front-end — 12/08/2024
2. Bruno Oliveira — Desenvolvedor Backend Júnior — 22/01/2025
3. Carla Mendes — Analista de Dados — 05/11/2024
4. Diego Ribeiro — Engenheiro de Software — 30/10/2023
5. Érika Carvalho — Estagiária em UX/UI — 14/03/2025
6. Fábio Lima — Desenvolvedor Fullstack — 18/06/2024

Se quiser, eu posso:

- Substituir a imagem neste repositório quando você fizer upload dela aqui.
- Ajustar cores, fontes ou o texto dos depoimentos.
- Gerar versões em React/Vue caso queira integrar com o site.
