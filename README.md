# GBD1



**GBD1 for pathology atlas repositories**



```{r language GBD1, echo=FALSE, include=TRUE}
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```




```{asis, echo = (language == "TR")}
## pediatrik otopsi, beyin {#sec-GBD1}
```


```{asis, echo = (language == "EN")}
## pediatric autopsy, brain {#sec-GBD1}
```


```{r GBD1 screenshot, eval=TRUE, include=FALSE}
if (!file.exists("./screenshots/GBD1_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/GBD1/HE.html",
  file = "./screenshots/GBD1_screenshot.png"
)
}
```

```{r, echo=FALSE, include=FALSE, eval=FALSE}
knitr::include_url(url = "https://images.patolojiatlasi.com/GBD1/HE.html")
```

```{r, echo=FALSE, include=FALSE, eval=FALSE}
#| label: GBD1_screenshot
#| fig-cap: "pediatrik otopsi, beyin"
knitr::include_graphics("./screenshots/GBD1_screenshot.png")
```


::: {.content-hidden when-format="html"}
pediatrik otopsi, beyin
:::

::: {.content-visible when-format="pdf"}
pediatrik otopsi, beyin
:::



```{asis, echo = (language == "TR")}

**pediatrik otopsi, beyin**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/GBD1_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/GBD1/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/GBD1/HE.html)
```


```{asis, echo = ((language=="TR") & (output_type=="html"))}
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/GBD1/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```



```{comment} 
asis, echo = (language == "TR")

**pediatrik otopsi, beyin**


[![İşaretlenmiş mikroskopik görüntüleri Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/GBD1_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/GBD1/HE_annotated.html) [İşaretlenmiş mikroskopik görüntüleri Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/GBD1/HE_annotated.html)

İşaretlenmiş mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/GBD1/HE_annotated.html" style="height:600px;width:100%;" data-external="1"></iframe>

```



```{comment}
asis, echo = (language == "TR")



<button id="tani-case-GBD1-btn">Tanıyı Göster</button>
<div id="answer-GBD1" style="display: none;">pediatrik otopsi, beyin</div>

<script>
  const showAnswer-GBD1Btn = document.getElementById('tani-case-GBD1-btn');
  const answer-GBD1 = document.getElementById('answer-GBD1');

  showAnswer-GBD1Btn.addEventListener('click', () => {
    if (answer-GBD1.style.display === 'none') {
      answer-GBD1.style.display = 'block';
      showAnswer-GBD1Btn.textContent = 'Tanıyı Gizle';
    } else {
      answer-GBD1.style.display = 'none';
      showAnswer-GBD1Btn.textContent = 'Tanıyı Göster';
    }
  });
</script>

```

```{comment}
asis, echo = ((language=="TR") & (output_type=="html"))

{{< video https://www.youtube.com/embed/ >}}

```

```{comment}
asis, echo = ((language=="TR") & (output_type!="html"))

[https://www.youtube.com/watch?v=](https://www.youtube.com/watch?v=)

```





```{asis, echo = (language == "EN")}

**pediatric autopsy, brain**

[![Click for Full Screen WSI](./screenshots/GBD1_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/GBD1/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/GBD1/HE.html)


```



```{asis, echo = ((language == "EN") & (output_type=="html"))} 

See Microscopy with viewer: 

<iframe src="https://images.patolojiatlasi.com/GBD1/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```


```{comment}
asis, echo = (language == "EN")

**pediatric autopsy, brain**

[![Click for Full Screen Annotated WSI](./screenshots/GBD1_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/GBD1/HE_annotated.html) [Click for Full Screen Annotated WSI](https://images.patolojiatlasi.com/GBD1/HE_annotated.html)


See Annotated Microscopy with viewer: 

<iframe src="https://images.patolojiatlasi.com/GBD1/HE_annotated.html" style="height:600px;width:100%;" data-external="1"></iframe>



```

```{comment}
asis, echo = (language == "EN")

<button id="dx-case-GBD1-btn">Show the Diagnosis</button>
<div id="answer-GBD1" style="display: none;">pediatric autopsy, brain</div>

<script>
  const showAnswer-GBD1Btn = document.getElementById('dx-case-GBD1-btn');
  const answer-GBD1 = document.getElementById('answer-GBD1');

  showAnswer-GBD1Btn.addEventListener('click', () => {
    if (answer-GBD1.style.display === 'none') {
      answer-GBD1.style.display = 'block';
      showAnswer-GBD1Btn.textContent = 'Hide the Diagnosis';
    } else {
      answer-GBD1.style.display = 'none';
      showAnswer-GBD1Btn.textContent = 'Show the Diagnosis';
    }
  });
</script>

```


```{comment}
r, eval=TRUE, echo=FALSE, include=FALSE, error=TRUE
if (!file.exists("./screenshots/GBD1_screenshot.png")) {

url <- "https://img.youtube.com/vi/U9glkfQLTm4/maxresdefault.jpg"
download.file(url, destfile = "./screenshots/GBD1_screenshot.png", mode = "wb")
}

**pediatrik otopsi, beyin**

[![Video İçin Tıklayın](./screenshots/GBD1_screenshot.png){width="25%"}](https://www.youtube.com/watch?v=) [Video İçin Tıklayın](https://www.youtube.com/watch?v=)

```




```{comment}
asis, echo = ((language=="EN") & (output_type=="html"))

{{< video https://www.youtube.com/embed/ >}}

```

```{comment}
asis, echo = ((language=="EN") & (output_type!="html"))

[https://www.youtube.com/watch?v=](https://www.youtube.com/watch?v=)

```


```{comment}
=html
<iframe src="https://images.patolojiatlasi.com/GBD1/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>
```
