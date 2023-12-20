# ***divan*** 

# Description
*divan* is intended to aid researchers and students in performing exploratory functional diversity (FD) analyses. The layout is based on the steps 3-7 proposed in Palacio et al. (2022), and works mainly as an exploration and interactive data tool. To perform a rigorous functional diversity data analysis, we suggest the user referring to several packages already available.

# Installation
To use this app locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/facuxpalacio/divan.git


2. **Install required packages**
```
# Navigate to the app directory
setwd("divan")

# Install necessary R packages
install.packages(c("shiny", "other_required_packages"))
```

Usage
To run the app, open the app.R file in RStudio and click on the 'Run App' button. Alternatively, you can run the following command in your R environment:

```
# Load the Shiny library
library(shiny)

# Run the app
shiny::runApp()
```

# Folder Structure
app.R: Contains the main Shiny app code.
data/: Stores any necessary datasets or files.

# Contributing
Contributions are welcome! If you want to improve the app or fix any issues, feel free to create an issue or submit a pull request.

# License
The web-based application is entirely based on Shiny, an open source R package (R 4.2.3, R Core Team 2023). The full list and version of each R package used can be found in the code available at https://github.com/facuxpalacio/divan/tree/main/R. 

# Contact
If you have any questions or suggestions, feel free to contact Facundo X. Palacio at facundo_palacio@fcnym.unlp.eduar.


