# N741 - Interactive tools - htmlwidgets and flexdashboard

## `htmlwidgets` for R

`htmlwidgets` allows you to utilize JavaScript data visualization methods to enhance your reports and results displays. To learn more, see [http://www.htmlwidgets.org/index.html](http://www.htmlwidgets.org/index.html)

To see the interactive HTML widgets example using the Pesticide dataset, go to [https://cdn.rawgit.com/melindahiggins2000/N741interactive/master/htmlwidget_DTdemo.html](https://cdn.rawgit.com/melindahiggins2000/N741interactive/master/htmlwidget_DTdemo.html).

## `flexdashboard`

`flexdashboard` is a R package you install to publish groups of data visualizations together. These visualizations can be static or dynamic. The example shown in this example using the Pesticides dataset is static, but dynamic examples use `shiny`. Learn more at [http://rmarkdown.rstudio.com/flexdashboard/](http://rmarkdown.rstudio.com/flexdashboard/).

To see today's example for the interactive `flexdashboard` with the Pesticides dataset go to [https://cdn.rawgit.com/melindahiggins2000/N741interactive/master/flexdashboard_demo2.html](https://cdn.rawgit.com/melindahiggins2000/N741interactive/master/flexdashboard_demo2.html).

## Knit with Parameters

Learn more about the `params` feature at [http://rmarkdown.rstudio.com/developer_parameterized_reports.html](http://rmarkdown.rstudio.com/developer_parameterized_reports.html).

This basically consists of adding the `params` option to your YAML code at the top of the RMD (`Rmarkdown`) file. Once this feature is added, the arguments can be passed by calling `rmarkdown::render()` and setting the options to what you want. However, once the YAML is setup, a list of choices for the `params` option can be provided and when you click "Knit with parameters" a GUI window pops-up with a pull down list (or other selection types) and you can pick which parameter setting you want for your customized report. See the screen shot of this GUI for the demo below.

![Knit with Parameters GUI](knitWparams.jpg)

See today's example with "knit with parameters" see [https://cdn.rawgit.com/melindahiggins2000/N741interactive/master/parametersTemplate.html](https://cdn.rawgit.com/melindahiggins2000/N741interactive/master/parametersTemplate.html).