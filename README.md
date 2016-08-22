# Flood_forecasting
A Shiny app to present flood forecasting results at NVE.
If you find a bug or think of an interesting new feature, please file a new [issue](https://github.com/fbaffie/Flood_forecasting/issues). Please refer to the guidelines for filing issues at the end of this readme.

## Aim
Provide the flood forecasters with an easy to use and customizable graphical user interface (GUI) for flood forecasting and model evaluation.

## Running the app

```R
# Create a folder where the data computed by the app will be saved, open RStudio and make sure the working directory is the folder you created:
setwd("C:/YOURPATH")

# Then install the "shiny" package. Open RStudio, go to Tools -> Install packages and type "shiny"
# If it is the first package you install I will likely suggest a path to install future packages. It is usually a sensible path, so check and click accept.

# Another way to install the package is to type
install.packages('shiny')
# But this command chooses strange default paths so please use the RStudio buttons for installing your first package.

# Then load the package and run the app:
library(shiny)
runGitHub("Flood_forecasting", "fbaffie", ref = "operational_manual")
# If you want to update the data used by the app, first press the "Stop" button on RStudio to stop the app. Then run again:
library(shiny)
runGitHub("Flood_forecasting", "fbaffie", ref = "operational_manual")
```

## Filing issues

Please try to follow those guidelines for filing issues:

One issue for one purpose. Don't add more than one bug, feature request, documentation request, question, etc.. on to the same issue.

- If you've found a bug, thanks for reporting!
- If you've a request of some kind, e.g., feature request or documentation request, it'd be much appreciated if you could add **[Request]** at the beginning of the title. This helps us to prioritise easily without having to go through the entire issue.
- If you need support, e.g., installation issues or upgrade issues, please add **[Support]** at the beginning of the title. This helps us to easily identify the most common support issues, and provide solutions in a separate page.
- If you have a general question, add **[Question]** at the beginning of the title.
- If you've an issue that doesn't fall into any of these categories, then it'd be helpful if you could add **[Misc]** to your title.
