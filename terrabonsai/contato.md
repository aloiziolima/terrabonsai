---
layout: default
title: Contato
permalink: /terrabonsai/contato
---

<main class="main">
    <div class="container">
        <form>
            <fieldset>
            <label for="nome">Nome completo</label>
            <input id="nome" type="text" name="nome" required autofocus pattern="[A-Za-z ']{4,}" title="O nome precisa ter pelo menos 4 caracteres" placeholder="Seu Nome">
            <label for="email">E-mail</label>
            <input id="email" type="email" name="email" required placeholder="seu@email.com">
            <label for="assunto">Assunto</label>
            <input id="assunto" type="assunto" name="assunto" required placeholder="Assunto">
            </fieldset>
            <label for="mensagem">Mensagem</label>
            <textarea id="mensagem" name="mensagem" cols="60" rows="8" placeholder="Digite aqui sua mensagem"></textarea>
            <button type="submit">Enviar mensagem</button>
        </form>
    </div>
    <div class="icones-contatos">
        <div class="box">
            <a href="mailto:terrabonsai@gmail.com">
                <img src="../assets/images/envelope.png" alt="email">
            </a>
            <a class="texto" href="mailto:lima.aloizio@gmail.com">terrabonsai@gmail.com</a>
        </div>
        <div class="box">
            <a href="tel:+5531988987503">
                <img src="../assets/images/whatsapp.png" alt="telefone">
            </a>
            <a class="texto" href="tel:+5531988987503">(31)98898-7503</a>
        </div>
        <div class="box">
            <a href="https://www.facebook.com/Escola-Terra-Bonsai-231177263574283/">
                <img src="../assets/images/facebook.png" alt="facebook">
            </a>
        </div>
    </div>
</main>
