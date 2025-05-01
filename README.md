# meshCNN-anvil
### My attempt to run https://github.com/ranahanocka/MeshCNN

## Step 1: Clone git repo.
`git clone https://github.com/ranahanocka/MeshCNN.git`

## Step 2: Fetch data.
`bash ./scripts/shrec/get_data.sh`

## Step 3: fixed conda directory
### Warning: I tried a lot but still faced a lot of data quota exceeding warnings.
```CONDA_PKGS_DIRS=/[your-project-directory]/conda/pkgs \
conda env create -f environment_fixed.yml```

