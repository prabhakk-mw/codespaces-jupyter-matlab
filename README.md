# GitHub Codespaces ♥️ Jupyter Notebooks

Welcome to your shiny new codespace! We've got everything fired up and running for you to explore Python and Jupyter notebooks.

You've got a blank canvas to work on from a git perspective as well. There's a single initial commit with what you're seeing right now - where you go from here is up to you!

Everything you do here is contained within this one codespace. There is no repository on GitHub yet. If and when you’re ready you can click "Publish Branch" and we’ll create your repository and push up your project. If you were just exploring then and have no further need for this code then you can simply delete your codespace and it's gone forever.

The permissions that exist in the folder hierarchy persists when a Dev Container is created.
However the user in the container, in this case "codespace" does not have write access by default.

Updated the permissions to the folders notebooks & data using 
```bash
chmod a=rwx notebooks/ data/
```
