# InChIKey identifier of the structure as defined by the InChI Trust (property)

This page documents an [OPTIMADE](https://www.optimade.org/) [Property Definition](https://schemas.optimade.org/#definitions). See [https://schemas.optimade.org/](https://schemas.optimade.org/) for more information.

**ID: [`https://schemas.optimade.org/namespaces/cheminformatics/v0.1/properties/structures/_cheminfo_inchikey`](https://schemas.optimade.org/namespaces/cheminformatics/v0.1/properties/structures/_cheminfo_inchikey.md)**  
**Definition name:** `_cheminfo_inchikey`

**Property name:** InChIKey identifier of the structure as defined by the InChI Trust  
**Description:** An InChIKey identifier of the structure as defined by the InChI Trust (https://www.inchi-trust.org).
It may be any type of InChIKey, including the Standard InChIKey.
InChIKey is not guaranteed to be unique and in extremely rare cases the same InChIKey may be assigned to several different structures.  
**Type:** string  



**Examples:**

- `QZAYGJVTTNCVMB-UHFFFAOYSA-N`
- `QZAYGJVTTNCVMB-UHFFFAOYNA-N`

**Formats:** [[JSON](_cheminfo_inchikey.json)] [[MD](_cheminfo_inchikey.md)]

**JSON definition:**

``` json
{
    "$id": "https://schemas.optimade.org/namespaces/cheminformatics/v0.1/properties/structures/_cheminfo_inchikey",
    "$schema": "https://schemas.optimade.org/meta/v1.2/optimade/property_definition.json",
    "title": "InChIKey identifier of the structure as defined by the InChI Trust",
    "x-optimade-type": "string",
    "x-optimade-definition": {
        "kind": "property",
        "version": "0.1.0",
        "format": "1.2",
        "name": "_cheminfo_inchikey",
        "label": "_cheminfo_inchikey_structures"
    },
    "type": [
        "string",
        "null"
    ],
    "description": "An InChIKey identifier of the structure as defined by the InChI Trust (https://www.inchi-trust.org).\nIt may be any type of InChIKey, including the Standard InChIKey.\nInChIKey is not guaranteed to be unique and in extremely rare cases the same InChIKey may be assigned to several different structures.",
    "examples": [
        "QZAYGJVTTNCVMB-UHFFFAOYSA-N",
        "QZAYGJVTTNCVMB-UHFFFAOYNA-N"
    ],
    "x-optimade-unit": "inapplicable"
}
```