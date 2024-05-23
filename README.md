Hello!

Thank you for making it this far into the repo. This project is going to be under fast-paced development, so please do check in quickly to keep up. But not too much or I might get performance anxiety - you know, 9/10 men etc.

But on a more serious note, this is a very experimental project. I do not make any claims on the scientific accuracy of any of the results produced by running programs in this repo, nor do I take any stance on the actual matter of domestics migration in Finland.
This repo is merely intended for the completion of a class project related to a subject that I found personally interesting, and related to which there were copious datasets available.
So don't come @ me, etc.

That being said, if you take a look and see something funky, let me know! I will be working solo on this one since it's, well, a school project, but happy to take in suggestions.
Just don't try to commit - my professor is already mad it me as is, so I would prefer not having to explain why someone else is contributing to my project at this time.

So yeah, cool, see you around.

Peace and love,
@ihamuma

Libraries used in the project:
- pandas (duh)
- chardet (Finnish tax authority uses some random ass codec)
- csv-detective (Finnish tax authority uses some random ass separator)
- os
- requests
- pyarrow (for fun, to enable parquet file usage)
- matplotlib (thought I was too cool to ever use this - always good to be proven wrong!)
- seaborn (for sweet(er) visuals)
- numpy
- sklearn (for PCA)
- networkx (for, you know. graphs and stuff.)
- gravis (for making networkx graphs interactive)

NB: This project stores data in .parquet, mainly due to personal grievances with .csv not maintaining data types. Many IDEs do not support viewing these by default. In case you wish to see the data in a tabular format, please use an appropriate viewer, or e.g. the VSCode parquet-viewer extension.