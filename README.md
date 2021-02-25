# Knowledge-bases

Based on OWL ontologies.

Currently, there are the following ontologies to use as base for your knowledge-bases:
| Name | IRI           | Description   |
| ---- | ------------- |:-------------:|
| InFormALin Base | https://informalin.github.io/knowledgebases/informalin_base.owl | |
| InFormALin Base Ecore | https://informalin.github.io/knowledgebases/informalin_base_ecore.owl | |
| InFormALin Base PCM | https://informalin.github.io/knowledgebases/informalin_base_pcm.owl | |
| InFormALin Base Text | https://informalin.github.io/knowledgebases/informalin_base_text.owl | |

The following example ontologies should give a rough idea how to use them:
- https://informalin.github.io/knowledgebases/examples/informalin_example_MediaStore.owl: (MediaStore)[https://github.com/ArDoCo/CaseStudies/tree/master/MediaStore3_Model] example combining PCM and Textual Documentation

## Create new ontologies

Import the necessary ontologies. The following are recommended for a start:
- `https://informalin.github.io/knowledgebases/informalin_base_pcm.owl` if you want to instantiate/use or extend the pcm ontology
- `https://informalin.github.io/knowledgebases/informalin_base_text.owl` if you want to instantiate/use or extend the ontology about texts (informal textual documents)
