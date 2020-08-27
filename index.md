---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: SISSAstyle #default #home
katex: true
---

$$x^2.$$

<h3>
I am a mathematician working in the field of {{ "nonlinear integrable equations" | capitalize }}
and {{" orthogonal polynomials" | capitalize}}.
</h3>

<h3> My CV can be found here: <a href="data/docs/Minakov-CV_190515.pdf">CV</a>
</h3>


<h3> My publications can be found here : <a href="Publications">Publications</a> </h3>

<style>
* {
  box-sizing: border-box;
}

/* Create two unequal columns that floats next to each other */
.column {
  float: left;
  padding: 10px;
  <!-- height:-->  300px; /* Should be removed. Only for demonstration */ 
}

.left {
  width: 40%;
}

.right {
  width: 60%;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>

<div class="row">
  <div class="column left" style="background-color:#aaa;">
    <h2>{{ "Position" | upcase }}</h2>
    <p>Postdoc <br>
	IRMP
	<br>UCL</p>
  </div>
  <div class="column right" style="background-color:#bbb;">
    <h2>{{ "address" | upcase }}</h2>
    <p>Université catholique de Louvain <br> Institut de Recherche en Mathématique et Physique
	<br>
	Chemin du Cyclotron 2  <br> B-1348 Louvain-La-Neuve Belgium </p>
  </div>
</div>



<style>
* {
  box-sizing: border-box;
}

/* Create two unequal columns that floats next to each other */
.column {
  float: left;
  padding: 10px;
  <!-- height:-->  300px; /* Should be removed. Only for demonstration */ 
}

.left {
  width: 50%;
}

.right {
  width: 50%;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>

<div class="row">
  <div class="column left" style="background-color:#ccc;">
    <h2>{{ "Research Interests" | upcase }}</h2>
    <p> Integrable equations <br>
	Asymptotic analysis
	<br>Riemann-Hilbert problems <br> Orthogonal Polynomials </p>
  </div>
  <div class="column right" style="background-color:#ddd;">
    <h2>{{ "Contact " | upcase }}</h2>
    <p>Bureau b327 <br> Phone: +32 (0) 10 47 31 53
	<br> Email: oleksandr (dot) minakov (at) uclouvain (dot) be </p>
  </div>
</div>



