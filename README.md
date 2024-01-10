# namespace-cheminformatics

Repository for the cheminformatics namespace. 
**Note: this is presently used only to work out an explicit example of a defintion-provider namespace and is to be regarded as extremely experimental**

1. Clone this repo (with submodules for tools)
   ```
   git clone --recurse-submodules https://github.com/Materials-Consortia/namespace-cheminformatics.git
   ```

2. Run make.

4. Output appears in `output/`, check the standards document with, e.g.:
   ```
   firefox output/v0.1.0/standards/cheminformatics
   ```

Notes:

- For prettifed HTML output add `schemas_html_pretty=true` when running make:
  ```
  make schemas_html_pretty=true
  ```

- To generate HTML output with `.html` extensions (instead of extensionless):
  ```
  make schemas_html_ext=true
  ```
  (Less suited for filesystem browsing, but works as intended when served e.g. via GitHub pages)
