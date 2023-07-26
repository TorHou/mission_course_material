__commands__

```
(mlst)$ mlst --legacy --nopath --scheme senterica_achtman_2 Assemblies/*.fa > mlst.profile
```

to get rid of extra columns

```
$ cut -f1,4,5,6,7,8,8,9,10 mlst.profile > mlst.cut.profile
```

visualize

```
(grapetree)$ grapetree --profile mlst.cut.profile > mlst.cut.newick
```
