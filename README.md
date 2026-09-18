<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Mundo dos Cachorros</title>

    <style>
        /* =========================================================
           VARIÁVEIS DA PALETA
           Altere somente estes valores para mudar as cores do site.
           ========================================================= */
        :root {
            --azul-escuro: #0b1f3a;
            --azul: #145da0;
            --azul-medio: #1f7acb;
            --azul-claro: #dceeff;
            --azul-fundo: #f4f8fc;
            --branco: #ffffff;
            --texto: #1f2937;
            --borda: #c7d9ea;
            --sombra: rgba(11, 31, 58, 0.12);
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            line-height: 1.7;
            color: var(--texto);
            background: var(--azul-fundo);
        }

        header {
            background: linear-gradient(135deg, var(--azul-escuro), var(--azul));
            color: var(--branco);
            text-align: center;
            padding: 48px 20px;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        header p {
            max-width: 700px;
            margin: 0 auto;
            opacity: 0.9;
        }

        nav {
            background: var(--branco);
            border-bottom: 1px solid var(--borda);
            box-shadow: 0 2px 8px var(--sombra);
            position: sticky;
            top: 0;
            z-index: 10;
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 8px;
            padding: 12px 20px;
        }

        nav a {
            display: block;
            color: var(--azul-escuro);
            text-decoration: none;
            font-weight: bold;
            padding: 8px 16px;
            border-radius: 6px;
        }

        nav a:hover {
            background: var(--azul-claro);
            color: var(--azul);
        }

        main {
            width: min(1100px, 92%);
            margin: 40px auto;
        }

        section {
            background: var(--branco);
            padding: 32px;
            margin-bottom: 30px;
            border: 1px solid var(--borda);
            border-radius: 12px;
            box-shadow: 0 6px 18px var(--sombra);
        }

        h2 {
            color: var(--azul-escuro);
            margin-bottom: 18px;
            font-size: 1.8rem;
        }

        h3 {
            color: var(--azul);
            margin: 24px 0 10px;
        }

        p {
            margin-bottom: 16px;
        }

        ul, ol {
            margin: 12px 0 18px 24px;
        }

        li {
            margin-bottom: 8px;
        }

        .destaque {
            background: var(--azul-claro);
            border-left: 5px solid var(--azul-medio);
            padding: 20px;
            border-radius: 8px;
            margin-top: 20px;
        }

        .galeria {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
            margin-top: 20px;
        }

        figure {
            margin: 0;
            background: var(--azul-fundo);
            border: 1px solid var(--borda);
            border-radius: 10px;
            overflow: hidden;
        }

        figure img {
            width: 100%;
            height: 260px;
            object-fit: cover;
            display: block;
        }

        figcaption {
            padding: 12px 14px;
            font-size: 0.9rem;
            color: var(--azul-escuro);
        }

        footer {
            background: var(--azul-escuro);
            color: var(--branco);
            text-align: center;
            padding: 30px 20px;
            margin-top: 50px;
        }

        footer p {
            margin: 4px 0;
        }

        @media (max-width: 700px) {
            header h1 {
                font-size: 2rem;
            }

            section {
                padding: 22px;
            }

            .galeria {
                grid-template-columns: 1fr;
            }

            figure img {
                height: 230px;
            }
        }
    </style>
</head>

<body>

    <header id="inicio">
        <h1>🐶 Mundo dos Cachorros</h1>
        <p>
            Descubra curiosidades, cuidados, raças e tudo sobre os melhores
            amigos do ser humano.
        </p>
    </header>

    <nav>
        <ul>
            <li><a href="#inicio">Início</a></li>
            <li><a href="#sobre">Sobre</a></li>
            <li><a href="#conteudo">Cuidados</a></li>
            <li><a href="#galeria">Galeria</a></li>
            <li><a href="#contato">Contato</a></li>
        </ul>
    </nav>

    <main>

        <section id="sobre">
            <h2>🐾 Sobre os Cachorros</h2>

            <p>
                Os cachorros são animais conhecidos por sua inteligência,
                lealdade e capacidade de criar fortes vínculos com as pessoas.
                Eles fazem parte da vida de muitas famílias e podem ser grandes
                companheiros no dia a dia.
            </p>

            <p>
                Existem centenas de raças de cães, cada uma com características,
                tamanhos, comportamentos e necessidades diferentes. Além das
                raças, cada cachorro possui sua própria personalidade.
            </p>

            <div class="destaque">
                <p>
                    <strong>Você sabia?</strong> Os cães possuem um olfato
                    extremamente desenvolvido e conseguem perceber cheiros em
                    concentrações muito menores do que os seres humanos.
                </p>
            </div>
        </section>

        <section id="conteudo">
            <h2>🐕 Conhecendo os Cachorros</h2>

            <h3>Alimentação</h3>
            <p>
                Uma alimentação equilibrada é importante para manter o cachorro
                saudável. A quantidade e o tipo de alimento devem considerar
                fatores como idade, tamanho, nível de atividade e necessidades
                individuais do animal.
            </p>

            <h3>Exercícios e Brincadeiras</h3>
            <p>
                Passeios, brincadeiras e atividades adequadas ajudam a manter
                os cães ativos e estimulados. A rotina deve respeitar a idade,
                condição física e características de cada cachorro.
            </p>

            <h3>Cuidados Importantes</h3>
            <ul>
                <li>Manter a vacinação em dia.</li>
                <li>Oferecer água limpa e fresca.</li>
                <li>Proporcionar alimentação adequada.</li>
                <li>Realizar consultas veterinárias.</li>
                <li>Oferecer carinho, atenção e atividades.</li>
            </ul>

            <h3>Rotina de um Cachorro</h3>
            <ol>
                <li>Alimentação adequada durante o dia.</li>
                <li>Passeios e momentos de brincadeira.</li>
                <li>Descanso em um ambiente confortável.</li>
            </ol>
        </section>

        <section id="galeria">
            <h2>📸 Galeria de Cachorros</h2>

            <p>
                Confira alguns exemplos de cães de diferentes tamanhos,
                características e personalidades.
            </p>

            <div class="galeria">

                <figure>
                    <img
                        src="https://images.unsplash.com/photo-1552053831-71594a27632d?auto=format&fit=crop&w=900&q=80"
                        alt="Cachorro da raça Golden Retriever"
                    >
                    <figcaption>
                        Golden Retriever — conhecido por ser amigável,
                        inteligente e companheiro.
                    </figcaption>
                </figure>

                <figure>
                    <img
                        src="https://images.unsplash.com/photo-1543466835-00a7907e9de1?auto=format&fit=crop&w=900&q=80"
                        alt="Cachorro olhando para a câmera"
                    >
                    <figcaption>
                        Os cães possuem diferentes personalidades e
                        características.
                    </figcaption>
                </figure>

                <figure>
                    <img
                        src="https://images.unsplash.com/photo-1587300003388-59208cc962cb?auto=format&fit=crop&w=900&q=80"
                        alt="Cachorro brincando"
                    >
                    <figcaption>
                        Brincadeiras e atividades ajudam a manter os cães
                        estimulados e ativos.
                    </figcaption>
                </figure>

            </div>
        </section>

        <section id="contato">
            <h2>📩 Fale Conosco</h2>

            <p>
                Gostou de conhecer mais sobre o mundo dos cachorros?
                Entre em contato para compartilhar suas dúvidas, histórias
                e experiências com seu melhor amigo.
            </p>

            <p>
                Este site foi criado para reunir informações e curiosidades
                sobre cães de maneira simples e acessível.
            </p>
        </section>

    </main>

    <footer>
        <p>🐾 O melhor amigo do ser humano merece todo o nosso carinho.</p>
        <p>© Mundo dos Cachorros — Todos os direitos reservados.</p>
    </footer>

</body>
</html>
