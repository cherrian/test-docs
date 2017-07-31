# Draw.io GitHub Integration

[Phase 2 doc](phase2/grpc.md)

GitHub support is now available https://www.draw.io/?mode=github An example for integration into GitHub wikis is available here: https://github.com/jgraph/draw.io/wiki/Embed-Diagrams!

--

![Diagram](http://jgraph.github.io/drawio-github/diagram.png)

<a href="http://jgraph.github.io/drawio-github/edit-diagram.html?repo=drawio-github&path=diagram.png" target="_blank">Edit</a> | <a href="https://www.draw.io/?url=http%3A%2F%2Fjgraph.github.io%2Fdrawio-github%2Fdiagram.png" target="_blank">Edit As New</a>

<a href="http://jgraph.github.io/drawio-github/edit-diagram.html" target="_blank">edit-diagram.html</a> does the I/O with GitHub and uses draw.io in embed mode for diagram editing. The page supports the following URL parameters: user, pass, repo, path, ref and action=open (the Edit link above is an example). Using action=open, links for immediate diagram editing in GitHub can be created (requires user and pass parameters). You can also use files on GitHub as templates in draw.io via the url parameter (see Edit As New above).