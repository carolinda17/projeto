# projeto
sobrenaturalflix

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sobrenatural - Série</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">Sobrenatural</div>
        <nav>
            <ul>
                <li><a href="#sobre">Sobre a Série</a></li>
                <li><a href="#personagens">Personagens</a></li>
                <li><a href="#temporadas">Temporadas</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="banner">
            <h1>Sobrenatural (Supernatural)</h1>
            <p>Uma série de suspense, mistério e caça aos monstros!</p>
        </section>
        <section id="sobre">
            <h2>Sobre a Série</h2>
            <p>
                Sobrenatural (Supernatural) é uma série de televisão americana criada por Eric Kripke. Ela acompanha os irmãos Sam e Dean Winchester enquanto eles caçam demônios, fantasmas, monstros e outras entidades sobrenaturais por todos os Estados Unidos.
            </p>
        </section>
        <section id="personagens">
            <h2>Personagens Principais</h2>
            <div class="cards">
                <div class="card">
                    <img src="https://static.wikia.nocookie.net/supernatural/images/2/25/DeanWinchester.png" alt="Dean Winchester">
                    <h3>Dean Winchester</h3>
                    <p>O irmão mais velho, corajoso e sarcástico, sempre disposto a proteger sua família.</p>
                </div>
                <div class="card">
                    <img src="https://static.wikia.nocookie.net/supernatural/images/6/6f/SamWinchester.png" alt="Sam Winchester">
                    <h3>Sam Winchester</h3>
                    <p>O irmão mais novo, inteligente e sensível, busca uma vida normal, mas é puxado para o mundo sobrenatural.</p>
                </div>
                <div class="card">
                    <img src="https://static.wikia.nocookie.net/supernatural/images/3/33/CastielS15.png" alt="Castiel">
                    <h3>Castiel</h3>
                    <p>Um anjo que se torna aliado e amigo dos irmãos Winchester na luta contra o mal.</p>
                </div>
            </div>
        </section>
        <section id="temporadas">
            <h2>Temporadas</h2>
            <p>
                A série possui 15 temporadas, exibidas entre 2005 e 2020. Cada temporada traz novos desafios, criaturas e histórias emocionantes para Sam e Dean.
            </p>
            <ul class="temporadas-lista">
                <li>Temporada 1: Caçando monstros e buscando o pai desaparecido.</li>
                <li>Temporada 5: O apocalipse e a luta contra Lúcifer.</li>
                <li>Temporada 10: A Marca de Caim e a ascensão do mal interno.</li>
                <li>Temporada 15: O confronto final com Deus (Chuck).</li>
            </ul>
        </section>
        <section id="contato">
            <h2>Contato</h2>
            <form>
                <input type="text" placeholder="Seu nome" required>
                <input type="email" placeholder="Seu e-mail" required>
                <textarea placeholder="Sua mensagem"></textarea>
                <button type="submit">Enviar</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 Site de Fãs de Sobrenatural | Este site é um projeto fictício.</p>
    </footer>
</body>
</html>

o css

/* Reset básico */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', Arial, sans-serif;
    background: #181818;
    color: #f0f0f0;
    line-height: 1.6;
}

header {
    background: #111;
    padding: 20px;
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: space-between;
}

.logo {
    font-size: 1.9rem;
    font-weight: bold;
    letter-spacing: 2px;
    color: #ff9a00;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 22px;
}

nav ul li a {
    text-decoration: none;
    color: #f0f0f0;
    font-weight: bold;
    transition: color 0.2s;
}

nav ul li a:hover {
    color: #ff9a00;
}

.banner {
    background: linear-gradient(to right, #111, #2f2f2f);
    padding: 60px 20px 40px 20px;
    text-align: center;
}

.banner h1 {
    font-size: 2.5rem;
    margin-bottom: 16px;
    color: #ff9a00;
    text-shadow: 2px 2px 8px #000;
}

.banner p {
    font-size: 1.3rem;
    color: #ddd;
}

main {
    max-width: 1000px;
    margin: 30px auto 70px auto;
    padding: 20px;
    background: #222;
    border-radius: 12px;
    box-shadow: 0 0 18px rgba(0,0,0,0.15);
}

h2 {
    color: #ff9a00;
    margin-bottom: 12px;
}

section {
    margin-bottom: 35px;
}

.cards {
    display: flex;
    gap: 28px;
    flex-wrap: wrap;
    justify-content: center;
}

.card {
    background: #292929;
    border-radius: 8px;
    box-shadow: 0 2px 10px #0004;
    padding: 18px;
    width: 200px;
    text-align: center;
    transition: transform 0.2s;
}

.card:hover {
    transform: translateY(-6px) scale(1.04);
}

.card img {
    width: 100px;
    height: 120px;
    object-fit: cover;
    border-radius: 7px;
    margin-bottom: 12px;
    border: 2px solid #ff9a00;
}

.card h3 {
    font-size: 1.2rem;
    color: #ff9a00;
    margin-bottom: 8px;
}

.temporadas-lista {
    margin-left: 25px;
    color: #ececec;
}

form {
    display: flex;
    flex-direction: column;
    gap: 13px;
    max-width: 340px;
    margin: 0 auto;
}

form input, form textarea {
    padding: 9px;
    border-radius: 6px;
    border: none;
    background: #333;
    color: #fff;
    font-size: 1rem;
}

form textarea {
    resize: vertical;
    min-height: 60px;
}

form button {
    background: #ff9a00;
    color: #222;
    border: none;
    padding: 10px;
    border-radius: 6px;
    cursor: pointer;
    font-weight: bold;
    transition: background 0.2s;
}

form button:hover {
    background: #ffaa33;
}

footer {
    background: #111;
    color: #ff9a00;
    text-align: center;
    padding: 18px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
    left: 0;
}

/* Responsivo */
@media (max-width: 800px) {
    .cards {
        flex-direction: column;
        align-items: center;
    }
    main {
        margin: 15px;
    }
    header {
        flex-direction: column;
        gap: 15px;
    }
}
