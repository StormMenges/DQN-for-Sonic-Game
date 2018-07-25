# DQN-for-Sonic-Game
Me and my partner made a DQN for sonic to learn to play by itself 
The following packages need to be installed:
  gym-retro
  gym-retro local (from open AI website that is used for the competition)
  pytorch
  torchvision
  OpenCV
  tqdm
  python3

  pip3 install --user torch torchvision gym tqdm opencv-python gym-retro
  git clone --recursive https://github.com/openai/retro-contest.git
  pip3 install -e "retro-contest/support[docker,rest]"

The ROM for the game being used needs to be imported into the gym-retro emunlator before running the agent
  python3 -m retro.import <path to ROM>
  *Note: The ROM needs to be of format .md
        This means it needs to be a Japanese ROM

More Details can be found here :
  https://contest.openai.com/details

Due to the large size of the Q-arrays obtained from training, the files could not
be included with this zip file.

PLEASE NOTE : all elements inside the retro-contest file are not property of this repository holder and are property of OpenAI
