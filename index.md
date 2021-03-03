<style>
body {
font-size:14px;
}
a, a:visited {
color:dodgerblue;
}


.aboutme {
display:block;
width:100%;
float:left;
}
.inside-block {
float:left;
display:inline-block;
}

.section-title {
    float: left;
    width: 100%;
    font-size: 24px;
    font-weight: bold;
    padding: 0px 0px 0px 0px;
}

.article-year {
    float: left;
    width: 100%;
    font-size: 18px;
    padding: 5px 0px 5px 0px;
    margin: 0px;
    color: black;
    font-weight: bold;
}

.article-block, .course-block, .review-block, .contact-block {
display:inline-block; 
display: flex; 
width:100%; 
float:left;
margin: 10px 0px 0px 0px;
padding:0px;
}

.article-left-bar, .course-left-bar, .review-left-bar {
float:left;
display:inline-block; 
width: 3px; 
height:auto; 
background-color: #ccc;
margin-left:10px;
}
.article-inline-title, .course-inline-title {
font-weight: bold; 
margin:1px 0px 1px 0px;
padding: 0px;
}
.article-inline-authors {
color: gray;
font-size:12px;
margin:1px 0px 1px 0px;
}
.article-inline-conference, .course-inline-details {
color: gray; 
font-style: italic;
font-size:12px;
margin:1px 0px 1px 0px;
}
.article-inline-reference, .course-inline-role {
color: black; 
font-size:12px;
margin:1px 0px 1px 0px;
}
.review-inline-title {
font-weight: bold; 
float:left;
}
.review-inline-year {
float:left;
margin-left:10px;
}
.review-inline-role {
float:left;
margin-left:10px;
}

.contact-subblock {
display:flex;
  width: 100%;
  padding: 10px;
}

.contact-title {
width:70px;
font-weight:bold;
float:left;
}
.contact-info {
float:left;
font-size: 12px;
}

</style>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
<script>
$(document).ready(function(){
    $(".article-block").hover(function(){
        $(this).css("background-color", "#fafafa");
        $(this).find(".article-left-bar").css("background-color", "dodgerblue");
    }, function(){
        $(this).css("background-color", "white");
        $(this).find(".article-left-bar").css("background-color", "#ccc");
    });
    
    
    $(".course-block").hover(function(){
        $(this).css("background-color", "#fafafa");
        $(this).find(".course-left-bar").css("background-color", "forestgreen");
    }, function(){
        $(this).css("background-color", "white");
        $(this).find(".course-left-bar").css("background-color", "#ccc");
    });
    
        $(".review-block").hover(function(){
        $(this).css("background-color", "#fafafa");
        $(this).find(".review-left-bar").css("background-color", "darkred");
    }, function(){
        $(this).css("background-color", "white");
        $(this).find(".review-left-bar").css("background-color", "#ccc");
    });
});
</script>


<div class="section-title">About Me</div>

<div class="aboutme">
<div class="inside-block" style="width: 150px">
<img src="assets/abdulkadir_with_shirt.jpg" style=" width: 110px; height: 110px; border-radius: 50%; margin: 10px; object-fit: cover; object-position: center right;">
<div style="margin-top: 10px; display: block; padding-left: 15px;">
<a href="https://github.com/abdcelikkanat/"><img src="assets/icons/icons8-github-48.png" style="height:24px; width:24px; margin-left: 5px;"></a>
<a href="https://www.linkedin.com/in/abdulkadir-%C3%A7elikkanat-65a759104/"><img src="assets/icons/icons8-linkedin-48.png" style="height:24px; width:24px; margin-left: 5px;"></a>
<a href="https://twitter.com/abdcelikkanat"><img src="assets/icons/icons8-twitter-48.png" style="height:24px; width:24px; margin-left: 5px;"></a>
</div>
</div>
<div class="inside-block" style="width: 525px; text-align: center; margin-bottom: 0px; font-size: 20px; letter-spacing: 3px; color:#555;">Abdulkadir Çelikkanat‬</div>
<div class="inside-block" style="width: 325px; background-color: #999999; height: 1px; margin: 5px auto 15px 100px;"></div>
<div class="inside-block" style="width: 525px; text-align: justify;">
I'm currently a Ph.D. student at <a href="http://cvn.centralesupelec.fr/">Centre for Visual Computing</a> laboratory of CentraleSupélec, Paris-Saclay University under the supervision of Assistant Prof. <a href="http://fragkiskos.me/">Fragkiskos D. Malliaros</a> and Prof. <a href="http://vision.mas.ecp.fr/personal.html">Nikos Paragios</a>. Before my Ph.D. studies, I received my Bachelor degree in Mathematics and my Master's degree in Computer Engineering from Boğaziçi University, where I worked with Prof. <a href="https://www.cmpe.boun.edu.tr/~cemgil/">Ali Taylan Cemgil</a>. 
<br><br>
My research mainly focuses on the analysis of graph-structured data. In particular, I am interested in graph representation learning with applications such as link prediction, classification, data visualization and network analysis. 
</div>
</div>





<div class="section-title" style="margin-top: 25px;">Publications</div>

<div class="article-year">2021</div>

<div class="article-block">
    <div class="article-left-bar"></div>
    <div style="float:left; display:inline-block; padding-left: 5px">
        <div class="article-inline-title">Topic-Aware Latent Models for Representation Learning on Networks</div>
        <div class="article-inline-authors">Abdulkadir Çelikkanat and Fragkiskos D. Malliaros.</div>
        <div class="article-inline-conference">Pattern Recognition Letters, Advances in graph-based pattern recognition, Elsevier, 2021.</div>
        <div class="article-inline-reference">[Doi: <a href="https://doi.org/10.1016/j.patrec.2021.01.006">LINK</a>] [Code: <a href="https://abdcelikkanat.github.io/projects/TNE/">LINK</a>]</div>
    </div>
</div>

<div class="article-block">
    <div class="article-left-bar"></div>
    <div style="float:left; display:inline-block; padding-left: 5px">
        <div class="article-inline-title">NodeSig: Random Walk Diffusion meets Hashing for Scalable Graph Embeddings</div>
        <div class="article-inline-authors">Abdulkadir Çelikkanat, Apostolos N. Papadopoulos and Fragkiskos D. Malliaros.</div>
        <div class="article-inline-conference">Manuscript</div>
        <div class="article-inline-reference">[arXiv: <a href="https://arxiv.org/abs/2010.00261">PDF</a>] [Code: <a href="https://github.com/abdcelikkanat/nodesigfinal/">LINK</a>]</div>
    </div>
</div>

<div class="article-year">2020</div>

<div class="article-block">
    <div class="article-left-bar"></div>
    <div style="float:left; display:inline-block; padding-left: 5px">
        <div class="article-inline-title">Exponential Family Graph Embeddings</div>
        <div class="article-inline-authors">Abdulkadir Çelikkanat and Fragkiskos D. Malliaros.</div>
        <div class="article-inline-conference">AAAI Conference on Artificial Intelligence (AAAI), 3357-3364, New York City, New York, 2020. </div>
        <div class="article-inline-reference">[Doi: <a href="https://doi.org/10.1609/aaai.v34i04.5737">LINK</a>] [arXiv: <a href="https://arxiv.org/abs/1911.09007">PDF</a>] [Poster: <a href="assets/posters/Exponential_Family_Graph_Embeddings__Poster__AAAI20_.pdf">LINK</a>] [Code: <a href="https://abdcelikkanat.github.io/projects/EFGE/">LINK</a>]</div>
    </div>
</div>

<div class="article-year">2019</div>

<div class="article-block">
    <div class="article-left-bar"></div>
    <div style="float:left; display:inline-block; padding-left: 5px">
        <div class="article-inline-title">Learning Node Embeddings with Exponential Family Distributions</div>
        <div class="article-inline-authors">Abdulkadir Çelikkanat and Fragkiskos D. Malliaros.</div>
        <div class="article-inline-conference">NeurIPS Graph Representation Learning Workshop (NeurIPS-GRL), Vancouver, Canada, 2019.</div>
        <div class="article-inline-reference">[arXiv: <a href="https://arxiv.org/abs/1911.09007">PDF</a>] [Poster: <a href="assets/posters/Kernel_Node_Embeddings_Poster_.pdf">LINK</a>] [Code: <a href="https://abdcelikkanat.github.io/projects/EFGE/">LINK</a>]</div>
    </div>
</div>

<div class="article-block">
    <div class="article-left-bar"></div>
    <div style="float:left; display:inline-block; padding-left: 5px">
        <div class="article-inline-title">Kernel Node Embeddings</div>
        <div class="article-inline-authors">Abdulkadir Çelikkanat and Fragkiskos D. Malliaros.</div>
        <div class="article-inline-conference">7th IEEE Global Conference on Signal and Information Processing (GlobalSIP), Ottawa, Canada, November 2019.</div>
        <div class="article-inline-reference">[Doi: <a href="https://doi.org/10.1109/GlobalSIP45357.2019.8969363">LINK</a>] [arXiv: <a href="https://arxiv.org/abs/1909.03416">PDF</a>] [Code: <a href="https://abdcelikkanat.github.io/projects/kernelNE/">LINK</a>]</div>
    </div>
</div>

<div class="article-year">2018</div>

<div class="article-block">
    <div class="article-left-bar"></div>
    <div style="float:left; display:inline-block; padding-left: 5px">
        <div class="article-inline-title">TNE: A Latent Model for Representation Learning on Networks</div>
        <div class="article-inline-authors">Abdulkadir Çelikkanat and Fragkiskos D. Malliaros.</div>
        <div class="article-inline-conference">NeurIPS Relational Representation Learning Workshop (NeurIPS-R2L), Montréal, Canada, 2018.</div>
        <div class="article-inline-reference">[arXiv: <a href="http://fragkiskos.me/papers/TNE_NeurIPS_R2L_2018.pdf">PDF</a>] [Poster: <a href="assets/posters/NIPS_Workshop_TNE_Poster.pdf">LINK</a>] [Code: <a href="https://abdcelikkanat.github.io/projects/TNE/">LINK</a>]</div>
    </div>
</div>

<div class="article-year">2017</div>

<div class="article-block">
    <div class="article-left-bar"></div>
    <div style="float:left; display:inline-block; padding-left: 5px">
        <div class="article-inline-title">Sampling methods for random simple and bipartite graphs with prescribed degree sequences </div>
        <div class="article-inline-authors">Abdulkadir Çelikkanat</div>
        <div class="article-inline-conference">Master's Thesis, 2017.</div>
        <div class="article-inline-reference">[Thesis: <a href="https://tez.yok.gov.tr/UlusalTezMerkezi/TezGoster?key=vbVkXe1KChYWNElr1MuLZusWwBD6YW1NT8jZCZCOPYKWun1pa2-LirYGE9m9uS7P">PDF</a>] [Presentation: <a href="https://drive.google.com/file/d/0B7PcipLnfc9RUUpoa3k3WnFJRU0/view?usp=sharing">LINK</a>] [Code: <a href="https://github.com/abdcelikkanat/sacorg">LINK</a>]</div>
    </div>
</div>



<br><br>

<div class="section-title" style="margin-top: 25px;">Teaching</div>

<div class="course-block">
    <div class="course-left-bar"></div>
    <div style="float: left; display: inline-block; padding-left: 5px">
        <div class="course-inline-title">ST2: Mathematical Modeling of Propagation Phenomena - Propagation on Graphs</div>
        <div class="course-inline-details">1st year, CentraleSupélec, Winter 2020</div>
        <div class="course-inline-role">Teaching Assistant</div>
    </div>
</div>

<div class="course-block">
    <div class="course-left-bar"></div>
    <div style="float: left; display: inline-block; padding-left: 5px">
        <div class="course-inline-title">Machine Learning on Networks, Teaching assistant</div>
        <div class="course-inline-details">AI Summer School Programme, CentraleSupélec, Summer 2019</div>
        <div class="course-inline-role">Teaching Assistant</div>
    </div>
</div>

<div class="course-block">
    <div class="course-left-bar"></div>
    <div style="float: left; display: inline-block; padding-left: 5px">
        <div class="course-inline-title">ST2: Mathematical Modeling of Propagation Phenomena - Propagation on Graphs</div>
        <div class="course-inline-details">1st year, CentraleSupélec, Winter 2019</div>
        <div class="course-inline-role">Teaching Assistant</div>
    </div>
</div>

<div class="course-block">
    <div class="course-left-bar"></div>
    <div style="float: left; display: inline-block; padding-left: 5px">
        <div class="course-inline-title">NGSA: Network Science Analytics, Applied Math</div>
        <div class="course-inline-details">3rd year, CentraleSupélec, M.Sc. in DSBA, and M.Sc. in AI, Winter 2019</div>
        <div class="course-inline-role">Teaching Assistant</div>
    </div>
</div>

<div class="course-block">
    <div class="course-left-bar"></div>
    <div style="float: left; display: inline-block; padding-left: 5px">
        <div class="course-inline-title">NGSA: Network Science Analytics, Applied Math</div>
        <div class="course-inline-details">3rd year, CentraleSupélec, M.Sc. in DSBA, and M.Sc. in DSBA, Spring 2018</div>
        <div class="course-inline-role">Teaching Assistant</div>
    </div>
</div>

<div class="section-title" style="margin-top: 25px;">Reviewer Activities</div>

<div class="review-block">
    <div class="review-left-bar"></div>
    <div style="float: left; display: inline-block; padding-left: 5px">
        <div class="review-inline-title">International Conference on Learning Representations (ICLR)</div>
        <div class="review-inline-year">2021</div>
        <div class="review-inline-role">Sub-reviewer</div>
    </div>
</div>

<div class="review-block">
    <div class="review-left-bar"></div>
    <div style="float: left; display: inline-block; padding-left: 5px">
        <div class="review-inline-title">AAAI Conference on Artificial Intelligence (AAAI)</div>
        <div class="review-inline-year">2020</div>
        <div class="review-inline-role">Sub-reviewer</div>
    </div>
</div>

<div class="review-block">
    <div class="review-left-bar"></div>
    <div style="float: left; display: inline-block; padding-left: 5px">
        <div class="review-inline-title">ECML-PKDD</div>
        <div class="review-inline-year">2020</div>
        <div class="review-inline-role">Reviewer</div>
    </div>
</div>

<div class="review-block">
    <div class="review-left-bar"></div>
    <div style="float: left; display: inline-block; padding-left: 5px">
        <div class="review-inline-title">The Web Conference</div>
        <div class="review-inline-year">2020</div>
        <div class="review-inline-role">Sub-reviewer</div>
    </div>
</div>

<div class="review-block">
    <div class="review-left-bar"></div>
    <div style="float: left; display: inline-block; padding-left: 5px">
        <div class="review-inline-title">International Conference on Artificial Neural Networks (ICANN)</div>
        <div class="review-inline-year">2019</div>
        <div class="review-inline-role">Co-reviewer</div>
    </div>
</div>

<div class="review-block">
    <div class="review-left-bar"></div>
    <div style="float: left; display: inline-block; padding-left: 5px">
        <div class="review-inline-title">The Web Conference</div>
        <div class="review-inline-year">2019</div>
        <div class="review-inline-role">Sub-reviewer</div>
    </div>
</div>

<div class="review-block">
    <div class="review-left-bar"></div>
    <div style="float: left; display: inline-block; padding-left: 5px">
        <div class="review-inline-title">International Conference on Complex Networks and their Applications</div>
        <div class="review-inline-year">2018</div>
        <div class="review-inline-role">Sub-reviewer</div>
    </div>
</div>

<div class="review-block">
    <div class="review-left-bar"></div>
    <div style="float: left; display: inline-block; padding-left: 5px">
        <div class="review-inline-title">Neural Information Processing Systems (NeurIPS)</div>
        <div class="review-inline-year">2018</div>
        <div class="review-inline-role">Sub-reviewer</div>
    </div>
</div>

<div class="section-title" style="margin-top: 25px;">Contact</div>
<div class="contact-block">
    <div class="contact-subblock">
        <div class="contact-title">E-mail:</div>
        <div class="contact-info"><a href="mailto:abdcelikkanat@gmail.com">abdcelikkanat@gmail.com</a><br><a href="mailto:abdulkadir.celikkanat@centralesupelec.fr">abdulkadir.celikkanat@centralesupelec.fr</a><br><a href="mailto:abdulkadir.celikkanat@centralesupelec.fr">abdulkadir.celikkanat@inria.fr</a></div>
    </div>
    <div class="contact-subblock">
        <div class="contact-title">Address:</div>
        <div class="contact-info">Bâtiment Bouygues, Centre for Visual Computing<br>CentraleSupélec, 8 rue Joliot-Curie<br>91190 Gif-sur-Yvette, France</div>
    </div>
</div>
