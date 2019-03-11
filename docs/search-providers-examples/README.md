To install one of these search providers, put its entire folder in `~/.local/share/cinnamon/search_providers` and enable the search provider.

The applet "Cinnamenu" offers a GUI to enable search providers, otherwise the list of active search providers can be set like this:

    gsettings set org.cinnamon enabled-search-providers [\"apt@cinnamon.org\",\"calc@cinnamon.org\"]

Finally, restart Cinnamon, for example by right-clicking the panel and selecting "Troubleshoot"->"Restart Cinnamon".
