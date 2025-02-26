Code for the paper [Semantic Triples Verbalization with Generative Pre-Training Model](https://aclanthology.org/2020.webnlg-1.17.pdf) by Pavel Blinov.

[Video](https://youtu.be/CR0SjX2fnHo)

### How to run
0. Clone the repo.
1. Check requirements / install with `pip install -r requirements.txt`.
2. Download pre-trained model (file `pytorch_model.bin`) from https://huggingface.co/blinoff/ru-gpt2-medium-rdf-2-text to `ru-gpt2-medium-rdf-2-text/`.
3. Open `run_test_for_webnlg.ipynb` and run all cells.

### BibTeX reference
```
@inproceedings{blinov-2020-semantic,
    title = "Semantic Triples Verbalization with Generative Pre-Training Model",
    author = "Blinov, Pavel",
    editor = "Castro Ferreira, Thiago  and
      Gardent, Claire  and
      Ilinykh, Nikolai  and
      van der Lee, Chris  and
      Mille, Simon  and
      Moussallem, Diego  and
      Shimorina, Anastasia",
    booktitle = "Proceedings of the 3rd International Workshop on Natural Language Generation from the Semantic Web (WebNLG+)",
    month = "12",
    year = "2020",
    address = "Dublin, Ireland (Virtual)",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2020.webnlg-1.17/",
    pages = "154--158"
}
```
