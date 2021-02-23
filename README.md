# Knowledge-bases

Based on OWL ontologies.

## Import the base ontology
To create a specific knowledge-base, currently the best way is to copy the base ontology and change the IRI. Alternatively, create a new ontology and copy (all) the axioms into the newly create ontology. With Protege, you can do the following:
1. Open the base ontology and the new ontology in the same window. Have the base ontology selected.
2. Go to `Refactor` and then to `Copy/Move/Delete axioms...`.
3. Select the axiom selection method
4. Select the signature by moving them from the left part to the right using the `>>` button.
5. Preview the axioms
6. Select what you want to do: `copy`.
7. Select the target ontology
8. DONE

Also, you can import the base ontology to use the given axioms. For this, import the following URI: `https://raw.githubusercontent.com/InFormALin/knowledgebases/main/informalin_base.owl`


