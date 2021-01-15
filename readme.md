<p align='center'>
  <h2 align="center">lichess gist box</h2>
  <p align="center">♟︎ Update a pinned gist to contain your top Lichess varients' rating</p>
</p>


---

> 📌✨ For more pinned-gist projects like this one, check out: https://github.com/matchai/awesome-pinned-gists

## 🎒 Prep Work

1. Create a new public GitHub Gist (https://gist.github.com/)
2. Create a token with the `gist` scope and copy it. (https://github.com/settings/tokens/new)
3. Copy the `API token`

## 🖥 Project Setup

1. Fork this repo
2. Go to your fork's `Settings` > `Secrets` > `Add a new secret` for each environment secret (below)

## 🤫 Environment Secrets

- **GH_TOKEN:** The GitHub token generated above.
- **GIST_ID:** The ID portion from your gist url:

  `https://gist.github.com/sciencepal/`**`ce5221fc5f3739d2c81ce7db99f17519`**.

  (Alternatively this can be put directly in `.github/workflows/lichess.yml` as it is public anyway.)
- **LICHESS_USERNAME:** Your [lichess.org](https://lichess.org) username. (This can also be put directly in the yml)


## ✨ Credits
This code was heavily inspired (with some code taken over) by [@sciencepal's chess-com-box-py](https://github.com/sciencepal/chess-com-box-py).
