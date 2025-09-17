# Preferred IUPAC name (property)

This page documents an [OPTIMADE](https://www.optimade.org/) [Property Definition](https://schemas.optimade.org/#definitions). See [https://schemas.optimade.org/](https://schemas.optimade.org/) for more information.

**ID: [`https://schemas.optimade.org/namespaces/cheminformatics/v0.1/properties/structures/_cheminfo_preferred_iupac_name`](https://schemas.optimade.org/namespaces/cheminformatics/v0.1/properties/structures/_cheminfo_preferred_iupac_name.md)**  
**Definition name:** `_cheminfo_preferred_iupac_name`

**Property name:** Preferred IUPAC name  
**Description:** A unique name for a chemical compound defined according to the rules of Preferred IUPAC Names (PINs).
The rules for PINs are provided in "Nomenclature of Organic Chemistry. IUPAC Recommendations and Preferred Names 2013", also known as the Blue Book (https://iupac.qmul.ac.uk/BlueBook/).
Usage of the Blue Book version 3 (2023-12-06) is RECOMMENDED.  
**Type:** string  



**Examples:**

- `1-ethoxypropane`
- `2,5,8,11-tetraoxatridecane`
- `7,7-dimethylbicyclo[2.2.1]heptane`

**Formats:** [[JSON](_cheminfo_preferred_iupac_name.json)] [[MD](_cheminfo_preferred_iupac_name.md)]

**JSON definition:**

``` json
{
    "$id": "https://schemas.optimade.org/namespaces/cheminformatics/v0.1/properties/structures/_cheminfo_preferred_iupac_name",
    "$schema": "https://schemas.optimade.org/meta/v1.2/optimade/property_definition.json",
    "title": "Preferred IUPAC name",
    "x-optimade-type": "string",
    "x-optimade-definition": {
        "kind": "property",
        "version": "0.1.0",
        "format": "1.2",
        "name": "_cheminfo_preferred_iupac_name",
        "label": "_cheminfo_preferred_iupac_name_structures"
    },
    "type": [
        "string",
        "null"
    ],
    "description": "A unique name for a chemical compound defined according to the rules of Preferred IUPAC Names (PINs).\nThe rules for PINs are provided in \"Nomenclature of Organic Chemistry. IUPAC Recommendations and Preferred Names 2013\", also known as the Blue Book (https://iupac.qmul.ac.uk/BlueBook/).\nUsage of the Blue Book version 3 (2023-12-06) is RECOMMENDED.",
    "examples": [
        "1-ethoxypropane",
        "2,5,8,11-tetraoxatridecane",
        "7,7-dimethylbicyclo[2.2.1]heptane"
    ],
    "x-optimade-unit": "inapplicable"
}
```