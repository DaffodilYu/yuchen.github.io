# Quantum Garden/琅嬛福地

[Building up...](https://github.com/DoctorYuChen/DoctorYuchen.github.io/edit/gh-pages/index.md)


## Interesting links

### Research relevance
- [QUANtum Technologies with 2D-OXides](http://quantox.spin.cnr.it/)


### Experiments
- [Photolithography and e-beam lithography recipes](https://nano.physics.leidenuniv.nl/dokuwiki/doku.php?id=resist_and_e-beam_recipes)
- [Writing a lab report](https://www.jyu.fi/science/en/physics/studies/student-laboratory/writing-a-lab-report)

### Computational physics
- [Understanding Molecular Simulations](http://www.cchem.berkeley.edu/chem195/index.html)
> you will find functions and code samples in MATLAB that will help you get started in the world of molecular simulations.
- [Nanonub](https://nanohub.org/)

### Solid Physics
- [Crystal structures](https://www.tulane.edu/~sanelson/eens211/index.html#Announcements) Prof. Stephen A. Nelson. There are many PDFs on the crystal structures.
- [Coordination Chemistry](http://wwwchem.uwimona.edu.jm/courses/IC10Kout.html) by Prof. R.J. Lancashire.
- [Dynamic periodic table](https://ptable.com/#Properties)

### Physics Learning
- [blog on Computational physics](https://compphys.go.ro/)
- [MIT EE & CS lectures](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/)
- [MIT Physics Lectures](https://ocw.mit.edu/courses/physics/) 
- [Quantum Physics](https://www2.ph.ed.ac.uk/~gja/qp/) This is a course on Quantum Mechanics written and delivered by Prof. Graeme Ackland at the University of Edinburgh between 2006 and 2011.
- [Physics library](https://phys.libretexts.org/)
> This Living Library is a principal hub of the LibreTexts project, which is a multi-institutional collaborative venture to develop the next generation of open-access texts to improve postsecondary education at all levels of higher learning.


#### Quantum Field Theory
- [Cambridge QFT by David Tong](https://www.damtp.cam.ac.uk/user/tong/qft.html)
- [QFT by Michael Luke](https://www.physics.utoronto.ca/~luke/PHY2403F/Homepage.html)
- [Fields   by Warren Siegel](http://insti.physics.sunysb.edu/~siegel/errata.shtml)
- [Quantum Condensed Matter Field Theory by Ben Simons](http://www.tcm.phy.cam.ac.uk/~bds10/tp3.html)
- [QFT by Jacob Linder](https://sites.google.com/view/lindergroup/qft?authuser=0)

#### Density functional theory
- [Modeling materials using density functional theory](http://kitchingroup.cheme.cmu.edu/dft-book/dft.html) by John Kitchin

### Science for Public
- [Chemical for kids](http://www.chem4kids.com/index.html)

### Language
#### English
- [Synonym](https://www.thesaurus.com/)

### Software learning
#### OOMMF
- [Talk: Micromagnetics and OOMMF](https://www.spintalks.org/tutorials)

### Journal and thesis
#### Journal
- [APS Physics](https://www.aps.org/)
- [Applied electronic materials](https://pubs.acs.org/journal/aaembp) and [author guidelines](https://publish.acs.org/publish/author_guidelines?coden=aaembp#preparing_graphics)
- [PhD thesis in Catalunia Spain](https://www.tdx.cat/)
- [PhD thesis in UAB](https://ddd.uab.cat/)
- [Open Access Theses and Dissertations](https://oatd.org/)
- [Book free download](https://b-ok.org/) Just for checking, please respect for the copyright.
- [Cambridge University Press](https://www.cambridge.org/)
- [academia](https://www.academia.edu/) Here you can download some papers and books.

### Data Science and machine learning
- [Towards Data Science](https://towardsdatascience.com/)
- [Christopher Olah](http://colah.github.io/) He is working on reverse engineering artificial neural networks into human understandable algorithms.
- [机器之心](https://cloud.tencent.com/developer/column/2713)
- [Synced-英文机器之心](https://syncedreview.com/)

### Scholar webpage
- [Gervasi Herranz](https://gervasi-herranz.blog/)
> Physicist, Condensed Matter & Photonics at ICMAB-CSIC, Barcelona
> Research interests: (i) [Nanophotonics](https://gherranz.wordpress.com/2017/08/25/multifunctional-photonics/). (ii) [Oxide Quantum Wells](https://gherranz.wordpress.com/2017/08/25/2d-electronic-systems-the-case-of-laalo3srtio3/).
- [Shanshan Wang](https://shannwang.github.io/shanshanwang/index.html)
> Her research interests: Econophysics, Market Microstructure, Price Impact, Complex Systems, Traffic Networks, Data Science, Machine Learning
- [Olivier Fruchart](http://fruchart.eu/olivier/links/links.html) He is a senior scientist and deputy director at SPINTEC Laboratory, Grenoble, France. SPINTEC is devoted to spin electronics. On his website there are many intereting links.
- [Prof. Xiaodong Yang](https://web.mst.edu/~yangxia/index.html) Nanoscale Optics Laboratory, Prof. Xiaodong Yang, Department of Mechanical and Aerospace Engineering,Missouri University of Science and Technology

### Looking for a job
- [Jobs in Science](https://jobs.sciencecareers.org/)


## Software/Code
### Matlab
test： Double-slit interference 
```matlab
clear all
ym = 1.25; y = linspace(-ym,ym,101);
d = 2; z = 1000; lambda = 5e-4;
L1 = sqrt((y-1).^2+z^2); L2 = sqrt((y+1).^2+z^2);
phi = 2*pi*(L2-L1)/lambda;
I = 4*(cos(phi/2)).^2;
subplot(2,1,1)
plot(y,I)
axis([-1.25 1.25 0 4])
subplot(2,1,2)
B = I*255/5;
image(B);
colormap(gray(255));
```
### Originlab
Save the figure command.
```Labtalk
expGraph type:=png path:="C:\xx\xx\xx\xx" filename:="TEST" ;
```
### Adobe Illustrator


### Igor

### Latex

### Python


## Reading
1. [Productivity Books](https://www.lifehack.org/articles/productivity/30-best-books-productivity-you-should-read.html)
2. 
## Publications
1. Y. Chen, Y. Lechaux, B. Casals, B. Guillet, A. Minj, J. Gázquez, L. Méchin, and G. Herranz, Photoinduced Persistent Electron Accumulation and Depletion in LaAlO3/SrTiO3 Quantum Wells, [**Phys. Rev. Lett.** 2020, 124, 246804](https://doi.org/10.1103/PhysRevLett.124.246804).
2. Y. Chen, B. Casals, and G. Herranz, Plasticity of Persistent Photoconductance of Amorphous LaAlO3/SrTiO3 Interfaces under Varying Illumination Conditions, ACS Appl. Electron. Mater. 1, 810 (2019).
3. Y. Chen, B. Casals, F. Sánchez, and G. Herranz, Solid-State Synapses Modulated by Wavelength-Sensitive Temporal Correlations in Optic Sensory Inputs, ACS Appl. Electron. Mater. 1, 1189 (2019).
4. Y. Chen, A. Nicolenco, P. Molet, A. Mihi, E. Pellicer, and J. Sort, Magneto-Ionic Suppression of Magnetic Vortices, Sci. Technol. Adv. Mater. 22, 972 (2021).
5. R. A. Maniyara, C. Graham, B. Paulillo, Y. Bi, Y. Chen, G. Herranz, D. E. Baker, P. Mazumder, G. Konstantatos, and V. Pruneri, Highly Transparent and Conductive ITO Substrates for near Infrared Applications, APL Mater. 9, 021121 (2021).
6. A. Nicolenco, Y. Chen, N. Tsyntsaru, H. Cesiulis, E. Pellicer, and J. Sort, Mechanical, Magnetic and Magnetostrictive Properties of Porous Fe-Ga Films Prepared by Electrodeposition, Mater. Des. 208, 109915 (2021).







