# Trilha JS Developer - Pokedex
<!-- Barra de pesquisa -->
<input type="text" placeholder="Buscar Pokémon" class="search">

/* Cards Pokémon */
.pokemon {
    transition: transform 0.3s ease;
    border-radius: 12px;
    padding: 1rem;
}

/* Efeito hover */
.pokemon:hover {
    transform: scale(1.05);
}

/* Campo de busca */
.search {
    width: 100%;
    max-width: 300px;
    padding: 10px;
    margin: 20px auto;
    display: block;
    border-radius: 10px;
    border: 1px solid #ccc;
    font-size: 16px;
    outline: none;
}

/* Efeito ao selecionar o input */
.search:focus {
    border-color: #ff5350;
    box-shadow: 0 0 8px rgba(255, 83, 80, 0.5);
}

/* Responsividade */
@media screen and (max-width: 768px) {
    .pokemon {
        width: 100%;
    }
}
/* Efeito ao clicar no input */
.search:focus {
    border-color: #ff5350;
    box-shadow: 0 0 8px rgba(255, 83, 80, 0.5);
}

/* Responsividade */
@media screen and (max-width: 768px) {
    .pokemon {
        width: 100%;
    }
}
