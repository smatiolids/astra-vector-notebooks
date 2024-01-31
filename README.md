# DataStax AstraDB Vector - Jupyter Notebooks

## Security 
In this notebook, we will leverage the DevOps API to create a role with read access on a colelction, while all the other collections are denied. 
Then, we generate a token for this role and used it to query the allowed and denied collections. As expected, the allowed collection is read succesfully, while we correctly received errors when querying the denied collection.
