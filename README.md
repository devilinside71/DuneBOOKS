# DuneBOOKS


## Sigil version

Old good: 2.6.0


## TODO

Angol gyűjtemények bontása könyvekre

Magyar megcsinálás

Sigil Regex
convert
<h2 ...><a ...>TEXT</a></h2>
to
<h2 class="part_title">TEXT</h2>

<h2\b[^>]*>\s*<a\b[^>]*>(.*?)</a>\s*</h2>

<h2 class="part_title">\1</h2>

----------------------
<p class="class_s5X7-0">\s*<a\b[^>]*>(.*?)</a>\s*</p>
<p class="part_title">\1</p><br />

----------------------
<p class="class_s5X9-0">\s*<a\b[^>]*>(.*?)</a>\s*</p>
<p class="part_title">\1</p><br />


<p\b[^>]*>\s*<a\b[^>]*>(.*?)</a>\s*</p>
<p class="part_title">\1</p>




.part_title {
  font-family: 'Dune Rise';
  font-size: 1.6em;
  font-weight: 700;
  margin-bottom: 0;
  margin-top: 0;
  text-align: center;
}
.part_subtitle {
  font-family: 'Dune Rise';
  font-size: 1.2em;
  font-weight: 700;
  margin-bottom: 0;
  margin-top: 0;
  text-align: center;
}
.imgcenter {
  display: block;
  text-align: center;
}
.class_s1A1U, .class_s181K-1 {
  margin-bottom: 0;
  margin-top: 1.49375em;
  text-align: justify;
}