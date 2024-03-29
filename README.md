


```
r language BS14, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis miksoid adenoma, karaciğer TR, echo = (language == "TR")
## BS14 - miksoid adenoma, karaciğer {#sec-BS14 }
```


```
asis myxoid adenomatosis, liver EN, echo = (language == "EN")
## BS14 - myxoid adenomatosis, liver {#sec-BS14 }
```






```
r BS14 screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS14-HE_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS14/HE.html",
  file = "./screenshots/BS14-HE_screenshot.png"
)
}
```





::::: panel-tabset


### WSI - Link










https://images.patolojiatlasi.com/BS14/HE.html





```
asis, echo = (language == "TR")

**miksoid adenoma, karaciğer**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS14-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS14/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS14/HE.html)
```

```
asis, echo = (language == "EN")

**myxoid adenomatosis, liver**

[![Click for Full Screen WSI](./screenshots/BS14-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS14/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS14/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS14/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS14/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

miksoid adenoma, karaciğer

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

myxoid adenomatosis, liver

:::

```









:::::









