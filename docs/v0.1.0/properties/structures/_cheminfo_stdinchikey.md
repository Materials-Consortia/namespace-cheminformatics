# The standard InChIKey identifier of the structure as defined by the InChI Trust (property)

This page documents an [OPTIMADE](https://www.optimade.org/) [Property Definition](https://schemas.optimade.org/#definitions). See [https://schemas.optimade.org/](https://schemas.optimade.org/) for more information.

**ID: [`https://schemas.optimade.org/namespaces/cheminformatics/v0.1/properties/structures/_cheminfo_stdinchikey`](https://schemas.optimade.org/namespaces/cheminformatics/v0.1/properties/structures/_cheminfo_stdinchikey.md)**  
**Definition name:** `_cheminfo_stdinchikey`

**Property name:** The standard InChIKey identifier of the structure as defined by the InChI Trust  
**Description:** The standard InChIKey identifier of the structure as defined by the InChI Trust (https://www.inchi-trust.org).
A standard InChIKey is not guaranteed to be unique and in extremely rare cases the same InChIKey may be assigned to several different structures.  
**Type:** string  



**Examples:**

- `QZAYGJVTTNCVMB-UHFFFAOYSA-N`

**Formats:** [[JSON](_cheminfo_stdinchikey.json)] [[MD](_cheminfo_stdinchikey.md)]

**JSON definition:**

``` json
{
    "$id": "https://schemas.optimade.org/namespaces/cheminformatics/v0.1/properties/structures/_cheminfo_stdinchikey",
    "$schema": "https://schemas.optimade.org/meta/v1.2/optimade/property_definition.json",
    "title": "The standard InChIKey identifier of the structure as defined by the InChI Trust",
    "x-optimade-type": "string",
    "x-optimade-definition": {
        "kind": "property",
        "version": "0.1.0",
        "format": "1.2",
        "name": "_cheminfo_stdinchikey",
        "label": "_cheminfo_stdinchikey_structures"
    },
    "type": [
        "string",
        "null"
    ],
    "description": "The standard InChIKey identifier of the structure as defined by the InChI Trust (https://www.inchi-trust.org).\nA standard InChIKey is not guaranteed to be unique and in extremely rare cases the same InChIKey may be assigned to several different structures.",
    "examples": [
        "QZAYGJVTTNCVMB-UHFFFAOYSA-N"
    ],
    "x-optimade-unit": "inapplicable"
}
```