# Guia de Estilo

Criado usando o briefing com a IA como consultora de design (afinal, sou programador, não designer).

## Paleta de cores

Background Primário: #0A0A0A (Eerie Black).

Texto Principal: #FFFFFF (Branco) – Para títulos de alto impacto.

Texto Secundário: #9CA3AF (Gray-400) – Conforme usado no seu parágrafo do Hero.

Destaque/Accent: #3B82F6 (Blue-500) ou #6366F1 (Indigo-500).

Bordas e Divisores: #262626 (Neutral-800) – Para separar seções sem poluir a visão.

## Tipografia

O segredo do design minimalista "arrojado" está no peso e no espaçamento das letras.

    Títulos (Headings): Utilize uma fonte Sans-Serif geométrica (ex: Inter, Geist ou Satoshi).

        Estilo: font-bold, tracking-tighter (como você já aplicou no Hero ).

        Dica: Em tamanhos grandes (como o seu text-8xl), o espaçamento negativo entre letras gera a sensação de design premium/editorial.

    Corpo de Texto: Inter ou a fonte padrão do sistema.

        Estilo: leading-relaxed para garantir que o recrutador consiga ler seu histórico sem cansar a vista.

    Mono (Para o Blog/Tech): JetBrains Mono ou Fira Code. Use para trechos de código ou pequenos labels "tech" (ex: as tags de tecnologias usadas).

## Espaçamento

Unidade (px),Tailwind Class,Uso Comum
8px,p-2 / gap-2,Espaços internos pequenos / Botões.
16px,p-4 / gap-4,Entre elementos relacionados.
32px,p-8 / gap-8,Padding interno de cards.
64px,py-16 / gap-16,Espaço entre seções menores.
96px,py-24,Espaço entre grandes seções (como seu Hero ).

## Estrutura e layout

Para equilibrar o público de Recrutadores e Empreendedores:
Grid de Projetos

Use um grid de 2 colunas no desktop e 1 no mobile.

    Imagens: Mantenha o padrão grayscale que você iniciou no Hero. Isso dá uma unidade visual incrível. Elas perdem o grayscale (ficam coloridas) apenas no hover.

    Cards: Bordas sutis (border border-neutral-800) e rounded-3xl para conversar com a foto de perfil do seu Hero.

Responsividade

    Containers: Sempre use max-w-7xl mx-auto px-8  para manter o conteúdo centralizado e respirando em telas grandes.

    Mobile First: No mobile, seus títulos text-8xl devem cair para text-5xl ou text-6xl para não quebrar a tela.
