# Copier template `default-repository`

Our canonical repository setup which should be used by default for new
repositories.

It is assumed that this will fit most repositories. Use only what's needed from
the template.


## Usage

```
copier copy https://gitlab.gitlab.k0s.lab.bo-tech.de/bv/templates/default-repository.git .
```


## Development

Version bumps:

```
nix run nixpkgs#bump-my-version -- bump patch
```

## Contact

- <joh@bo-tech.de>


## Pointers

- [Copier](https://copier.readthedocs.io/en/stable)
