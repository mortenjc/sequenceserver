# sequenceserver
Experiments with DNA and protein search using sequenceserver


![Search example](images/hemosearch.svg)


## Prerequisites
Colima or Docker desktop is required. The scripts in **bin/** assume colima.

Detailed instructions can be found at https://sequenceserver.com/doc/#installing


## Running
Note that all commands should be executed from the root of this
repository.

To start sequenceserver:

    > ./bin/dockerstart
    > ./bin/startserver

If all goes well you will be prompted to create relevant database files. Default
action is to just press enter for all questions unless you know better.

Finally you can access the webinterface on

https://localhost:4567

## Database
This demo comes preloaded with fasta files for selected hemoglobin sequences. To
cover a wide variety of species the following were selected:
Home sapiens (you), Pan paniscus (Bonobo), Canis lupus (Wolf), Gallus gallus
(Chicken), Danio rerio (puffer fish), Mizuhopecten yessoensis (Japanese scallop).


## Attribution
Priyam A, Woodcroft BJ, Rai V, Moghul I, Munagala A, Ter F,
Chowdhary H, Pieniak I, Maynard LJ, Gibbins MA, Moon H,
Davis-Richardson A, Uludag M, Watson-Haigh N, Challis R,
Nakamura H, Favreau E, Gómez EA, Pluskal T, Leonard G,
Rumpf W & Wurm Y. _Sequenceserver: A modern graphical user
interface for custom BLAST databases._ Molecular Biology and Evolution (2019)
