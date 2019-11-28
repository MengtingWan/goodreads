# [Goodreads Datasets](https://sites.google.com/eng.ucsd.edu/ucsdbookgraph/home)

The datasets were collected in late 2017 from [goodreads](https://goodreads.com). Details of the datasets are described in the [dataset website](https://sites.google.com/eng.ucsd.edu/ucsdbookgraph/home)

**We collected these datasets for academic use only! Please do not redistribute them or use for commercial purposes.**

## Citations
If you are using our dataset, please cite the following papers:

- Mengting Wan, Julian McAuley, "[Item Recommendation on Monotonic Behavior Chains](https://github.com/MengtingWan/mengtingwan.github.io/raw/master/paper/recsys18_mwan.pdf)", in RecSys'18. [[bibtex](https://dblp.uni-trier.de/rec/bibtex/conf/recsys/WanM18)]
- Mengting Wan, Rishabh Misra, Ndapa Nakashole, Julian McAuley, "[Fine-Grained Spoiler Detection from Large-Scale Review Corpora](https://github.com/MengtingWan/mengtingwan.github.io/raw/master/paper/acl19_mwan.pdf)", in ACL'19. [[bibtex](https://dblp.uni-trier.de/rec/bibtex/conf/acl/WanMNM19)]



## Notebooks/Code Samples

We've created several notebooks (in python 3.7) to illustrate how to download/read these datasets, and provide some basic explorations of the data.

- [download.ipynb](/download.ipynb): If you prefer to download datasets without GUI. This notebook will show how to download files in bash/python. **Note: It requires installing the [gdown](https://github.com/wkentaro/gdown) package as the datasets are hosted on google drive.**
- [samples.ipynb](/samples.ipynb): This notebook will show how to read '.json.gz' files line-by-line and display sample records of each file.
- [statistics.ipynb](/statistics.ipynb): This notebook will calculate some basic statistics of the datasets (except the largest complete interaction file 'goodreads_interactions.csv'). Running this notebook may take a while.
- [distributions.ipynb](/distributions.ipynb): This notebook will operate on the complete interaction file 'goodreads_interactions.csv' and provide some explorations of the distributions of these interactions. **Note: Run this notebook only when you have LARGE memory (recommend 32g+)!!**
- [reviews.ipynb](/reviews.ipynb): This notebook will calculate some statistics of the review datasets.

