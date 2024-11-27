---
layout: home
title: About
---

# Project Team

<div class="team-grid">
    <div class="team-member">
        <img src="assets/images/Anders.jpg" alt="Anders Kristian Munk">
        <h2>Anders Kristian Munk</h2>
        <p>DTU, ECHO lab</p>
        <div class="social-links">
            <a href="#"><img src="assets/images/linkedin.svg" alt="LinkedIn"></a>
            <a href="#"><img src="assets/images/twitter.svg" alt="Twitter"></a>
            <a href="#"><img src="assets/images/website.svg" alt="Website"></a>
        </div>
    </div>

    <div class="team-member">
        <img src="assets/images/Mathieu.jpg" alt="Mathieu Jacomy">
        <h2>Mathieu Jacomy</h2>
        <p>AAU, Tantlab, ADD</p>
        <div class="social-links">
            <a href="#"><img src="assets/images/linkedin.svg" alt="LinkedIn"></a>
            <a href="#"><img src="assets/images/twitter.svg" alt="Twitter"></a>
            <a href="#"><img src="assets/images/website.svg" alt="Website"></a>
        </div>
    </div>

    <div class="team-member">
        <img src="assets/images/Matilde.jpg" alt="Matilde Ficozzi">
        <h2>Matilde Ficozzi</h2>
        <p>AAU, Tantlab, ADD, RUG</p>
        <div class="social-links">
            <a href="#"><img src="assets/images/linkedin.svg" alt="LinkedIn"></a>
            <a href="#"><img src="assets/images/twitter.svg" alt="Twitter"></a>
            <a href="#"><img src="assets/images/website.svg" alt="Website"></a>
        </div>
    </div>

    <div class="team-member">
        <img src="assets/images/Johan.jpg" alt="Johan Irving Søltoft">
        <h2>Johan Irving Søltoft</h2>
        <p>DTU, ECHO lab</p>
        <div class="social-links">
            <a href="#"><img src="assets/images/linkedin.svg" alt="LinkedIn"></a>
            <a href="#"><img src="assets/images/twitter.svg" alt="Twitter"></a>
            <a href="#"><img src="assets/images/website.svg" alt="Website"></a>
        </div>
    </div>

    <div class="team-member">
        <img src="assets/images/Ainoa.jpg" alt="Ainoa Pubill Unzeta">
        <h2>Ainoa Pubill Unzeta</h2>
        <p>DTU, ECHO lab</p>
        <div class="social-links">
            <a href="#"><img src="assets/images/linkedin.svg" alt="LinkedIn"></a>
            <a href="#"><img src="assets/images/twitter.svg" alt="Twitter"></a>
            <a href="#"><img src="assets/images/website.svg" alt="Website"></a>
        </div>
    </div>

    <div class="team-member">
        <img src="assets/images/Sarah.jpg" alt="Sarah Feldes">
        <h2>Sarah Feldes</h2>
        <p>DTU, ECHO lab</p>
        <div class="social-links">
            <a href="#"><img src="assets/images/linkedin.svg" alt="LinkedIn"></a>
            <a href="#"><img src="assets/images/twitter.svg" alt="Twitter"></a>
            <a href="#"><img src="assets/images/website.svg" alt="Website"></a>
        </div>
    </div>

    <div class="team-member">
        <img src="assets/images/Barbara.jpg" alt="Barbara Nino Carreras">
        <h2>Barbara Nino Carreras</h2>
        <p>DTU, ECHO lab</p>
        <div class="social-links">
            <a href="#"><img src="assets/images/linkedin.svg" alt="LinkedIn"></a>
            <a href="#"><img src="assets/images/twitter.svg" alt="Twitter"></a>
            <a href="#"><img src="assets/images/website.svg" alt="Website"></a>
        </div>
    </div>

    <div class="team-member">
        <img src="assets/images/Dario.jpg" alt="Dario Rodighiero">
        <h2>Dario Rodighiero</h2>
        <p>RUG</p>
        <div class="social-links">
            <a href="#"><img src="assets/images/linkedin.svg" alt="LinkedIn"></a>
            <a href="#"><img src="assets/images/twitter.svg" alt="Twitter"></a>
            <a href="#"><img src="assets/images/website.svg" alt="Website"></a>
        </div>
    </div>
</div>

<style>
.team-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 2rem;
    margin: 2rem 0;
}

.team-member {
    text-align: center;
}

.team-member img {
    width: 100%;
    height: auto;
    margin-bottom: 1rem;
    border-radius: 5px;
}

.team-member h2 {
    font-size: 1.2rem;
    margin: 0.5rem 0;
}

.team-member p {
    margin: 0.5rem 0;
    color: #666;
}

.social-links {
    margin-top: 0.5rem;
    display: flex;
    justify-content: center;
    gap: 1rem;
}

.social-links img {
    width: 24px;
    height: 24px;
}

@media (max-width: 1200px) {
    .team-grid {
        grid-template-columns: repeat(3, 1fr);
    }
}

@media (max-width: 768px) {
    .team-grid {
        grid-template-columns: repeat(2, 1fr);
    }
}

@media (max-width: 480px) {
    .team-grid {
        grid-template-columns: 1fr;
    }
}
</style>
