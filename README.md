
We refer to the g=5 example of the article "Explicit generalized 2-descent on Jacobians of non-hyperelliptic curves of moderate genus". <br />

 - Galois Group G: file GaloisGroup  <br />
Contains the Magma command to acces G as well as the explicit extension that realise it.
 - Explicit Polynomials for the fields of the small orbits: file EtaleFields <br />
Contains the explicit polynomials that define the "small orbits". They are the orbits used to perform 2-descent in the article. <br />
We also give the polyomial of the orbit we computed the Galois closure from.
 - Etale Polynomials: file chiOTC, chiETC, chiJ2 <br />
These files contain the etale polynomials of the OTC, the ETC and J[2], as returned by the algorithm of the author. One could apply the PARI/GP fonction "polredbest" to each factors. To access the etale polynomials, open a PARI/GP session and run the corresponding file with the command 'read'. <br />
Ex[in the gp terminal]: chiOTC=read("~/ArticleDescentExamples/chiOTC");

