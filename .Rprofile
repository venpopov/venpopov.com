source("renv/activate.R")

# Force source installation in CI to avoid pre-built binary compatibility issues
# (e.g. rstan binary compiled against older TBB ABI than the system provides)
if (isTRUE(as.logical(Sys.getenv("CI")))) {
  options(pkgType = "source")
}
