# REMEMBER to restart R after you modify and save this file!

# First, execute the global .Rprofile if it exists. You may configure blogdown
# options there, too, so they apply to any blogdown projects. Feel free to
# ignore this part if it sounds too complicated to you.
if (file.exists("~/.Rprofile")) {
  base::sys.source("~/.Rprofile", envir = environment())
}

# Now set options to customize the behaviour of blogdown for this project. Below
# are a few sample options; for more options, see
# https://bookdown.org/yihui/blogdown/global-options.html
options(
  # Post settings
  blogdown.author = "Tomas Stevens",
  blogdown.ext = ".Rmd",
  blogdown.yaml.empty = TRUE,
  blogdown.subdir = "post",
  blogdown.title_case = TRUE,
  # Fix hugo version
  blogdown.hugo.version = "0.81.0",
  # Page bundles (hugo functionality)
  # Source: https://alison.rbind.io/post/2019-02-21-hugo-page-bundles/
  blogdown.new_bundle = TRUE,
  blogdown.knit.on_save = FALSE,
  blogdown.method = "html",
  blogdown.serve_site.startup = FALSE,
  # Use md5sum to rebuild (see ?blogdown::build_site)
  blogdown.files_filter = blogdown::filter_md5sum
)
