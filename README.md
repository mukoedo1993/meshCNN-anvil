# meshCNN-anvil
### My attempt to run https://github.com/ranahanocka/MeshCNN

Step 1: Jump to the working directory:
git clone https://github.com/ranahanocka/MeshCNN.git
cd MeshCNN

Step 2: Manually Create a New Conda Environment:
conda create -n meshcnn python=3.8 -y
conda activate meshcnn

Step 3: Install PyTorch  (Temporally, On CPU only):
pip install torch==1.9.1 torchvision==0.10.1 torchaudio==0.9.1

Step 4: Install MeshCNN Requirements:
pip install numpy scipy matplotlib scikit-image tqdm trimesh cython
pip install git+https://github.com/TheFrenchLeaf/gdist.git

Step 5: Still in the MeshCNN environment:
pip install numpy scipy matplotlib scikit-image tqdm trimesh cython
# Skip gdist


Step 6: training:
#failing on running the line of code below: 
#bash ./scripts/shrec/test.sh #Not runnable
