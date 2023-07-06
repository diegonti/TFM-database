# TFM-database

Database for the extra information of my Master's thesis work, "Tuning MXenes towards their Use in Photocatalytic Water Splitting". Here, you will find the complete database utilized for the Machine Learning (ML) models, as well as additional data that could not be accommodated within the confines of the report.

## ML Database

The `ML_database.xlsx` contains the database used for the Machine Learning models. The Excel has 3 pages: one containing the full database, "database", another one that has the same data but in an Excel table format, "database_table", for better manipulation, and the last one, "info", that contains information on all features used and what the labels mean.

Here can be found the **PBE and PBE0 bandgap** values for all terminated MXene structures considered and discussed in the report. Moreover, here are also gathered the **structural parameters**, such as the lattice constant, $a$, and width, $d$, and other ones like the $M-T$, $X-T$, and $M-X$ distances of both surfaces.

## Energies

In `Energies.xlsx` are presented the relative energies of each MXene, $\Delta E$, with respect to the $ABC H_M$ structure, with the bold values indicating the most stable one from the six condifered. Nontheless, on the "Most_stable" page, a table with the most stable configuration can be found for each case.

The $\Delta E$ plots can be found in the `Energy/` folder, where they are classified for each termination.

## Density of States

The PBE and PBE0 projected DOS plots are gathered in the `DOS/` folder, classified by termination and structure. In each plot the energyes have been corrected with the Fermi level.

<br><br>
For any doubts or help, contact [Diego Ontiveros](https://github.com/diegonti) ([Mail](mailto:diegonti.doc@gmail.com)).
