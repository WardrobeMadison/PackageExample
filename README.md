# PackageExample

## Usage 
1. Clone repository. .
2. Download packages. 
3. Download pyinstaller. 
4. Run ```pyinstaller -w -F --add-data "apps;apps" --add-data "assets;assets" index.py```. 

For use with, pythondotnet, use

```pyinstaller -w -F --add-data "apps;apps" --add-data "assets;assets"  --hidden-import=clr index.py```

## Sturcturing 
For large-multi-page apps, use this structure. 

-- Multi-Page-App/
  -- index.py
  -- app.py
  -- apps
      -- pages/
      -- objects/ 
  -- assets/
