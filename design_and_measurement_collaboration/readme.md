This directory contains data used during the design and measurement collaboration example. Each directory contains files exported from native CAD (CATIA V5, Creo, and NX) to .stp with assigned UUIDs for each of four  design iterations described below.

Default organization:
Each source file will have its own subdirectory (by the basename of the file).

## Rev 0.0:
Initial state of the CAD model
- Plate of dimensions 50.8 mm x 76.2 mm x 10 mm with a 19 mm diameter hole.
- The hole is located at (3.2, 6.4, 10).
- Model units: mm
- Datum A in the positive direction
- Creo absolute accuracy = .009906 mm

## Rev 0.1:
Model from Rev 0.0 remains unchanged with the exception of the change noted below.
- The 19 diameter hole was moved to (-8.3, 8.9, 10).

## Rev 0.2:
Model from Rev 0.1 remains unchanged with the exception of the change noted below.
- The hole feature was deleted and a new diameter 19 hole feature was created at (-6.3, 6.9, 10).

## Rev 0.3:
Model from Rev 0.2 remains unchanged with the exception of the change noted below.
- Chamfer X = 7.6 and Y = 5.1 added to the model.
