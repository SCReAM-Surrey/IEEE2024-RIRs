# SCReAM | Audio samples

Room Impulse Responses created with the methods proposed and discussed in the journal paper "Enhanced control of scattering and early reflections in Acoustic Rendering Networks".

Refer to the figures and tables in the paper for room geometries.
Reflection coefficients are also reported in the paper, except for the room 'hallway 3', which has reflection = 0.7.

Source and receiver positions are as follows.
'hallway':
 $\hspace{5mm}$       source = [1.2, 5.4, 1.2]
 $\hspace{5mm}$       receiver = [0.7, 0.6, 0.7]
'hallway 2':
 $\hspace{5mm}$       source = [1.2, 2.4, 1.2]
 $\hspace{5mm}$       receiver = [0.7, 0.6, 0.7]
'hallway 3':
$\hspace{5mm}$        source = [1.2, 2.4, 1.2]
$\hspace{5mm}$        receiver = [0.7, 0.6, 0.7]
'nonconvex':
$\hspace{5mm}$        source = [0.5, 4.5, 1.0]
$\hspace{5mm}$        receiver = [3.5, 4.3, 1.2]
'nonconvex 2':
$\hspace{5mm}$        source = [2.5, 1.5, 1.0]
$\hspace{5mm}$        receiver = [3.5, 3.3, 1.2]
'uneven':
$\hspace{5mm}$        source = [1.2, 1.4, 1.0]
$\hspace{5mm}$        receiver = [0.7, 1.6, 1.7]
'uneven 2':
$\hspace{5mm}$        source = [3.2, 3.4, 1.0]
$\hspace{5mm}$        receiver = [1.7, 2.6, 0.7]

Note that in rooms with scattering=0, the "Householder" matrix option is not available.
This is because the Householder matrix always includes scattering.
The "uniform" matrix exists, and is a permutation matrix.
