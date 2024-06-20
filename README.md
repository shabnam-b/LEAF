# LEAF: Language Learners' English Essays and Feedback Corpus


This repository provides the dataset introduced our NAACL 2024 paper:

> [ELEAF: Language Learners' English Essays and Feedback Corpus](https://aclanthology.org/2024.naacl-short.36/) <br><br>
> [Shabnam Behzad](https://shabnam-b.github.io/), Omid Kashefi, Swapna Somasundaran. <br>





The second verion of the LEAF dataset is avaible as data.jsonl <br><br> AI-Augmented feedback will be added soon!<br><br>
Changes we made compared to what is described in the paper: <br>
- Only feedback comments from Educational Consultant Mary Rose are included in the dataset to ensure higher quality feedback, so this version is a little smaller than what is reported in the paper. <br>
- Splits are now 500/400/4018 test/dev/train <br><br>


Note: We made extensive efforts to remove noise, forum-related information, and personal names from the data using heuristics and named entity recognition systems. However, some may still remain. Additionally, students insert essay prompts in various locations. While we have attempted to address these variations, prompts might still appear at the beginning of the essay_text in some instances.<br>

## License
Essayforum.com has the following terms of use:<br><br>
*Once you have made a post on the EssayForum.com website, you consent to us dealing with it (within and outside
of the forums) as we see fit. By submitting your post, you agree to grant us a royalty-free, perpetual, non-exclusive,
unrestricted, worldwide license to use, reproduce, modify, adapt, translate, enhance, transmit, distribute, publicly
perform, display, or sublicense any such content in any medium (now in existence or hereinafter developed) and
for any purpose, including commercial purposes, and to authorize others to do so. Unless you complete the thread
deletion procedure (which is free only if no other members posted in your thread and requires a fee if other users
answered your question), you cannot withdraw or retract the post. You cannot seek payments from us in relation to
this licence at any time now or in the future. If you do not want your post to be used in this or any other way that we
may find appropriate you should not post it on EssayForum.com.*<br><br>
Nevertheless, we contacted them, asking if their data could be shared and used for **research purposes**.
They responded: “You can use the data as long as you reference it to our site.”

## Citation
If you find this work useful for your work, please cite our paper:

```
@inproceedings{behzad-etal-2024-leaf,
    title = "{LEAF}: Language Learners{'} {E}nglish Essays and Feedback Corpus",
    author = "Behzad, Shabnam  and
      Kashefi, Omid  and
      Somasundaran, Swapna",
    editor = "Duh, Kevin  and
      Gomez, Helena  and
      Bethard, Steven",
    booktitle = "Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies (Volume 2: Short Papers)",
    month = jun,
    year = "2024",
    address = "Mexico City, Mexico",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.naacl-short.36",
    pages = "433--442",
}
```

