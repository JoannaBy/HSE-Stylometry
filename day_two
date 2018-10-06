# Day Two - Stylometry in Authorship Attribution

## Classify
Create two folders:
* primary_set
* secondary_set
Put the texts you want to examine into *secondary_set*, and the other texts by candidate authors into *primary_set*.

The command is **classify()** and offers gui.

## Rolling classify
Create two folders:  
* reference_set
* test_set
Put the text you want to examine into *test set* and other texts by candidate authors into *reference_set*.
  
The basic command is **rolling.classify()**  
You can modify it by putting parameters in the brackets, e.g.:  
When you're using language other than English:  
  rolling.classify(corpus.lang="Other")

Now try another classification method, e.g. SVM (Support Vector Machine):
  rolling.classify(corpus.lang="Other", classification.method="SVM")
  
Surely, you want a picture?
  rolling.classify(corpus.lang="Other", classification.method="SVM", write.png.file="TRUE")
  
You can find more options at p. 58 of the [documentation](https://cran.r-project.org/web/packages/stylo/stylo.pdf) and easy detailed explanations in [HOWTO](https://sites.google.com/site/computationalstylistics/stylo/stylo_howto.pdf).

## Are you looking for more?
Check CSG tutorials on [cross-validation](https://computationalstylistics.github.io/blog/cross-validation/) and [authorship verification](https://computationalstylistics.github.io/blog/imposters/)


