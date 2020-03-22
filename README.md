# Balloon Detection

A simple detection model for Balloon detection.

Example result:
![Ballon detection result](https://github.com/GuyChriqui/Balloon_Detection/blob/master/result/result_img.jpg?raw=true)


## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install Balloon Detection.

```bash
pip3 install requirements.txt
```

You can download pre-traind weigths from [here](https://drive.google.com/open?id=1BvUSgcQjQStZ_KaCYjakzfNXBeLrzMvS)
(Locate the weigths in the project root folder)

## Usage

```bash
# Detection on single image
python3 Balloon_Detection.py --image test.jpg

# Detection on video
python3 Balloon_Detection.py --video test.mp4

# Detection from live camera
python3 Balloon_Detection.py --camera 0  # Camera number '0'
```

Edit [this line](https://github.com/GuyChriqui/Balloon_Detection/blob/master/Balloon_Detection.py#L8) in "Balloon_Detection.py" to change confidence threshold:
```python
confThreshold = 0.1  # Confidence threshold
```

## Contributing
Pull requests are welcome. 
For major changes, please open an issue first to discuss what you would like to change.

## License
By the order of the Peaky Blinders
