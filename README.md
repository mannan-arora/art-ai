
  
## ART AI - Generative NFT Art
<img src="https://i.ibb.co/TYBFzd3/Background.png" width="640" height="360">

ART AI is a program that creates algorithmically generative abstract art work using Python.  This program was used was to generate art work for my first ever NFT collection "ELIX-AI" which is currently available on [OpenSea](https://opensea.io/ELIX-AI).


### Built With
* [Python](https://www.python.org/)
* [Pillow](https://pillow.readthedocs.io/en/stable/)


## Usage

To generate your own art, follow these simple steps.

1. Clone the repo
   ```sh
   git clone https://github.com/mannan-arora/art-ai.git
   ```
2. Install the pillow library
   ```sh
   pip install pillow
   ```
3. Execute the following command. the ``-n`` flag denotes the number of images to be generated and the ``--collection``  flag denotes the name of the art. 
   ```sh
   python art_ai.py -n 10 --collection "test"
   ```
   This execution would create 10 images in a new file with the name ``test_image_n`` where test would be the name provided after the ``collection`` flag and n ranges from 0 to the value provided in the ``-n`` flag.   
