# graph JSON examples

This repository collects examples of JSON representation of graph data structures.
It is intended to find a good JSON representation for simple JSON graphs rendered out of [Portable Linked Profiles](https://github.com/ouisharelabs/plp-berlin-hacks) for visualizations like [Public Space Invaders](http://alpha.publicspaceinvaders.org) or the [Open Steps Directory](http://directory.open-steps.org), if direct RDFa/JSON-LD/Turtle parsing is not available.

## files

* `federated_wiki.json`

Derived from [Federated Wiki](https://github.com/WardCunningham/Smallest-Federated-Wiki/)'s Websocket stream of the [Linkmap](http://socio.federated.wiki/t/linkmap/13/1) plugin.
This looks how the *Directed Acyclic Graph* (DAG) looks like according to [**stack**overflow](http://stackoverflow.com/questions/9897956/how-do-you-store-a-directed-acyclic-graph-dag-as-json).

* `metacademy_demo.json`

This is an example of the old [Metacademy Content](https://github.com/metacademy/metacademy-content) markup.
The newer fixture can be found in the [application repository](https://github.com/metacademy/metacademy-application/blob/master/server/apps/graph/fixtures/graph_fixture.json).

* `metacademy.json`

This is how a downloaded graph from [Metacademy](https://metacademy.org/) looks like.

* `mydag.json`

This can be created with [`directed-graph-creator`](https://gist.github.com/cjrd/6863459) and resembles very much to the Federated Wiki example.

* `open_steps_directory.json`

This is an old example from the [Open Steps Directory](http://directory.open-steps.org/), before it has been rebuilt on [Portable Linked Profiles](https://github.com/hackers4peace/plp-docs/) and proper JSON-LD.

* `public_space_invaders.json`

This is the output of our improvised Django-SQL-graph [example from Public Space Invaders](https://github.com/gryzzly/publicspaceinvaders/blob/master/invaders/views.py).

* `vega.json`

This file represents the model of Vega's graph model, the proposed declarative successor to D3.
