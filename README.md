# Davinci scripts
 Davinci custom scripts

## Notes and tutorials:

- [Doc for python scripting](https://deric.github.io/DaVinciResolve-API-Docs/)

- [Davinci Resolve Wesuckless forum](https://www.steakunderwater.com/wesuckless/viewforum.php?f=46)

- [DaVinci-Resolve-Utilities](https://github.com/jjsawdon/DaVinci-Resolve-Utilities)

- [Reactor 3 : Scripts library and installer ](https://www.steakunderwater.com/wesuckless/viewtopic.php?t=3067)

- [Official examples](https://github.com/deric/DaVinciResolve-API-Docs/tree/main/examples/python)

- How to Get the Duration of the Current Video Item in console

```python
pprint.pp(resolve.GetProjectManager().GetCurrentProject().GetCurrentTimeline().GetCurrentVideoItem().GetDuration())
```

- Location of the scripts

```
C:\Users\${Username}\AppData\Roaming\Blackmagic Design\DaVinci Resolve\Support\Fusion\Scripts
```

