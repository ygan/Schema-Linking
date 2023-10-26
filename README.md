# Schema-Linking
For paper: Re-appraising the Schema Linking for Text-to-SQL


This repository contains data for the ACL 2023 findings paper ["Re-appraising the Schema Linking for Text-to-SQL"](https://aclanthology.org/2023.findings-acl.53/).

If you use the data in your work, please cite it as follows:
``` bibtex
@inproceedings{gan-etal-2023-appraising,
    title = "Re-appraising the Schema Linking for Text-to-{SQL}",
    author = "Gan, Yujian  and
      Chen, Xinyun  and
      Purver, Matthew",
    booktitle = "Findings of the Association for Computational Linguistics: ACL 2023",
    month = jul,
    year = "2023",
    address = "Toronto, Canada",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.findings-acl.53",
    doi = "10.18653/v1/2023.findings-acl.53",
    pages = "835--852",
}
}
```


## Exact Match Grammar Linking labels
You can locate the code for generating Exact Match Grammar Linking labels within the [NatSQL](https://github.com/ygan/NatSQL) generation code. After you finish the first step of 'preprocess the dataset' in [NatSQL](https://github.com/ygan/NatSQL), you will obtain the pattern_tok attribute in the processed data, and the data within this attribute are the Exact Match Grammar Linking labels.


## Spider T1 to T5
Replace the tables.json file in the original dataset with the one from the ```Spider-T1~5``` folder to obtain the experimental environment for Spider-T1 to T5.