---
author: Daniel Klotz
title: Hello
---
{{< rawhtml >}}
<div id="about"
     style="background-color: #cac0bb;
        color: #000000;
        position: relative;
        padding-top: 1px;
        padding-bottom: 10px;
        padding-left: 25vw;
        padding-right: 25vw;
        margin-left: 0vw;"
        >
    <center>
        <img src="/self.png"></img>
    </center>
    <h2>About me</h2>
    My name is Daniel Klotz. I am a researcher! Currently I work at the Department of Compound Environmental Risks (UFZ, Leipzig) and think about data-driven approaches for reducing enviornmental/hydrological risks. Before that, I got Phd in Hydrology and Water Resource Management at the institute for Hydaulic Engineering, Hydrology and Water Management (BOKU, Vienna) and learned a lot about Machine Learning by doing a Postdoc at the Institute for Machine Learning (JKU, Linz).
    <h3>Contact</h3>
    <b>Email: </b> <a href = "mailto: daniel.klotz@ufz.de">daniel.klotz@ufz.de</a>

    <br><br><br>

</div>

<div class="main" id="pubs" style="position: relative;
        padding-top: 1px;
        padding-bottom: 10px;
        padding-left: 25vw;
        padding-right: 25vw;
        margin-left: 0vw;">
<br>
<h2> Selected publications </h2>
<br>

<a href = "https://doi.org/10.1002/2017WR021253">Klotz, D., Herrnegger, M., & Schulz, K. (2017). Symbolic regression for the estimation of transfer functions of hydrological models. Water Resources Research, 53(11), 9402-9423.</a><br>

This paper explores a more rigorous way to bind the parameters of hydrological models to geo-physical properties than the multi-scale parameter regionalization approach had used before. It spawned its own branch of research, which I have followed with great interest since then.

<hr>

<a href = "https://doi.org/10.5194/hess-23-5089-2019">Kratzert, F., Klotz, D., Shalev, G., Klambauer, G., Hochreiter, S., & Nearing, G. (2019). Towards learning universal, regional, and local hydrological behaviors via machine learning applied to large-sample datasets. Hydrol. Earth Syst. Sci., 2019, 23, 5089–5110.</a><br>

This paper introduced a regional LSTM approach and compared its performance against a set of well established models on a large scale dataset. When this paper was published, we already introduced the LSTM to hydrology and by now the gripGL challenge, where the regional LSTM performed best, now provides a more rigorous test. Yet, the modelling concepts we introduced remain state of the art.

<hr>

<a href = "http://proceedings.mlr.press/v139/hoedt21a.html">Hoedt, P. J., Kratzert, F., Klotz, D., Halmich, C., Holzleitner, M., Nearing, G. S., ... & Klambauer, G. (2021, July). MC-LSTM: Mass-conserving lstm. In International Conference on Machine Learning (pp. 4275-4286). PMLR.</a><br>

This paper represents my showcase for how to explore model assumptions. Instead of building them all in as a prior, we start with a general model class (in this case, the LSTM) and add specific restrictions that we want to explore (in this case, an input conservation property).

<hr>

<a href = "https://doi.org/10.5194/hess-26-1673-2022">Klotz, D., Kratzert, F., Gauch, M., Keefe Sampson, A., Brandstetter, J., Klambauer, G., ... & Nearing, G. (2022). Uncertainty estimation with deep learning for rainfall–runoff modeling. Hydrology and Earth System Sciences, 26(6), 1673-1693.</a><br>

This paper shows how uncertainty estimates for streamflow can be obtained from an LSTM based rainfall-runoff model. To do so, we (a) introduced a set of approaches that can learn to directly estimate the uncertainty using a maximum likelihood approach, (b) implemented a Bayesian reference approach, and (c) realised a framework for evaluating the predictive uncertainty. To my knowledge, the introduced and tested approach still yields the best results for streamflow uncertainty prediction.

<hr>

<a href = "https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2022WR033918">Gauch, M., Kratzert, F., Gilon, O., Gupta, H., Mai, J., Nearing, G., ... &
Klotz, D. (2022). In Defense of Metrics: Metrics Sufficiently Encode Typical Human Preferences Regarding Hydrological Model Performance. Water Resources Research 59, no. 6 (2023): e2022WR033918.</a><br>

This paper examines the connection of human judgement and evaluation diagnostics in hydrological modelling. During the early preparation, we contacted social scientists to make sure that we do things properly. Then, we built a website and motivated hundreds of researchers to rate hydrographs. The, for me, surprising result: If we use multiple existing metrics, we can reflect human judgements about model quality quite well.

<hr>

<a href = "https://link.springer.com/article/10.1007/s00506-021-00767-z">Kratzert, F., Gauch, M., Nearing, G., Hochreiter, S., & Klotz, D. (2021). Niederschlags-Abfluss-Modellierung mit Long Short-Term Memory (LSTM). Österreichische Wasser-und Abfallwirtschaft, 73(7), 270-280.</a><br>

This paper summarises major parts of our research on LSTMs for rainfall-runoff modelling in a way that is comprehensive for practitioners. As of today, it provides the best bird-perspective of the approach that we developed.<br>
<br>
<br>

<div class="main" id="projects"></div>
<h2>Projects </h2>
<h3> Research </h3>
- <a href = "https://neuralhydrology.github.io">NeuralHydrology</a>. Exloring the potential of Deep Learing for Hydrology.

<h3> Fun </h3>
<ul>
<li> <a href = "https://github.com/danklotz/openNotes">Open Notes</a>. Short notes and incomplete lists of random stuff.
<li> <a href = "https://nomonkey.art">NoMonkey</a>. A small project with a good friend of mine. Don't expect many updates.
<li> <a href = "http://allokkio.net">Allokkio</a>. A private, experimental website that is not yet cryptic enough.
</ul>
</div>
<br>
<div id="socials"
    style="background-color: #0E3530;
        color: #f0eeee;
        position: relative;
        padding-top: 1px;
        padding-bottom: 10px;
        padding-left: 25vw;
        padding-right: 25vw;
        margin-left: 0vw;">
    <br>
    <h2>Elsewhere</h2>
    <ul>
    <li><a href="https://scholar.google.com/citations?user=J5Odv8wAAAAJ&hl=en">Google Scholar</a> For updates on scientific publications.  </li>
    <li><a href="https://github.com/danklotz/">Github</a>. Code. But mostly interesting if one wants to how my <a href="https://github.com/danklotz/openNotes">open notes project</a> progresses.</li>
    <li><a href="https://bsky.app/profile/danklotz.bsky.social">Bsky</a>. I am currently testing bluesky, in the hope that it might replace twitter at some point in time. As of now, I am active, in case you want to contact me over there.</li>
    <li><a href="https://neuralhydrology.github.io">NeuralHydrology</a>.  Inactive, but will tweet and retweet science stuff.</li>
    <li><a href="https://www.instagram.com/latentlibrary/">Instagram</a>. Mostly experimental photography..</li>
    </ul>
<br>
</div>

{{< /rawhtml >}}
