
# Vision-Free Retrieval: Rethinking Multimodal Search with Textual Scene Descriptions

Official repository for the EMNLP 2025 paper.

---

## 📚 Abstract
Contrastively-trained Vision-Language Models (VLMs), such as CLIP, have become the standard approach for learning discriminative vision-language representations. However, these models often exhibit shallow language understanding, manifesting bag-of-words behaviour. These limitations are reinforced by their dual-encoder design, which induces a modality gap. Additionally, the reliance on vast web-collected data corpora for training makes the process computationally expensive and introduces significant privacy concerns.  

To address these limitations, in this work, we challenge the necessity of vision encoders for retrieval tasks by introducing a vision-free, single-encoder retrieval pipeline. Departing from the traditional text-to-image retrieval paradigm, we migrate to a text-to-text paradigm with the assistance of VLLM-generated structured image descriptions. We demonstrate that this paradigm shift has significant advantages, including a substantial reduction of the modality gap, improved compositionality, and better performance on short and long caption queries, all attainable with only few hours of calibration on two GPUs.  

Additionally, substituting raw images with textual descriptions introduces a more privacy-friendly alternative for retrieval. To further assess generalisation and address some of the shortcomings of prior compositionality benchmarks, we release two benchmarks derived from Flickr30k and COCO, containing diverse compositional queries made of short captions, which we coin **subFlickr** and **subCOCO**. Our vision-free retriever matches and often surpasses traditional multimodal models. Importantly, our approach achieves state-of-the-art zero-shot performance on multiple retrieval and compositionality benchmarks, with models as small as **0.3B parameters**.



## 📜 Citation
If you use this work, please cite:  

```bibtex
@inproceedings{ntinou2025visionfree,
  title={Vision-Free Retrieval: Rethinking Multimodal Search with Textual Scene Descriptions},
  author={Ntinou, Ioanna and Xenos, Alexandros and Ouali, Yassine and Bulat, Adrian and Tzimiropoulos, Georgios},
  booktitle={Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing (EMNLP)},
  year={2025}
}
````

---

## 🛠️ Code Release

The code and pretrained models will be released **soon**. Planned resources include:

---

## 📬 Contact

For questions, please contact:
📧 [i.ntinou@qmul.ac.uk](mailto:i.ntinou@qmul.ac.uk)

---

## 🌍 Acknowledgments

This work was partly funded by the **European Union** under the Horizon Europe grant agreement **101135800 (RAIDO)**.

```

Do you want me to also add a **“Teaser Figure” placeholder section** (so later you can drop in a diagram of your pipeline), or keep this README text-only?
```
