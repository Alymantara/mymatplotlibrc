# mymatplotlibrc
My personal matplotlib default file


## Installing Computer Modern
```
sudo apt install fonts-cmu
```

## To re-build the font library within matplotlib:

```python
import matplotlib

matplotlib.font_manager._rebuild()
```

