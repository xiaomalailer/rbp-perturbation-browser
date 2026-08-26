# K562 Modification-Enzyme Perturbation Browser (Li Lab)

Static public browser for 65 K562 RNA-modification-enzyme perturbations retained
by maximum-AD guide deduplication and the strict AD>5 filter. It includes
Dynamic Tree Cut deepSplit=2/4 similarity maps, functional annotations, and
lazy-loaded volcano and GO Biological Process results for every perturbation.

Serve this directory over HTTP; for example:

```bash
python3 -m http.server 8000 --directory browser
```

Then open `http://localhost:8000`. The site has no upload feature and does not
publish the source `.h5ad`, GMT, or intermediate analysis files.
