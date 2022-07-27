# Prerequisites

<b> A RunPod account

Money

Setup

Visit the RunPod Website.

Click 'Secure Cloud'

You will be presented with different machine types. Select the desired type, and click Select.

Under Select a Template, choose Disco Diffusion

Click Ok

Click Continue

Click Deploy Spot or Deploy On-Demand depending on your preference. (spot instances are cheap, but interruptable | on-demand instances are more expensive but non-interruptible)

A modal popup will appear, click My Pods

Click Connect and then click Connect To Jupyter

<b> You are now in Jupyter Notebook within the RunPod Docker Container entmike/disco-diffusion-1! Things may look familiar to you.

In JupyterLab, Click Terminal

Do a test run with python disco.py

Look at your pretty images in images_out start to develop.

Example Commands

<b> Get Help

python disco.py --help


Simple Command Line arguments run

python disco.py --steps 350 --batch_name=simple-example --text_prompts='{"0":["a pretty sailboat floating in the ocean in front of a colorful sunset, trending on artstation"]}'

Run a batch from YAML

python disco.py --config_file=configs/xyz.yaml


<b> ZIP a folder

zip -r downloads.zip images_out/batchname


Notes
Unlike the Lambda Labs guide, at this point you do NOT have to type sudo docker ... commands. All commands simply begin with python disco.py followed by any command-line arguments you wish to pass (or --config_file=path/to/your/config.yaml) for YAML args.
