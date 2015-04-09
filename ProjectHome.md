RDF HDT (Header-Dictionary-Triples) is a format for publishing and exchanging RDF data at large scale. RDF HDT represents RDF in a compact manner, natively supporting splitting huge RDF graphs into several chunks. It is designed to allow high compression rates. This is achieved by organizing and representing the RDF graph in terms of three main components: Header, Dictionary and Triples structure. The Header includes extensible metadata required to describe the RDF data set and its organization. The Dictionary organizes all vocabulary present in the RDF graph in a manner that permits rapid search and high levels of compression. The Triples component comprises the pure structure of the underlying graph in a compressed form.