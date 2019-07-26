# Radar Plot / Spider Plot code for cluster analysis

Get the code in the notebook.

```
def plot_cluster_radar(data, cluster_label, features=None, center=np.mean)
```

**data** : Pandas Dataframe, Numpy

**cluster_label**  : cluster / group field name or list of clusters with matching length

**features** : attribute field to aggregate and show. Default to all fields other than the cluster field specified

**center**  : desired aggregation like mean, np.median or any method that return a numeric value. Currently this value will apply to ALL attribute fields. Default to np.mean
