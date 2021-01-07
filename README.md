<img src="images/improve.png" align="center">


# improve

Using `the sequential least squares programming algorit`, the drag
coefficient for this wing decreases from `0.20031270E-01` to
`0.17377422E-01`.


# What is this?


## TODO Using span-wise averaged function to generate runtime data

The goal is to figure out how to [use the source code](https://github.com/ZmengXu/sampledPlaneAverage/tree/of7/sampledSurface/sampledPlaneSpanwise) and porting data
from v7 to v1906.

The testing code would be in the branch: `span-wise-average`.


## Road map


### TODO run with of7/of8 <code>[0/10]</code>

-   TODO find a proper tutorial to play

    I find an example, i.e.
    `$FOAM/tutorials/incompressible/simpleFoam/airFoil2D/` very fast to
    run the test. It's a 2D model.

    -   TODO issue with airFoil2D

        The front and back is defined using the same group.

            frontAndBack
            {
                type empty;
                physicalType empty;
                nFaces 21440;
                startFace 21626;
            }

        This will make a wrong extrusion.

    -   TODO test with aerofoilNACA0012

        in: `$FOAM/tutorials/compressible/rhoSimpleFoam/aerofoilNACA0012`

-   TODO how to extrude 2d mesh?

-   TODO compile the add-on code

-   TODO setup the system directory

-   TODO validate the data is span-wise averaged

-   TODO try to understand the source code

-   TODO try to compile it with ofv1906

-   TODO study the code difference between ofv1906 v.s. of7/of8

-   TODO translate the of7/8 to ofv1906

-   TODO test the tutorial case


# Contributing

Yes, please do! See [CONTRIBUTING][] for guidelines.


# License

See [COPYING][]. Copyright (c) 2020 Ran Wang.

[CONTRIBUTING]: ./CONTRIBUTING.md
[COPYING]: ./COPYING
