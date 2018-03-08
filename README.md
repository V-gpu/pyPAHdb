# pyPAHdb

pyPAHdb is a Python package to quickly decompose astronomical PAH
emission spectra into contributing PAH subclasses.

## Installing

pyPAHdb can be directly installed from the
[repository](https://github.com/pahdb/pypahdb):

``pip install git+git://github.com/pahdb/pypahdb.git#egg=pypahdb``

Examples on using pyPAHdb can be found in the
[examples](https://github.com/pahdb/pypahdb/examples/)-directory.

Unit-tests are available in the
[pypahdb/tests](https://github.com/pahdb/pypahdb/pypahdb/tests/)-directory.

Documentation can be found in the
[docs](https://github.com/pahdb/pypahdb/docs/)-directory.

## Background

The pyPAHdb package is being developed as part of the awarded [James
Webb Space Telescope](https://www.jwst.nasa.gov/) (*JWST*) Early Release Science (ERS) program
"Radiative Feedback from Massive Stars as Traced by Multiband Imaging
and Spectroscopic Mosaics" ([program website](http://jwst-ism.org/);
ID: 1288). The entire program is coordinated by an international "Core
team" of 19 scientists and supported by 119 "science
collaborators". pyPAHdb is developed by the
[NASA Ames PAH IR Spectroscopic Database](http://www.astrochemistry.org/pahdb/) team,
asscociated with the
[Astrophysics & Astrochemistry Laboratory](http://www.astrochemistry.org)
at NASA Ames Research Center
[NASA Ames Research Center](https://www.nasa.gov/centers/ames).

pyPAHdb uses a precomputed matrix of theoretically calculated PAH
emission spectra from the NASA Ames PAH IR Spectroscopic
Database. This matrix has been constructed from a collection of
"astronomical" PAHs, which meet the following critera:

       'magnesium=0 oxygen=0 iron=0 silicium=0 chx=0 ch2=0 c>20'

Version 3.00 of the library of computed spectra from the NASA Ames PAH
IR Spectroscopic Database (PAHdb) has been used.

The PAH emission spectra have been calculated with the following
parameters:

   * Pure PAHs/PANHs more than 20 carbon atoms in size
   * A calculated vibrational temperature upon the absorption of a 7
     eV photon
   * Blackbody emission at the calculated vibrational temperature
   * A redshift of 15 /cm to mimic some anharmonic effect
   * Gaussian emission profile with a FWHM of 15 /cm

The NASA Ames PAH IR Spectroscopic Database website is located at
www.astrochemistry.org/pahdb/.

You are kindly asked to cite the following papers when using pyPAHdb:

    * C.W. Bauschlicher, Jr., A. Ricca, C. Boersma, and
      L.J. Allamandola, "THE NASA AMES PAH IR SPECTROSCOPIC DATABASE:
      COMPUTATIONAL VERSION 3.00 WITH UPDATED CONTENT AND THE
      INTRODUCTION OF MULTIPLE SCALING FACTORS", The Astrophysical
      Journal Supplement Series, 234, 32, 2018
      10.3847/1538-4365/aaa019

    * C. Boersma, C.W. Bauschlicher, Jr., A. Ricca, A.L. Mattioda,
      J. Cami, E. Peeters, F. Sanchez de Armas, G. Puerta Saborido,
      D.M. Hudgins, and L.J. Allamandola, "THE NASA AMES PAH IR
      SPECTROSCOPIC DATABASE VERSION 2.00: UPDATED CONTENT, WEBSITE AND
      ON/OFFLINE TOOLS", The Astrophysical Journal Supplement Series,
      211, 8, 2014 10.1088/0067-0049/211/1/8

    * Mattioda, A. L., Hudgins, D. M., Boersma, C., Ricca, A.,
      Peeters, E., Cami, J., Sanchez de Armas, F., Puerta Saborido,
      G., Bauschlicher, C. W., J., and Allamandola, L. J. "THE NASA
      AMES PAH IR SPECTROSCOPIC DATABASE: THE LABORATORY SPECTRA", The
      Astrophysical Journal Supplement Series, XXX, 201X (in
      preparation)

## Contributing

Please read [CONTRIBUTING.md](https://github.com/PAHdb/CONTRIBUTING.md)
for details on the code of conduct, and the process for submitting
pull requests.

## Versioning

For the versions available, see the
[tags on this repository](https://github.com/pahdb/pypahdb/tags).

## Authors

* **Christiaan Boersma** - *Initial work* - [PAHdb](https://github.com/pahdb)
* **Matthew J. Shannon** - *Initial work* - [PAHdb](https://github.com/pahdb)

See also the list of
[contributors](https://github.com/PAHdb/AmesPAHdbIDLSuite/contributors)
who participated in this project.

## License

This project is licensed under the BSD 3-Clause License - see the
[LICENSE](LICENSE) file for details

## Acknowledgments

* The NASA Ames PAH IR Spectroscopic Database Team -
  [www.astrochemistry.org/pahdb](http://www.astrochemistry.org/pahdb/theoretical/3.00/help/about)
* The Astrophysics & Astrochemistry Laboratory at NASA Ames Research
  Center - [www.astrochemistry.org](http://www.astrochemistry.org)