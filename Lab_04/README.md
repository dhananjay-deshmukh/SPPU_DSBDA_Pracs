# Boston Dataset removed from scikit-learn

Error faced : 

```bash
ImportError: 
`load_boston` has been removed from scikit-learn since version 1.2.
```

To fix this downgrade the scikit-learn version. Run:

```bash
pip install scikit-learn==1.1.3
```
