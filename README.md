Lotka–Volterra‑saalistaja–saalis -simulointi
Graafinen ja interaktiivinen simulointi klassisesta Lotka–Volterra‑saalistaja–saalis‑mallista.
Ohjelma ratkaisee differentiaaliyhtälöt numeerisesti ja piirtää sekä populaatioiden ajallisen kehityksen että vaiheavaruuspolun. Käyttäjä voi säätää mallin parametreja reaaliaikaisesti liukusäätimillä ja palauttaa oletusarvot painikkeella.

Kuvaus
Lotka–Volterra‑malli kuvaa kahden lajin vuorovaikutusta: saaliin ja saalistajan.
Malli koostuu kahdesta ensimmäisen kertaluvun differentiaaliyhtälöstä:

dx/dt = αx − βxy

dy/dt = δxy − γy

missä

x = saalispopulaatio

y = saalistajapopulaatio

α, β, δ, γ = mallin parametrit

Tämä repositorio sisältää Python‑skriptin, joka toteuttaa simuloinnin käyttäen scipy.integrate.odeint‑ratkaisijaa ja visualisoi tulokset matplotlib‑kirjastolla.
Graafinen käyttöliittymä sisältää liukusäätimet parametrien (α, β, δ, γ) muuttamiseen sekä painikkeen oletusarvojen palauttamiseen.

Esikatselu
https://github.com/Tekton-MAS/Lotka-Volterra/blob/main/Lotka-Volterra_sample.jpg  
Esimerkkikuva simuloinnin oletusparametreilla

Asennus ja käyttö
Vaatimukset
Python 3.8 tai uudempi

Kirjastot: numpy, scipy, matplotlib

Asennus
Kloonaa repositorio ja asenna riippuvuudet:

pip install numpy scipy matplotlib
git clone https://github.com/Tekton-MAS/Lotka-Volterra.git
cd Lotka-Volterra

Suoritus

python lotka_volterra.py

