---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}



Education
======
* October 2015 – November 2019 PhD Degree in materials science at Institut de Ciència de Materials de Barcelona (ICMAB-CSIC) - Universitat Autònoma de Barcelona (UAB) (Barcelona, Spain)
<br/>Thesis: [Artificial Synapses based on the Photoconductance of LaAlO3/SrTiO3 Quantum Wells](https://dialnet.unirioja.es/servlet/dctes?codigo=270736)
<br/>Supervisor: Dr. Gervasi HERRANZ CASABONA
* March 2011 – June 2014 master’s degree in Condensed Matter Physics at Shanghai University (SHU) (Shanghai, China)
<br/>Thesis: Study on electrotransport properties of Graphene Ferromagnetic/Insulator/Superconducting junction
<br/>Supervisor: Prof. Shiping ZHOU

Work experience
======
* February 2021 – Present Italian National Research Council- SuPerconductors, oxides and other INnovative materials and devices (CNR-SPIN)
<br/>Fixed-term researcher (Post-Doc) in the framework of the TOPSPIN (“two-dimensional oxides platform for spin-orbitronics nanotechnology”)
<br/>Topic: Experimental methods for the study of the low temperature physics of transition metal oxides two- dimensional electron gas for applications in quantum technologies

* May 2020 – December 2020 FACULTY OF PHYSICS - Universitat Autònoma de Barcelona
POSTDOC IN PROF. JORDI SORT’S GROUP May 2020 - Sep. 2020
<br/>Fixed-term researcher (Post-Doc) in the framework of the ERC project ‘SPIN-PORICS MERGING
<br/>NANOPOROUS MATERIALS WITH ENERGY-EFFICIENT SPINTRONICS’
  * Magnetoelectricity in FeGa/PVDF multiferroic bilayer
  * Magnetoionics (Voltage-driven motion of nitrogen/oxygen ions)


Skills
======
Along my study and job careers I gained massive familiarity with the following techniques and instruments:
1. Deposition systems for oxide/metallic thin films such as: pulsed laser deposition, sputtering, and evaporation.
2. UV photolithography and mask design
3. Electrical transport characterization
4. Impedance measurement
5. Confocal Optical microscopy, MOKE (Magneto optical Kerr Effect)
6. Magnetic and (magneto)transport measurements for oxide thin films (PPMS and Vibrating-sample magnetometry (VSM))
7. Multimeter, oscilloscope and function generator
8. Programming:
Matlab (Data analysis, numerical calculations of tight-binding models, ...), Python, LATEX, LabVIEW, Labwindows…
9. Data analysis and modeling,
10. Other software: Originlab, Igor, Vesta, SketchUp, Adobe illustration, Inkscape, CleWin4, Latex animation, Gwyddion...
11. Languages: Chinese, English


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Learning
======
  <ul>{% for post in site.learning %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service and leadership
======
* Currently signed in to 43 different slack teams -->

<!-- <div id="content">
     <h3>Hello, this is a H3 tag</h3>

    #<p>a pararaph</p>
</div> -->
$('#downloadPDF').click(function () {
    domtoimage.toPng(document.getElementById('content2'))
      .then(function (blob) {
          var pdf = new jsPDF('l', 'pt', [$('#content2').width(), $('#content2').height()]);
          pdf.addImage(blob, 'PNG', 0, 0, $('#content2').width(), $('#content2').height());
          pdf.save("test.pdf");
      });
});
