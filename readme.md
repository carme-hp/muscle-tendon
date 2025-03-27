# Muscle-tendon complex

Context: muscle sends the traction

Expected behaviour:
- When we activate the muscle, the length of the muscle-tendon complex diminishes -> for this we need the (-1) on the traction. This means that the traction on the muscle end has an inverted signed with respect to the traction on the tendon end. Hence we removed the traction from convergence and acceleration.

- traction in precice configuration -> does not matter
- linear vs non-linear -> non-linear contracts slightly more?
- Averaged vs non-averaged -> differences in values (averaged looks slightly better, in the sense that the values of traction are smaller - in abs- than in the muscle)

