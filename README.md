#Python 3.7.16  
Anaconda Shell >  
conda create -n ent3.7.16 python=3.7.16  
conda activate ent3.7.16  
pip install requirements.txt  

python -m pybullet_envs.deep_mimic.testrl --arg_file run_humanoid3d_backflip_args.txt  
run_humanoid3d_jump_args.txt  
run_humanoid3d_spinkick_args.txt  
run_humanoid3d_walk_args.txt  
