# links.pavalos.xyz

## Workshop

A [Workshop] definition is provided to work in a containerized environment.

To launch the Workshop, run:

```shell
workshop launch
```

To use Workshop within VS Code, see the [Workshop VS Code extension].

## Serve

To serve the pages with [Wrangler] from within the Workshop, run:

```shell
# Action: workshop run wrangler ...
workshop run wrangler pages dev
```

The Workshop configuration will tunnel the necessary ports for the pages to be
accessible outside the Workshop (i.e., from the host).

[workshop vs code extension]: https://marketplace.visualstudio.com/items?itemName=Canonical.workshop
[workshop]: https://ubuntu.com/workshop
[wrangler]: https://developers.cloudflare.com/workers/wrangler/
