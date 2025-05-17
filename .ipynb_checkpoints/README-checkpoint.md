## Validation Data

We put the first volume in the official validation set of the single-coil FastMRI knee dataset inside `data/example/val` folder. Note that the last number denotes the slice number, and that the first five and the last five noisy slices are removed as stated in the paper.


## Repository Structure
All the experiments are issued in the form of self-explanatory `python` codes. To execute each code, we provide python scripts inside `stable-diffusion/scripts/` folder. You can run  `python inverse_fastMRIknee_recon.py --ckpt [LDM_CHECKPOINT_PATH]` for the validation set reconstruction. Currently you can download the LDM checkpoints from https://huggingface.co/stable-diffusion-v1-5/stable-diffusion-v1-5/blob/main/v1-5-pruned-emaonly.ckpt.

## Credits
This codebase is modified based on https://github.com/Z7Gao/MRPD/tree/main. Thanks for creating this awesome repo.

