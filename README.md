# ObservableHq to Local

Based on the work of [https://github.com/Fil/SphericalContoursStandalone](https://github.com/Fil/SphericalContoursStandalone)

changes are to make suitable to every plot.

1. change repository name in package.json under config_notebook

2. If plot has:  
    a. ```data = FileAttachment("flare-2.json").json()``` download the data, create and place in folder files with name: "e65374209781891f37dea1e7a6e1c5e020a3009b8aedf113b4c80942018887a1176ad4945cf14444603ff91d3da371b3b0d72419fa8d2ee0f6e815732475d5de" with no extension  
    b. ```points = d3.json(
  "https://gist.githubusercontent.com/Fil/6bc12c535edc3602813a6ef2d1c73891/raw/3ae88bf307e740ddc020303ea95d7d2ecdec0d19/points.json"
)``` then change fetchalias.json to fit the data
3. ```yarn setup```
4. ```yarn serve``` and go to http://127.0.0.1:8080