# GitHub Pages

Instructions for setting up GitHub Pages
- in the project
  - create the ```./gh-pages``` folder
  - create the ```./gh-pages/README.MD``` file
- on GitHub, go to ```settings``` -> ```pages```
- under ```Build and Deployment```, change the ```source``` to ```GitHub Actions```
- under ```GitHub Pages Jekyll```, click on ```configure```
- under ```jobs``` -> ```build``` -> ```steps``` -> ```with```, change the ```source``` to ```./gh-pages```
