# Radar Plot / Spider Plot code for cluster analysis

Get the code in the notebook.

```
def plot_cluster_radar(data, cluster_label, features=None, center=np.mean, ax=None, figsize=(8,8), legend_loc=(1.3,0.9), legend_labels=None)
```

**data** : Pandas Dataframe, Numpy

**cluster_label**  : cluster / group field name or list of clusters with matching length

**features** : attribute field to aggregate and show. Default to all fields other than the cluster field specified

**center**  : desired aggregation like mean, np.median or any method that return a numeric value. Currently this value will apply to ALL attribute fields. Default to np.mean

![24 hours](https://github.com/jasonlcy91/Radar-plot-Spider-plot-python-code/blob/master/image1_24hours.png)
![Weather clusters](https://github.com/jasonlcy91/Radar-plot-Spider-plot-python-code/blob/master/image2_weather_clusters.png)
