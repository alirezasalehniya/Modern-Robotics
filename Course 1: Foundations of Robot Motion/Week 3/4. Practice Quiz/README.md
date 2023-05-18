## Lecture Comprehension, Angular Velocities (Chapter 3.2.2)

### Question 1:
Our representation of the three-dimensional orientation uses an implicit representation (a 3x3 SO(3) matrix with 9 numbers), but our usual representation of the angular velocity uses only three numbers, i.e., an explicit parametrization of the three-dimensional velocity space. Why do we use an implicit representation of the orientation but an explicit parametrization of the angular velocity?<br>
&#10007; There is no natural implicit representation of an angular velocity.<br>
&#10003; The space of angular velocities can be equated to a "flat" 3d space (a linear vector space) tangent to the curved 3d surface of orientations at any given time, so it can be globally represented by 3 numbers without singularities. The space of orientations, on the other hand, is not flat, and cannot be globally represented by 3 numbers without a singularity.<br>

--------------------------------------------------------------------------------------------------------------------------------------------------------
### Question 2:
A rotation matrix is an element of which space?<br>
&#10007; R<sup>3</sup> <br>
&#10003; SO(3) <br>
&#10007; so(3) <br>

--------------------------------------------------------------------------------------------------------------------------------------------------------
### Question 3:
An angular velocity is an element of which space? <br>
&#10003; R<sup>3</sup> <br>
&#10007; SO(3) <br>
&#10007; so(3) <br>

--------------------------------------------------------------------------------------------------------------------------------------------------------
### Question 4:
The 3x3 skew-symmetric matrix representation of an angular velocity is an element of which space? <br>
&#10007; R<sup>3</sup> <br>
&#10007; SO(3) <br>
&#10003; so(3) <br>

--------------------------------------------------------------------------------------------------------------------------------------------------------
### Question 5:
If an angular velocity is represented as ω<sub>b</sub> in the body frame {b}, what is the representation of the same angular velocity in the space frame {s}? <br>
&#10003; R<sub>sb</sub>.ω<sub>b</sub> <br>
&#10007; R<sub>bs</sub>.ω<sub>b</sub> <br>
&#10007; ω<sub>b</sub>.R<sub>sb</sub> <br>
&#10007; ω<sub>b</sub>.R<sub>bs</sub> <br>

--------------------------------------------------------------------------------------------------------------------------------------------------------
### Question 6:
The cross-product ω×p can be written [ω]p, where [ω] is:<br>
&#10007; the SO(3) representation of ω.<br>
&#10003; the skew-symmetric so(3) representation of ω.<br>
