# Goodnight Moon AR Translator (View Master Branch for Code)

## Inspiration
When we saw the available categories for recognition at the beginning of KnightHacks, we decided that we wanted to pursue something using Augmented Reality. We'd need something with lots of vivid imagery for plane recognition, so we opted to go with modifying a children's book in some way. In the end we settled on making a translation for the book "Goodnight Moon" as a start to this project.

## What Do?
The app recognizes the pages of the book "Goodnight Moon" and will display a Spanish translation that hovers over each snippet of text in the book.

## How It's Made {Software_Version}
First, we needed to get the book's pages and convert them into capture targets by mapping out key features on the page; we chose to use Vuforia as the software took care of the mapping was easy to integrate into Unity. From there, we created .png files to use as the text translations that we converted to sprites and paired with their respective pages. To port the Unity project to an Android, we simply had to switch our platform and upload to an Android device and test the app using the device's camera.

## Challenges
Version control ended up being a big roadblock in trying to collaborate on the same Unity scene at the same time; to avoid wasting any more time than necessary, we split up the remaining tasks among ourselves and worked. Every asset that was completed was sent to the person working on the Unity scene at the moment who would then stitch it into wherever it needed to be.

## Accomplishments
None of us have worked with AR before so being able to get an actual functioning AR app is a major accomplishment in itself!

## What We Learned
- How AR application track images
- Using Vuforia to create assets for a capture image
- Creating custom AR interactions for an image

## What's Next?
With more time we'd like to create small 3d dioramas of illustrations that would show up on pages without any text, along with some small adjustments on how we chose to show the text/3d model details to engage the user more. Additionally, expanding the app to more children's books would be a goal to look forward to.

# Want to use it Yourself?

1. Download the folder from this Github!
2. Open your Unity Hub and click on "Add" -> Find the project folder in your downloads
   * Ensure that your version of Unity has the Android Development and Vuforia modules!
   
3. After opening, go to "File" -> "Build Settings" -> "Player Settings" -> Enable Vuforia on each platform module and disable Android TV compatability
4. Connect your Android device via USB
   * Ensure your Android device has Developer Mode and USB Debugging on!
   
5. hit "Build and Run" and wait for the app to show up on your device!
