---
title: "Matlab"
collection: coding
type: "matlab"
permalink: /coding/matlab
venue: " University of Naples &quotFederico II&quot, Department of Physics"
date: 2022-03-26
location: "Napoli, Italy"
---


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
