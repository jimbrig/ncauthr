source("renv/activate.R")

# history -----------------------------------------------------------------

# setup project level Rhistory

.Last <- function() {

  if (interactive()) {
    try(
      utils::savehistory(
        file = file.path(getwd(), ".Rhistory")
      )
    )
  }

}

if (interactive()) {
  try(
    utils::loadhistory(
      file = file.path(getwd(), ".Rhistory")
    )
  )
}
