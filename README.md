

# 8 Base substitution model including methylated base.

This repository contains scripts to run phylogenetic analyses with methylated base using RAxML-NG.

## 🔹 4-base model (used for topology inference)

Run the script:

```bash
bash 4branch.sh
```

This performs tree topology inference using the GTR model.

## 🔹 8-base model (used fo substitution parameter estimation with methylation)

Run the script:

```sh
bash 8branch.sh
```

This evaluates branch lengths and substitution parameters under the [multi state](https://github.com/amkozlov/raxml-ng/wiki/Input-data#evolutionary-model:~:text=Morphological/multistate) GTR model using a fixed tree topology.

⸻

For detailed usage of RAxML-NG, refer to the official documentation:
👉 https://github.com/amkozlov/raxml-ng/wiki
