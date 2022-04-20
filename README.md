# Higgs-Boson-Background-Event-Detection


HIGGS BOSON-->the fundamental particle associated with the Higgs field, a field that gives mass to other fundamental particles such as electrons and quarks
It was discovered at at the Large Hadron Collider (LHC) at CERN (the European Organization for Nuclear Research), Geneva in 2013.

In the LHC, proton bunches are accelerated on a circular trajectory in both directions. When
these bunches cross in the ATLAS detector, some of the protons collide, producing hundreds of
millions of proton-proton collisions per second. The up to hundreds of particles resulting from
each bunch crossing (called an event) are detected by sensors, producing a sparse vector of about
a hundred thousand dimensions (roughly corresponding to an image or speech signal in classical
machine learning applications). From this raw data, the type, the energy, and the 3D direction
of each particle are estimated. In the last step of this feature construction phase, this variable-
length list of four-tuples is digested into a fixed-length vector of features containing up to tens of real-valued variables.

The idea of this project was inspired from The Higgs boson machine learning challenge (HiggsML or Challenge in short).It had been set up to promote collaboration between high energy physicists and data scientists.The implementation shown here is part of the bigger challenge which was to find a (not necessarily connected) region in the feature space in which there is a significant excess of events (called signal) compared to what known background processes can explain. Once the region has been fixed, a statistical (counting) test is applied to determine the significance of the excess. If the probability that the excess has been produced by background processes falls below a limit,the new particle is deemed to be discovered.The main of these challenge was to detect the undesired uninteresting background particles by machine learning techniques and then remove them.
