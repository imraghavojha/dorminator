# dorminator

## problem statement

we are developing an algorithm to manage dorm assignments at Texas State University while considering parking constraints. The system tracks the number of beds and resident parking permits available for each dorm. When a new student applies, the algorithm checks whether they are bringing a vehicle.

- If the preferred dorm has space and parking availability, the student is assigned.
- If the dorm reaches 95% capacity, no further assignments are allowed there.
- If the student's preferred dorm is full, the algorithm checks their next preference.
- If all preferred dorms are full, the system recommends the closest available dorm to the student's top preference.

The algorithm continuously updates as students join dorms to ensure accurate tracking of occupancy and parking availability.
