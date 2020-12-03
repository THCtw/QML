# Quantum Fourier Transform
Briefly speaking, quantum Fourier transform (QFT) is discrete Fourier transform on quantum devices.

## Discrete Fourier Transform
DFT transform a N dimension vector 
<img src="https://render.githubusercontent.com/render/math?math={
    x_0, x_1, ... ,x_{N-1}
}"> 
to another N dimension vector
<img src="https://render.githubusercontent.com/render/math?math={
    y_0, y_1, ... ,y_{N-1}
}">
as following,

<p align="center">
<img src="https://render.githubusercontent.com/render/math?math={
    \begin{equation} 
    \large y_k \equiv \frac{1}{\sqrt{N}} \sum_{j=0}^{N-1} x_j e^{2\pi ijk / N}
    \end{equation}
}">
</p>

## Quantum Fourier Transform
On the other hand, QFT, operates the same transformation with different form of notation. Consider an orthonormal basis

<img src="https://render.githubusercontent.com/render/math?math={
    
}">
