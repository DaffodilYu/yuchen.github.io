## Yu's treehole/琅嬛福地

I will share some useful links and my research...

## Interesting links

### Physics Learning
- [blog on Computational physics](https://compphys.go.ro/)
- [MIT EE & CS lecutures](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/)
- [MIT Physics Lectures](https://ocw.mit.edu/courses/physics/) 

## Programming
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


## Publications
1. Chen, Y.; Lechaux, Y.; Casals, B.; Guillet, B.; Minj, A.; Gázquez, J.; Méchin, L.; Herranz, G. _Photoinduced Persistent Electron Accumulation and Depletion in LaAlO3/SrTiO3 Quantum Wells._ [**Phys. Rev. Lett.** 2020, 124, 246804](https://doi.org/10.1103/PhysRevLett.124.246804).






