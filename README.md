# Matematički softver - 1. projekt

<b>U projektu promatramo šrenje virusa <u>SARS-CoV-2</u> u svijetu i Hrvatskoj.</b> Projekt je dostupan na GitHub-u: https://github.com/nesto123/MS_projekt1

<h3><i>Upute za pokretanje</i></h3>
<p>Potrebno je:</p>
<ol>
    <li>Skinuti repozitorij lokalno ili klonirati pomoću: <code>git clone https://github.com/nesto123/MS_projekt1.git</code> </li>
    <li><b>Ovaj korak je <u>SAMO za Windows OS</u></b>, za Linux nije potrebno, naredbe se unose u treminal. Potrebno je naći <code>Anaconda Prompt</code>, najlakše je pomoću search-a te se sljedeće naredbe za instalaciju paketa tamo unose!</li>
    <li>Update-ati <i>Anacondu</i> naredbom: <code>conda update --all</code> </li>
    <li>Instalirati dodatni modul <code>GeoPandas</code> za prikaz mapa(.shp datoteka) na <b>jedan</b> od sljedećih načina:
        <ul>
            <li>Prvi način - naredbom: <code>conda install geopandas</code> </li>
            <li>Drugi način -  naredbom: <code>conda install -c conda-forge geopandas</code> </li>
            <li>Treći način:
                <ol>
                    <li>Instalirati <code>pip</code> naredbom: <code>sudo apt install python3-pip</code></li>
                    <li>Instalirati <code>GeoPandas</code> naredbom: <code>pip install geopandas</code></li>
                </ol>
            </li>
            <li>Četvrti način dostupan je u <a href="https://geopandas.org/install.html">službenoj dokumentaciji</a></li>
        </ul>
    </li>
    <li>Instalirati dodatni modul <code>descartes</code> naredbom: <code>conda install -c conda-forge descartes</code></li>
    <li>Pokrenuti <i>Jupyther</i> bilježnicu <u>Projekt.ipynb</u>.</li>
</ol>

<h6> Napomena:</h6>
    <ul>
        <li>U prethodnim koracima instalacije potrebno je dati suglasnost za instalaciju navedenih paketa.</li>
    </ul>

