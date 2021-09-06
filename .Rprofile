options(
  blogdown.yaml.empty = FALSE, blogdown.rename_file = TRUE,
  blogdown.title_case = function(x) {
    # if the title is pure ASCII, use title case
    if (xfun::is_ascii(x)) tools::toTitleCase(x) else x
  },
  blogdown.generator.server = TRUE,
  blogdown.hugo.server = c('-D', '-F', '--navigateToChanged')
)
options(blogdown.hugo.version = "0.58.3")
