# Quantum Garden/琅嬛福地

[Building up...](https://github.com/DoctorYuChen/DoctorYuchen.github.io/edit/gh-pages/index.md)


## Interesting links

### Research relevance
- [QUANtum Technologies with 2D-OXides](http://quantox.spin.cnr.it/)


### Experiments
- [Photolithography and e-beam lithography recipes](https://nano.physics.leidenuniv.nl/dokuwiki/doku.php?id=resist_and_e-beam_recipes)
- [Writing a lab report](https://www.jyu.fi/science/en/physics/studies/student-laboratory/writing-a-lab-report)
- [Basics of Electrochemical Impedance Spectroscopy](https://www.gamry.com/application-notes/EIS/basics-of-electrochemical-impedance-spectroscopy/)
- [Resources for Electrochemistry](http://www.consultrsr.net/index.htm)
- [ELectronics tutorials](https://www.electronics-tutorials.ws/)
- [Schottky diode](http://www.physics-and-radio-electronics.com/electronic-devices-and-circuits/semiconductor-diodes/schottkydiode.html)
- [Deep-Level Transient Spectroscopy System](http://www.phystech.de/products/dlts/dlts.htm)
- [Unit Conversion Table 单位换算](http://www.csgnetwork.com/converttable.html)
- [Zurich instruments](https://www.zhinst.com/europe/en)

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
> [How to Learn Math and Physics](https://math.ucr.edu/home/baez/books.html#classical_mechanics) by John Baez


#### Quantum Field Theory
- [Cambridge QFT by David Tong](https://www.damtp.cam.ac.uk/user/tong/qft.html)
- [QFT by Michael Luke](https://www.physics.utoronto.ca/~luke/PHY2403F/Homepage.html)
- [Fields   by Warren Siegel](http://insti.physics.sunysb.edu/~siegel/errata.shtml)
- [Quantum Condensed Matter Field Theory by Ben Simons](http://www.tcm.phy.cam.ac.uk/~bds10/tp3.html)
- [QFT by Jacob Linder](https://sites.google.com/view/lindergroup/qft?authuser=0)
- [From Griffiths to Peskin: a lit review for beginners](https://fliptomato.wordpress.com/2006/12/30/from-griffiths-to-peskin-a-lit-review-for-beginners/)

#### Group theory
- [California Institute of Technology Prof. Xie Chen](https://www.its.caltech.edu/~xcchen/courses/physics129.html)

#### Density functional theory
- [Modeling materials using density functional theory](http://kitchingroup.cheme.cmu.edu/dft-book/dft.html) by John Kitchin

### Science for Public
- [Chemical for kids](http://www.chem4kids.com/index.html)

### Others
- [The Dark Energy](https://www.darkenergysurvey.org/)

### Language
#### English
- [Synonym](https://www.thesaurus.com/)

### Software learning
#### OOMMF
- [Talk: Micromagnetics and OOMMF](https://www.spintalks.org/tutorials)

### Journal/thesis/Conference
#### Journal
- [APS Physics](https://www.aps.org/)
- [Applied electronic materials](https://pubs.acs.org/journal/aaembp) and [author guidelines](https://publish.acs.org/publish/author_guidelines?coden=aaembp#preparing_graphics)
- [PhD thesis in Catalunia Spain](https://www.tdx.cat/)
- [PhD thesis in UAB](https://ddd.uab.cat/)
- [Open Access Theses and Dissertations](https://oatd.org/)
- [Book free download](https://b-ok.org/) Just for checking, please respect for the copyright.
- [Cambridge University Press](https://www.cambridge.org/)
- [academia](https://www.academia.edu/) Here you can download some papers and books.

#### Conference
-[European Materials Research Society](https://www.european-mrs.com/)

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
Save the figure using Labtalk script
```Labtalk
expGraph type:=png path:="C:\xx\xx\xx\xx" filename:="TEST" ;
```
**Figure size**

Single column(like ACS maximum 85mm):  42 mm x 40 mm 

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


# 诗词格律

## 卜算子

正体，双调四十四字，前后段各四句、两仄韵。以苏轼《卜算子·黄州定慧院寓居作》为代表。此若石词之多押两韵，徐、黄、张、杜四词之添字，皆变体也。 苏词别首前段第二句“长忆吴山好”，“长”字平声。

格律对照例词：《卜算子·黄州定慧院寓居作》

中中中中平，中仄平平**仄**。中仄平平中中中？中仄平平**仄**。

*缺月挂疏桐，漏断人初**静**。谁见幽人独往来？缥缈孤鸿**影**。*

中中中中平，中仄平平**仄**。中仄平平中中中，仄仄平平**仄**。

*惊起却回头，有恨无人**省**。拣尽寒枝不肯栖，寂寞沙洲**冷**。*





## 点绛唇

格律对照例词：《[点绛唇·荫绿围红](https://baike.baidu.com/item/点绛唇·荫绿围红/22736767)》

中仄平平，中平中仄平平**仄**。中平中**仄**，中仄平平**仄**。

*荫绿围红，飞琼家在桃源****住\****。画桥当****路\****，临水开朱****户\****。*

中仄中平，中仄平平**仄**。中中**仄**，中平中**仄**，中仄平平**仄**。

*柳径春深，行到关情****处\****。颦不****语\****，意凭风****絮\****，吹向郎边****去\****。*



## 青玉案

**正体**

格律对照例词：《青玉案·淩波不过横塘路》

中平中仄平平**仄**，仄中仄、平平**仄**，中仄中平平仄**仄**？中平中仄，中平中**仄**，中仄平平**仄**。

*淩波不过横塘****路\****，但目送、芳尘****去\****。锦瑟年华谁与****度\****？月楼花院，绮窗朱****户\****，惟有春知****处\****。*

中平中仄平平**仄**，中仄平平仄平**仄**。中仄中平平仄**仄**？中平中仄，中平中**仄**，中仄平平**仄**。

*碧云冉冉蘅皋****暮\****，彩笔空题断肠****句\****。试问闲愁知几****许\****？一川烟草，满城风****絮\****，梅子黄时****雨\****。*



## 生查子

**正体**

格律对照例词：《生查子·侍女动妆奁》

中中中中中，中仄平平**仄**。中中仄中平，中仄平平**仄**。

*侍女动妆奁，故故惊人****睡\****。那知本未眠，背面偷垂****泪\****。*

中中中中平，中仄平平**仄**。中仄仄平平，中中中平**仄**。

*懒卸凤凰钗，羞入鸳鸯****被\****。时复见残灯，和烟坠金****穗\****。*



## 醉花间

**正体**

格律对照词：《醉花间·深相忆》

平平仄。仄平仄。平仄平平仄。平仄仄平平，中仄平平仄。

*深相忆。莫相忆。相忆情难极。银汉是红墙，一带遥相隔。*

中中中中仄。中中平中仄。平中仄中平，中仄平平仄。

*金盘珠露滴。两岸榆花白。风摇玉佩清，今夕为何夕？*



## 踏莎行

**正体**

格律对照例词：《踏莎行·细草愁烟》

中仄平平，中平中**仄**。中平中仄平平**仄**。中平中仄仄平平，中平中仄平平**仄**

*细草愁烟，幽花怯****露\****。凭阑总是销魂****处\****。日高深院静无人，时时海燕双飞****去\****。*

中仄平平，中平中**仄**。中平中仄平平**仄**。中平中仄仄平平，中平中仄平平**仄**。

*带缓罗衣，香残蕙****炷\****。天长不禁迢迢****路\****。垂杨只解惹春风，何曾系得行人****住\****。*



## 醉花阴

**正体**

格律对照例词：《醉花阴·孙守席上次会宗韵》

中中中中平中**仄**，中中平中**仄**。中仄仄平平，中仄平平，中仄平平**仄**。

*檀板一声莺起****速\****，山影穿疏****木\****。人在翠阴中，欲觅残春，春在屏风****曲\****。*

仄平仄仄平平**仄**，中仄平平**仄**。中仄仄平平，中仄平平，中仄平平**仄**。

*劝君对客杯须****覆\****，灯照瀛州****绿\****。西去玉堂深，魄冷魂清，独引金莲烛。*



## 洞仙歌

格律对照例词：《洞仙歌·冰肌玉骨》

中平中仄，仄中平平**仄**。中仄平平仄平**仄**。仄平平、中仄平仄平平，平中仄、中仄平平中**仄**。

*冰肌玉骨，自清凉无****汗\****。水殿风来暗香****满\****。绣帘开，一点明月窥人，人未寝，攲枕钗横鬓****乱\****。*

中平平仄仄，中仄平平，中仄平平仄平**仄**。仄仄仄平平，仄仄平平，平中仄、中平中**仄**。仄中仄平平仄平平，仄平仄平平，仄平平**仄**。

*起来携素手，庭户无声，时见疏星渡河****汉\****。试问夜如何？夜已三更，金波淡、玉绳低****转\****。但屈指西风几时来？又不道流年暗中偷****换\****。*



## 苏幕遮

**正体**

格律对照例词：《苏幕遮·怀旧》

仄平平，平仄**仄**。中仄平平，中仄平平**仄**。中仄中平平仄**仄**。中仄平平，中仄平平**仄**。

*碧云天，黄叶****地\****。秋色连波，波上寒烟****翠\****。山映斜阳天接****水\****。芳草无情，更在斜阳****外\****。*

仄平平，平仄**仄**。中仄平平，中仄平平**仄**。中仄中平平仄**仄**。中仄中平，中仄平平**仄**。

*黯乡魂，追旅思\****。夜夜除非，好梦留人睡。明月楼高休独倚\****。酒入愁肠，化作相思****泪\****。* [3-4]



## 鹧鸪天

**定格**

格律对照例词：《鹧鸪天·彩袖殷勤捧玉钟》

中中中中中中**平**，中平中仄仄平**平**。中平中仄中平仄，中仄平平中仄**平**。

*彩袖殷勤捧玉****钟\****，当年拚却醉颜****红\****。舞低杨柳楼心月，歌尽桃花扇影****风\****。*

中中仄，仄平**平**，中平中仄仄平**平**。中平中仄平平仄，中仄平平中仄**平**。

*从别后，忆相**逢**，几回魂梦与君**同**。今宵剩把银釭照，犹恐相逢是梦****中\****。* [2-3]  





### 



## 蝶恋花

面旋落花风荡漾。柳重烟深，雪絮飞来往。雨后轻寒犹未放，春愁酒病成惆怅。

枕畔屏山围碧浪。翠被华灯，夜夜空相向。寂寞起来搴休幌，月明正在梨花上。



> 近代·[王国维](https://baike.baidu.com/item/王国维/119039)《[人间词话](https://baike.baidu.com/item/人间词话/687)》：欧公《蝶恋花》“面旋落花”云云，字字沉响，殊不可及。

> 欧阳修（1007年—1072年），唐宋八大家之一，字永叔，号醉翁，晚号六一居士，庐陵（今江西吉安）人。

虽然，‘翠被华灯，夜夜空相向。’ 很像我长久以来的处境，但我更很喜欢月明正在梨花上这句。




