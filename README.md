# bioc-ld

We define a linked-data-enabled implmentation of the [BioC](http://bioc.sourceforge.org/) lightweight document annotation format. This work is intended to be complementary to existing [Semantic Web standards for Web Annotation](https://www.w3.org/annotation/) by providing a minimalist, self-contained representaton of the BioC core classes so that data and tools developed using that standard could be easily represented as linked data. 

We will develop tools for conversion to community standards presently. 

The main contributions of this library are:

* A version of a BioC ontology defined in `TTL` format: [bioc.ttl](bioc.ttl)
* A mapping file to map semantic web elements to JSON-LD: [context.json](context.json) 
