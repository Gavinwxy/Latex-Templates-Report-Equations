#Pseudocode

Two main ways provided

1. **algorithm** & **algorithmicx**

   ```latex
   \usepackage{algorithm}  
   \usepackage{algorithmicx}  
   \usepackage{algpseudocode}  
   \usepackage{amsmath}  
   \renewcommand{\algorithmicrequire}{\textbf{Input:}}  % Use Input in the format of Algorithm 
   \renewcommand{\algorithmicensure}{\textbf{Output:}} % Use Output in the format of Algorithm 
   ```

2. **algorithm2e**

   It needs presetting

   ```latex
   \makeatletter  
   \newif\if@restonecol  
   \makeatother  
   \let\algorithm\relax  
   \let\endalgorithm\relax  
   \usepackage[linesnumbered,ruled,vlined]{algorithm2e}%[ruled,vlined]{  
   \usepackage{algpseudocode}  
   \usepackage{amsmath}  
   \renewcommand{\algorithmicrequire}{\textbf{Input:}}  % Use Input in the format of Algorithm 
   \renewcommand{\algorithmicensure}{\textbf{Output:}} % Use Output in the format of Algorithm 
   ```

   ​