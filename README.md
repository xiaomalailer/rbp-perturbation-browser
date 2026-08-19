# RBP Perturbation Similarity Browser (Li Lab)

Static public browser for 1,376 K562 RBP perturbations retained by the AD>5
filter. It includes Dynamic Tree Cut similarity maps and lazy-loaded volcano
and GO Biological Process results for every perturbation.

Serve this directory over HTTP; for example:

```bash
python3 -m http.server 8000 --directory browser
```

Then open `http://localhost:8000`. The site has no upload feature and does not
publish the source `.h5ad`, GMT, or intermediate analysis files.
