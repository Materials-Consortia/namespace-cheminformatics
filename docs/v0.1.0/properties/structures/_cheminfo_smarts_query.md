# A chemical substructure query in the SMARTS language (property)

This page documents an [OPTIMADE](https://www.optimade.org/) [Property Definition](https://schemas.optimade.org/#definitions). See [https://schemas.optimade.org/](https://schemas.optimade.org/) for more information.

**ID: [`https://schemas.optimade.org/namespaces/cheminformatics/v0.1/properties/structures/_cheminfo_smarts_query`](https://schemas.optimade.org/namespaces/cheminformatics/v0.1/properties/structures/_cheminfo_smarts_query.md)**  
**Definition name:** `_cheminfo_smarts_query`

**Property name:** A chemical substructure query in the SMARTS language  
**Description:** A property used to specify chemical substructure queries in the SMILES Arbitrary Target Specification (SMARTS) language, defined in the Daylight SMARTS documentation (https://www.daylight.com/dayhtml/doc/theory/theory.smarts.html).
This property is not intended to be stored or returned by the API, but rather to be used in queries to search for structures containing a specified substructure via the `CONTAINS` operator.  
**Type:** string  



**Examples:**

- `"C(=O)O.OCC>>C(=O)OCC.O"`
- `"[$([NH2][CX4]),$([NH]([CX4])[CX4]),$([NX3]([CX4])([CX4])[CX4])]"`
- `"[$([OH][C,S,P]=O),$([nH]1nnnc1)]"`

**Formats:** [[JSON](_cheminfo_smarts_query.json)] [[MD](_cheminfo_smarts_query.md)]

**JSON definition:**

``` json
{
    "$id": "https://schemas.optimade.org/namespaces/cheminformatics/v0.1/properties/structures/_cheminfo_smarts_query",
    "$schema": "https://schemas.optimade.org/meta/v1.2/optimade/property_definition.json",
    "title": "A chemical substructure query in the SMARTS language",
    "x-optimade-type": "string",
    "x-optimade-definition": {
        "kind": "property",
        "version": "0.1.0",
        "format": "1.2",
        "name": "_cheminfo_smarts_query",
        "label": "_cheminfo_smarts_query"
    },
    "type": [
        "string",
        "null"
    ],
    "description": "A property used to specify chemical substructure queries in the SMILES Arbitrary Target Specification (SMARTS) language, defined in the Daylight SMARTS documentation (https://www.daylight.com/dayhtml/doc/theory/theory.smarts.html).\nThis property is not intended to be stored or returned by the API, but rather to be used in queries to search for structures containing a specified substructure via the `CONTAINS` operator.",
    "examples": [
        "C(=O)O.OCC>>C(=O)OCC.O",
        "[$([NH2][CX4]),$([NH]([CX4])[CX4]),$([NX3]([CX4])([CX4])[CX4])]",
        "[$([OH][C,S,P]=O),$([nH]1nnnc1)]"
    ],
    "x-optimade-unit": "inapplicable"
}
```