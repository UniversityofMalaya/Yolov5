# yolov5_FER

# Labeling or Annotating the images
we use tools like [labelimg](https://github.com/heartexlabs/labelImg) to label the images. The images are labeled by the user.

see installation procedure in [README](https://github.com/heartexlabs/labelImg#readme)

# Custom Train 
By creating new configuration yaml file 

# To run this project
by uploading YAML file to this [notebook](https://colab.research.google.com/drive/1f-WJkP0XhVivJqZNriRXpIPak1bHtyON?authuser=1#scrollTo=iBvWcg5NJWZD) and running the code

```bash
python train.py --img 640 --batch 64 --epochs 100 --data FER.yaml 
```
<!-- open in colab generation -->

colab --output_version=1.7 --drive --upgrade_dependencies

[this](https://towardsdatascience.com/the-practical-guide-for-object-detection-with-yolov5-algorithm-74c04aac4843) is the best blog i found to read about training yolov5
