<<<<<<< HEAD
Tugas Matriks

A. Determinan
1.
A=[
−7
1
	​

−5
4
	​

]

Rumus determinan 2×2:

det(A)=ad−bc
=(−7)(4)−(−5)(1)=−28−(−5)=−28+5=−23

Hasil: det(A)=−23

2.
A=
	​

0
1
0
	​

2
−2
0
	​

−3
−1
1
	​

	​


Karena ini segitiga atas, determinan = hasil kali diagonal:

det(A)=0⋅(−2)⋅1=0

Hasil: det(A)=0

3.
A=
	​

1
−3
1
1
	​

−3
1
1
1
	​

1
1
−3
1
	​

1
1
1
−3
	​

	​


Dengan eliminasi baris (ringkas):

Hasil akhirnya:

det(A)=0

Hasil: det(A)=0

B. Invers Matriks

Rumus:

A
−1
=
det(A)
1
	​

adj(A)
4.
A=[
−7
1
	​

−5
4
	​

]

Sudah tahu:

det(A)=−23

Rumus invers 2×2:

A
−1
=
ad−bc
1
	​

[
d
−c
	​

−b
a
	​

]
A
−1
=
−23
1
	​

[
4
−1
	​

5
−7
	​

]

Hasil:

A
−1
=[
−4/23
1/23
	​

−5/23
7/23
	​

]
5.

(Matrix sama seperti nomor 2)

det(A)=0

Tidak punya invers (karena determinan = 0)

6.

(Matrix sama seperti nomor 3)

det(A)=0

Tidak punya invers (singular matrix)
=======
1. Matriks $2 \times 2$$A = \begin{bmatrix} -7 & -5 \\ 1 & 4 \end{bmatrix}$Proses:$\text{det}(A) = (-7 \cdot 4) - (-5 \cdot 1)$$\text{det}(A) = -28 + 5 = \mathbf{-23}$2. Matriks $3 \times 3$$A = \begin{bmatrix} 0 & 2 & -3 \\ 1 & -2 & -1 \\ 0 & 0 & 1 \end{bmatrix}$Proses (Ekspansi Baris 3):$\text{det}(A) = a_{31}C_{31} + a_{32}C_{32} + a_{33}C_{33}$$\text{det}(A) = 0 - 0 + 1 \begin{vmatrix} 0 & 2 \\ 1 & -2 \end{vmatrix}$$\text{det}(A) = 1 \cdot (0 - 2) = \mathbf{-2}$3. Matriks $4 \times 4$$A = \begin{bmatrix} 1 & -3 & 1 & 1 \\ -3 & 1 & 1 & 1 \\ 1 & 1 & -3 & 1 \\ 1 & 1 & 1 & -3 \end{bmatrix}$Proses: Karena jumlah setiap elemen per baris adalah 0 ($1-3+1+1=0$), maka baris-barisnya dependen linier.$\text{det}(A) = \mathbf{0}$BAGIAN B: Menghitung Invers dengan Matriks Adjoin4. Invers Matriks Nomor 1$A = \begin{bmatrix} -7 & -5 \\ 1 & 4 \end{bmatrix}$, $\text{det}(A) = -23$Cari Adjoin: (Tukar elemen diagonal utama, kali -1 diagonal samping)$\text{adj}(A) = \begin{bmatrix} 4 & 5 \\ -1 & -7 \end{bmatrix}$Invers:$A^{-1} = \frac{1}{-23} \begin{bmatrix} 4 & 5 \\ -1 & -7 \end{bmatrix} = \mathbf{\begin{bmatrix} -4/23 & -5/23 \\ 1/23 & 7/23 \end{bmatrix}}$5. Invers Matriks Nomor 2$A = \begin{bmatrix} 0 & 2 & -3 \\ 1 & -2 & -1 \\ 0 & 0 & 1 \end{bmatrix}$, $\text{det}(A) = -2$Cari Kofaktor (C):$C_{11} = -2, C_{12} = -1, C_{13} = 0$$C_{21} = -2, C_{22} = 0, C_{23} = 0$$C_{31} = -8, C_{32} = -3, C_{33} = -2$Adjoin (Transpose Kofaktor):$\text{adj}(A) = \begin{bmatrix} -2 & -2 & -8 \\ -1 & 0 & -3 \\ 0 & 0 & -2 \end{bmatrix}$Invers:$A^{-1} = \frac{1}{-2} \begin{bmatrix} -2 & -2 & -8 \\ -1 & 0 & -3 \\ 0 & 0 & -2 \end{bmatrix} = \mathbf{\begin{bmatrix} 1 & 1 & 4 \\ 0.5 & 0 & 1.5 \\ 0 & 0 & 1 \end{bmatrix}}$6. Invers Matriks Nomor 3$A = \begin{bmatrix} 1 & -3 & 1 & 1 \\ -3 & 1 & 1 & 1 \\ 1 & 1 & -3 & 1 \\ 1 & 1 & 1 & -3 \end{bmatrix}$Proses: Karena $\text{det}(A) = 0$ (dari soal nomor 3), maka matriks ini adalah matriks singular.Hasil: Matriks tidak memiliki invers.
>>>>>>> 2c35283dd6110d584e14a5f20a79a0d173df3e6a
