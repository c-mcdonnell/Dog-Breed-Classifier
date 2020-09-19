# Dog Breed Classifier
## Use a created Python classifier to identify dog breeds from images

The objectives of this project are as follows:
1. Correctly identify which pet images are of dogs and which are not of dogs.
2. For the images that *are* dogs, correctly classify their breed. 
3. Determine which CNN model architecture (image classification algorithm), **AlexNet**, **VGG**, or **ResNet**, works the "best" for classifying the images and how well it works.
4. Consider how long these tasks take and how to maximize time resources and accuracy.

## How it works
### Command Line Arguments
[get_input_args.py](/Dog-Breed-Classifier/blob/master/get_input_args.py)

Use argparse to retrieve three command line arguments from the user.

Inputs:
  - Folder that contains the images
  - Chosen CNN model architecture: resnet, alexnet, or vgg (set one as default)
  - File that contains the list of valid dog names

### Running the Program
- Open a terminal window and navigate to the project directory
- Type in ` python check_images.py ` 
  - This will use the default command line arguments that have been defined
  - To change from defaults: type in ` python check_images.py --your_chosen_arguments`
  - Example: ` python check_images.py --dir different_directory --arch vgg --dogfile different_file.txt` will run in the directory 'different_directory' and use the vgg architecture and the file 'different_file.txt' even if those are not the default parameters.
