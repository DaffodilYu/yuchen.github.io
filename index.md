# Quantum Garden/琅嬛福地

Building up...


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

### Physics Learning
- [blog on Computational physics](https://compphys.go.ro/)
- [MIT EE & CS lectures](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/)
- [MIT Physics Lectures](https://ocw.mit.edu/courses/physics/) 
- [Quantum Physics](https://www2.ph.ed.ac.uk/~gja/qp/) This is a course on Quantum Mechanics written and delivered by Prof. Graeme Ackland at the University of Edinburgh between 2006 and 2011.


#### Quantum Field Theory
- [Cambridge QFT by David Tong](https://www.damtp.cam.ac.uk/user/tong/qft.html)
- [QFT by Michael Luke](https://www.physics.utoronto.ca/~luke/PHY2403F/Homepage.html)
- [Fields   by Warren Siegel](http://insti.physics.sunysb.edu/~siegel/errata.shtml)
- [Quantum Condensed Matter Field Theory by Ben Simons](http://www.tcm.phy.cam.ac.uk/~bds10/tp3.html)
- [QFT by Jacob Linder](https://sites.google.com/view/lindergroup/qft?authuser=0)

#### density functional theory
- [Modeling materials using density functional theory](http://kitchingroup.cheme.cmu.edu/dft-book/dft.html) by John Kitchin




### Language
#### English
- [Synonym](https://www.thesaurus.com/)

### Software learning
#### OOMMF
- [Talk: Micromagnetics and OOMMF](https://www.spintalks.org/tutorials)

### Journal and thesis
- [PhD thesis in Catalunia Spain](https://www.tdx.cat/)
- [PhD thesis in UAB](https://ddd.uab.cat/)
- [Cambridge University press](https://www.cambridge.org/)

### Scholar webpage
- [Gervasi Herranz](https://gervasi-herranz.blog/)
- [Shanshan wang](https://shannwang.github.io/shanshanwang/index.html)
> Her research interests: Econophysics, Market Microstructure, Price Impact, Complex Systems, Traffic Networks, Data Science, Machine Learning

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
```
expGraph type:=png path:="C:\xx\xx\xx\xx" filename:="TEST" ;
```
### Igor

### Python

## Publications
1. Y. Chen, Y. Lechaux, B. Casals, B. Guillet, A. Minj, J. Gázquez, L. Méchin, and G. Herranz, Photoinduced Persistent Electron Accumulation and Depletion in LaAlO3/SrTiO3 Quantum Wells, [**Phys. Rev. Lett.** 2020, 124, 246804](https://doi.org/10.1103/PhysRevLett.124.246804).
2. Y. Chen, B. Casals, and G. Herranz, Plasticity of Persistent Photoconductance of Amorphous LaAlO3/SrTiO3 Interfaces under Varying Illumination Conditions, ACS Appl. Electron. Mater. 1, 810 (2019).
3. Y. Chen, B. Casals, F. Sánchez, and G. Herranz, Solid-State Synapses Modulated by Wavelength-Sensitive Temporal Correlations in Optic Sensory Inputs, ACS Appl. Electron. Mater. 1, 1189 (2019).
4. Y. Chen, A. Nicolenco, P. Molet, A. Mihi, E. Pellicer, and J. Sort, Magneto-Ionic Suppression of Magnetic Vortices, Sci. Technol. Adv. Mater. 22, 972 (2021).
5. R. A. Maniyara, C. Graham, B. Paulillo, Y. Bi, Y. Chen, G. Herranz, D. E. Baker, P. Mazumder, G. Konstantatos, and V. Pruneri, Highly Transparent and Conductive ITO Substrates for near Infrared Applications, APL Mater. 9, 021121 (2021).
6. A. Nicolenco, Y. Chen, N. Tsyntsaru, H. Cesiulis, E. Pellicer, and J. Sort, Mechanical, Magnetic and Magnetostrictive Properties of Porous Fe-Ga Films Prepared by Electrodeposition, Mater. Des. 208, 109915 (2021).







